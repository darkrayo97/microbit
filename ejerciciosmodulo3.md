## actividad 1
Para crea una variable y programar la placa Micro:bit para que, al presionar el
botón B, la variable aumente y, al presionar el botón A, la variable disminuya,
deberemos seguir los siguientes pasos:
A continuación, se detallan los pasos a seguir para resolver la actividad 1:
1. Para utilizar una variable, comenzamos por crearla haciendo clic en el botón
“Crear variable”.
2. Una vez creada, le asignamos un valor inicial en el interior del bloque “al
iniciar”, utilizando el bloque “establecer variable para”. Asignaremos un
valor inicial de, por ejemplo, 3.
3. A continuación, utilizaremos los bloques de entrada para programar el
cambio de la variable al presionar los botones A y B. Realizaremos estos
cambios utilizando los bloques “cambiar variable por”, sumando 1 al
presionar botón B, y sumando -1 al presionar el botón A.

![Captura](https://user-images.githubusercontent.com/114906901/208539060-a9b7b931-4e3a-4bfa-a62a-04384d8a1ede.PNG)


[archivo ampliado](https://github.com/darkrayo97/microbit/blob/27b7f9007492db7b448f412a5b81b3052f2326d4/microbit-modulo31.hex)

## actividad 2
Para crear una imagen grande y programar la placa para que inicialmente se
muestre la parte central de la imagen y, al presionar los botones A y B, la imagen
se deslice a la izquierda o a la derecha, respectivamente, deberás seguir los
siguientes pasos:
Para comenzar, descomponemos la actividad en retos sencillos. Existen muchas
posibilidades, una de ellas sería:
a) Crear la imagen y almacenarla en una variable.
b) Crear una variable con la que mover la imagen dándole valores
ascendientes o descendientes, en función de si se presionan los
botones.
c) Mostrar la imagen en la pantalla de la placa.
Continuamos con el reconocimiento de patrones:
Al comenzar el programa, debemos crear la imagen y dar el valor inicial a
una variable que indicará la posición de la imagen.
A la hora de pensar en la creación de esta variable la cual vamos a
incrementar o disminuir al presionar los botones observamos que
utilizaremos los mismos bloques que usamos en la actividad anterior, por
lo que ya tenemos en mente el algoritmo a usar:
● Creamos la imagen y la variable (en nuestro caso, la llamaremos offset)
● Si se presiona el botón A, mover la imagen a la izquierda (es decir,
modificar el valor de offset, disminuyéndolo para que la imagen se mueva
a la izquierda).
● Si se presiona el botón B, mover la imagen a la derecha (aumentando el
valor de offset).
● Por último, representar la imagen en la posición indicada por el offset.
En cuanto a la abstracción, analizando los demás retos podemos utilizar algunos
de los conocimientos adquiridos durante los módulos 1 y 2 del curso:
●Bloques de variable para calcular el movimiento de la imagen y para
almacenar la imagen grande.
●Bloques de imágenes para crear una imagen grande y para representarla,
controlando la posición (intervalo).
Con lo que debemos descartar el uso del resto de bloques aprendidos hasta
ahora, como los bloques de música o bucles.
Para terminar, codificamos, es decir, utilizamos los bloques para construir
nuestro programa. Replicaremos el programa de la actividad 1 para calcular la
variable “offset” (el intervalo). Además, crearemos una imagen grande, la
almacenaremos en una variable y la representaremos (de manera continua, en el
bloque “para siempre”) con el intervalo calculado.
El programa quedaría como se muestra a continuación
![Captura](https://user-images.githubusercontent.com/114906901/208539476-dfcd859b-eec5-480d-b271-14b09fe2b922.PNG)
