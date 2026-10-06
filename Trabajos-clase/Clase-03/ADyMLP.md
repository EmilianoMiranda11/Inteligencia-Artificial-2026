# Arboles de Decision y Redes Neuronales Multicapa 
Los arboles de decisión y las redes neuronales multicapa son algoritmos de aprendizaje supervisado que pueden utilizarse para problemas de clasificación y regresión, pero funcionan de manera diferente. Un árbol de decisión representa las decisiones mendiante una estructura de nodos y ramas, donde cada nodo realiza una condicion sobre una variable hasta que llega a una prediccion. En cambio, las redes neuronales multicapa esta formada como su nombre lo dice por varias capas de neuronas que estan conectadas entre si, que procesan las variables de entrada mediante lo que se llama funciones de activacion para obtener una salida.

### Ventajas de Arboles de Decisión
- Son bastante facil de interpretar y tambien de visualizar.
- Pueden trabajar con variables numericas y con categorias.
- Estos arboles requieren relativamente poco procesamiento.
- Al momento de entrenarlos suele ser rapido.
- Este te permite conocer que condiciones influyen en una decision.

### Desventajas de Arboles de Decisión
- Pueden sufrir un sobreajuste sobretodo si el arbol crece demasiado.
- Los pequeños cambios en los datos pueden generar o producir un arbol diferente.
- Un arbol individual puede tener menor capacidad para representar relaciones muy complejas.
- Para mejorar su rendimiento normalmente se utilizan metodos como el de Random Forest.

### Ventajas de la Red Neuronal Multicapa
- Pueden aprender relaciones complejas y no lineales.
- Estas son capaces de trabjar con una gran cantidad de variables.
- Pueden llegar a alcanzar un alto rendimiento cuando cuentan con suficientes datos y claro, una buena configuracion.
- Pueden llegar a utilizarse como una base para modelos mas avanzados de deep learning.

### Desventajs de la Red Neuronal Multicapa
- Son mucho mas dificiles de interpretar.
- Generalmente requieren mas datos para poder entrenarse correctamente.
- Pueden necesitar mayor capacidad.
- Tambien pueden sufrir un sobreajuste como los arboles de decision si el modelo es demasiado complejo.

En conclusion, los arboles de decisión son una buena opcion cuando se quiere buscar un modelo sencillo, rapido y facil de interpretar, mientras que por otro lado las redes neuronales multicapa son mas adecuadas cuando se necesita modelar relaciones complejas y se tienen los suficientes datos y recursos para entrenarlas correctamente.

# Plantamiento de DataSet

### Variables del DataSet
#### Pelota 1:
- **frame / tiempo:** Este es indentificador del instante de tiempo.
- **jugador_x, jugador_y:** Coordenadas del personaje.
- **pelota1_x, pelota1_y:** Posicion actual de la pelota en el plano 2D.
- **pelota1_vx, pelota1_vy:** Velocidad y direccion de movimiento de la pelota.
- **distancia_p1_jugador:** Distancia entre el jugador y la pelota.
- **colision:** Es una variable booleana que nos indica si la pelota toco al jugador.



