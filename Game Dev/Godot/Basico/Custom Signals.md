#godot #godotEssentials 

Além dos [[Signal]]s já existentes, também é possivel criar nossos próprios com código:

```GDScript
signal atirou
signal municao_mudou(valor_antigo, valor_novo)

func atirar():
	# Instanciar bala
	atirou.emit()
	municao_mudou(2,1)
```

Signals definidos dessa maneira aparecem dentro dos Signals do node e podem ser utilizados por outros nodes.