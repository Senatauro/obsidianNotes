#godot #godotEssentials #programming

Scripts são a forma de extender as funcionalidades de [[Node]]s existentes ou criar novas funcionalidades por completo. Quando um Script é adicionado a um [[Node]], este recebe por herança todas as funções e propriedades que o [[Node]] que ele está conectado tem.

Um bom exemplo de como isso funciona seria imaginar que você tem uma nave de um jogador, só que você quer que a camera que está seguindo a nave de uma mexida quando o jogador toma dano. Essa funcionalidade não existe por padrão, então é necessário programar isso com um Script

## Linguagens

O [[Godot]] é uma game engine que suporta, oficialmente, 4 linguagens:

Out of the box:
- [[GDScript]]: Uma interpretada linguagem própria do Godot
- C#

Via GDExtension:
- C++
- C

Mas há muitas outras linguagens que são suportadas via plugins da comunidade, como: Rust, Python, Javascript, etc...

É possivel utilizar multiplas linguagens em um unico projeto se necessário.