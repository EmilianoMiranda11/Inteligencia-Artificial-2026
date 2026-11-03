**EXAMEN TEÓRICO — PERCEPTRÓN, MLP Y CNN**

- Miranda Alejo Moises Emiliano
- Grupo B
- 03/Noviembre/2026

**Pregunta 1 - ¿Por que no basta una sola neurona?**

*1.- ¿Como funciona un perceptrón como regla de decision?*

Un perceptrón recibe los datos de entradad, les asigna pesos, calcula combinaciones de los valores que tienen y despues genera una salida que permite clasificarlos en una de las dos categorias.

*2.- ¿Que es una frontera lineal?*

Es una linea que divide los datos en dos regiones, permitiendo asi separar los elementos de una clase de los de otra. Esto en dimensiones mayores puede representar un plano o hiperplano.

*3.- Da un ejemplo donde es frontera no alcanza*

El problema XOR, ya que sus resultados no pueden separarse correctamente utilizando una sola linea recta.

**Pregunta 2 - CNN: de pixeles a mapas**

*1.- ¿Que problema de estructura espacial ignora un MLP si aplana la foto?*

Pierde la relacion espacial entre los pixeles, es decir, la informacion sobre que elementos estan cerca de otros y como estan organizados dentro de la imagen.

*2.- ¿Que significa que un mismo filtro se apliqeu en toda la imagen?*

Significa que el CNN suele utilizar los mismos pesos para poder buscar caracteristicas en diferentes regiones de la imagen, como los bordes, las texturas o las formas.

*3.- Menciona dos usos de las CNN ademas de clasificar objetos*

- El reconocimiento facial
- La deteccion de anomalias en imagenes medicas

**Pregunta 3 - Softmax, clases y decisiones**

*1.- Diferencia un problema binario de uno multiclase en terminos de salida de la red*

En un problema binario se busca distinguir entre dos categorias, mientras que en uno multiclase se necesita identificar entre tres o mas categorias. Entonces por eso la salida de red cambia segun la cantidad de clases que se ocupan predecir.

*2.- ¿Que lectura le das a las probablilidades que produce un softmax?*

Representan la confianza relativa del modelo en cada categoria asi que todas las probabilidades suman 1.

*3.- Si tienes tres carpetas de imagenes, ¿que arquitectura de salida usarias y por que?*

Utilizaria una capa de salida con tres neuronas y una funcion softmax ya que cada neurona representaria una categoria por asi decirlo y me permitiria obtener la probabilidad.

**Pregunta 4 - MLP: profundidad con sentido**

*1. ¿Qué ganas al apilar capas densas con activaciones no lineales?*

La capacidad de aprender relaciones más complejas entre los datos y construir patrones que no pueden representarse mediante una sola frontera lineal.

*2. ¿Qué riesgo aparece si la red es demasiado grande para tus datos?*

Puede producirse sobreajuste (overfitting), haciendo que el modelo memorice los datos de entrenamiento y tenga dificultades para generalizar con datos nuevos.

*3. Relaciona capa oculta con representaciones intermedias.*



**Pregunta 5 - Entrenamiento sin magia**

*1.- Explica que es una epoca*

Una epoca es una vuelta completa del conjunto de datos de entrenamiento a través de la red neuronal, durante la cual el modelo aprende y ajusta sus pesos.

*2.- ¿Hacia qué objetivo se mueven los pesos cuando hablamos de minimizar el error?*

Los pesos se ajustan buscando reducir la diferencia entre las predicciones del modelos y los resultados esperados.

*3.- ¿Que sucede si el learning rate es demasiado grande o demasiado pequeño?*

- Demasiado grande: los ajustes pueden ser excesivos, provocando que el modelo no consiga estabilizarse y minimizar el error.
- Demasiado pequeño: el aprendizaje será muy lento y necesitará muchas iteraciones para mejorar.

**Pregunta 6 - Bloques de una CNN**

*1.- Kernel/Filtro convolucional*

Es una pequeña matriz que recorre la imagen buscando caracteristicas especificas, como los bordes, texturas o patrones.

*2.- Función de activación después de conv*

Introduce no linealidad en la red, permitiendo aprender relaciones y características más complejas.

*3.- Max pooling*

Reduce las dimensiones de los mapas de características seleccionando los valores máximos de pequeñas regiones, conservando las características más importantes.

*4.- Capa densa + softmax al final de un clasificador*

**Pregunta 7 - XOR y la historia del aprendizaje**

*1.- ¿Por qué XOR se volvió un “contraejemplo” famoso?*

Porque demostró que un perceptrón simple no podía resolver todos los problemas de clasificación, ya que XOR no puede separarse mediante una frontera lineal.

*2.- ¿Qué elemento de un MLP permite patrones que no son una sola línea?*

Las capas ocultas combinadas con funciones de activación no lineales permiten construir fronteras de decisión más complejas.
