#godotEssentials #programming #godot 

Scripts feitos com GDScript são, implicitamente, classes. GDScripts, por padrão, extendem a classe do [[Node]] que estão conectados. Se você conecta um GDScript a um [[Node]] de sprite2D, ele vai extender a classe do [[Node]]

```GDScript
extends Sprite2D

#Codigo aqui
```

***Importante lembrar***: Quando se extende uma classe, você pega todas as propriedades que aquela classe tem. Então ao se extender de um nó, você tem acesso a todas as propriedades daquele nó, como posição, rotação, etc..., em precisar acessar elas atráves de gets e sets

Caso o script não tenha um "*extend*s", por padrão o Godot vai fazer o script extender da classe [RefCounted](https://docs.godotengine.org/en/stable/classes/class_refcounted.html#class-refcounted), que é utilizada para gerenciar a memória da aplicação.

## Semantica

GDScript é escrito parecido com python, utilizando tabs para definir blocos de código.
## Funções padrões

Todo script tem algumas funções que vão sempre rodar **SE** essas funções forem definidas no código. Essas funções são:

- func \_init(): Roda somente 1 vez quando o script é criado na memória
```GDScript
func _init():
	print ("Olá Jogo!")
```

- func [[_process]](delta): Roda a cada frame do jogo
```GDSCript
func _process(delta):
	print ("Olha eu de novo")
```