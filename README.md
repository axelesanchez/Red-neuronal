# Red-neuronal

Vamos a suponer que no se conoce la fórmula para pasar de grados Celsius a Fahrenheit. Entrenaremos entonces una red neuronal para que aprenda hacer dicha conversión. Para ello, voy a utilizar la librería Tensorflow.
Utilizaremos siete datos almacenados en la variable Celsius y siete en la variable Fahrenheit. Por lo tanto, queremos darle a la red neuronal estos ejemplos y que aprenda por si sola la relación. Es decir, que ajuste automáticamente los pesos y los sesgos para poder hacer predicción lo más acertadas posibles.
Para lograrlo, la red va a tomar todos esos datos de entrada que le dimos y por cada uno va a hacer una predicción. Recordemos que fue inicializado de manera aleatoria así que al principio le va a ir bastante mal. Luego ajustara los pesos y los sesgos y, si le fue muy mal se va a justar mucho, sino le fue tan mal ajustara poco.  

Observación:  la fórmula original de conversión es: Fahrenheit = Celsius * 1.8 + 32


Fuente: https://colab.research.google.com/drive/1ehETBOVtCqe7G6HOvm84hfXba8Gd9ILW?usp=sharing