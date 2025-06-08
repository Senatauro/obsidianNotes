#godot #godotEssentials 

São chamadas de instancias objetos que são criados a partir de [[Scene]]s existentes. Ex: Se você tem uma Scene de uma bola e você usa essa Scene dentro de outra Scene, você está usando uma instancia da Scene da bola. A instancia da bola ainda vai estar ligada a sua Scene original, isso significa que se você mexer nas propriedades da bola dentro da Scene da bola, você muda todas as instancias dela que não tenham tido suas propriedades sobreescrevidas. 

Aparentemente só é possivel reescrever as propriedades do [[Node]] raiz, ficar atento a isso.