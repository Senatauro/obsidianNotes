#godot #godotEssentials

Se uma [[Scene]] é a representação de um objeto reutilizavel, [[Node]]s são componentes desse objeto reutilizavel. Ex: Vamos pensar que temos uma scene chamada Player:

- Player (Scene)
	- Camera2D (Node)
	- Sprite2D (Node)
	- CollisionShape2D (Node)

## A base de tudo

Nodes são a base de todo o desenvolvimento de jogos no Godot. Temos que pensar neles como pequenos blocos de construção que quando juntos, formam algo grande. Todos os Nodes possuem essas caracteristicas:

- Nome
- Propriedades Editaveis
- Recebem callbacks para update a cada frame
- É possivel extender eles com novas funcionalidades e funções
- Da para adicionar um node como filho de outro node