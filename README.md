# Introducción
Bienvenid@ a mi wiki de la asignatura Sensores y Actuadores, aquí podrás encontrar en mayor detalle aspectos relacionados con la asignatura. ¡Espero que te guste! 

# Semana del 13 al 19 de Septiembre
Durante esta semana se produjo la presentación a la asignatura y la explicación del funcionamiento del sistema de entregas a través de git. También se nos presentó la práctica 0 (no entregable) para familiarizarnos con este sistema. 

# Semana del 20 al 26 de Septiembre
El miércoles 22 nos entregaron un kit muy completo para la realización de las prácticas y el jueves 23 nos explicaron cómo instalar Rasbian dentro de la Raspberry aunque muchos tuvimos problemas en esa sesión, por la tarde lo pude solucionar. Además, Julio nos indicó cómo realizar la práctica 1 que tendremos que entregar en 2 semanas: 
## Práctica 1
### 1. Implementación  y resultado de la práctica
Como indica el PDF, he reconstruido el esquema que se me proponía del LED en mi protoboard conectada a la Raspberry. Así me ha quedado:
![led encendido](https://github.com/jlopeza2020/wiki/blob/main/led_encendido.jpg "LED encendido")

# Semana del 27 de Septiembre al 3 de Octubre
Esta semana hemos empezado el tema de introducción  de teoría.

# Semana del 4 de Octubre al 10 de Octubre
El 6 de Octubre hemos acabado el tema de introducción y nos han pedido hacer la práctica 2:
## Practica 2:
### 1. Implementación de la práctica
En este caso he decidido elegir los pines 36, 38 y 40 a diferencia de los marcados por el profe y he usado 3 resistencias de 150 ohmios. A continuación, podrás ver cómo me ha quedado (El orden de los cables colocados es de RBG ya que los colores que da el LED están colocados así)
![led RBG montado](https://github.com/jlopeza2020/wiki/blob/main/p2_implementacion.jpg "LED RBG montado")
### 2. Ejemplo de la práctica
Como la realización de la misma es ir jugando con los distintos tipos de colores que se pueden formar y no se puede captar en una foto todos a la vez, he decidido mostrate el color Rojo:
![ejemplo con led Rojo](https://github.com/jlopeza2020/wiki/blob/main/p2_ledrojo.jpg "Ejemplo con el LED  rojo")

El 7 de Octubre hemos dado la primera parte del tema 2.
# Semana del 11 de Octubre al 17 de Octubre
El 13 de Octubre hemos acabado el tema 2 en el que hemos aprendido cómo funcionan los acondicionadores de señal y muchas propiedades y aplicaciones al respecto.
El 14 de Octubre se nos ha pedido realizar la práctica 3 que trata sobre las interrupciones:
## Práctica 3:
### 1. Implementación del ejercicio 1
Según aparece descrito en el enunciado de la práctica (**p3.pdf**), he utilizado la misma implementación que ha usado Julio.
![boton](https://github.com/jlopeza2020/wiki/blob/main/eje1_p3.jpg "Botón")                                                 
### 2. Implementación del ejercicio 2
En este ejercicio había que rediseñar el diseño del ejercicio 1 para poder hacer 2 pulsadores y que cada uno tenga un LED asignado y se puedan gestionar de manera independiente. Este es el resultado:
![ejercicio2](https://github.com/jlopeza2020/wiki/blob/main/eje2_p3.jpg "Ejercicio 2")

# Semana del 18 al 24 de Octubre
El miércoles 20 dimos la primera parte del tema 3: Sensores de velocidad, posición y aceleración. Vimos el potenciómetro, el tacogenerador y el LVDT.
EL jueves 21 acabamos ese tema y se nos ha introducido cómo hacer la práctica 4.

# Semana del 25 al 31 de Octubre 
El miércoles 27 hemos podido disponer de la clase para empezar la práctica 4 que trata de arreglar los errores producidos en la práctica 3.
El jueves 28 hemos introducido y tenido toda la clase para empezar con la práctica 5 que trata sobre conocer el funcionamiento de un sensor óptico para construir un encoder incremental.
## Práctica 5:
### 1.Implementación del divisor de tensiones
En el README de la práctica podrás haber leído que he usado las resistencias de 330 ohmios y de 470 ohmios y que a nivel de calcularlo con la calculadora he obtenido unos valores de 2,9 ohmios pero que usando el multímetro los valores son aproximadamente de 3.2 ohmios. A continuación, podrás ver unas imágenes de lo que acabo de describir:
![cálculo de Vout](https://github.com/jlopeza2020/wiki/blob/main/demostracion.jpg "Cálculo de Vout")

### 2.Implementación de la práctica completa 
A continuación podrás ver imágenes del circuito con encoder:
![implementación con encoder](https://github.com/jlopeza2020/wiki/blob/main/conEncoder.jpg "Implementación con Encoder")

# Semana del 1 al 7 de octubre 
EL miércoles 3 de noviembre dimos el tema 4 de teoría que trata de los sensores de Color, luz y visión  y el jueves 4 se nos ha introducido y dejado toda la clase para empezar la práctica 6 que trata sobre el sensor de ultrasonidos.
## Práctica 6:
### 1. Implementación de la práctica
En la imagen se puede ver el sensor de ultrasonidos y los tres Ledes que se pedían para la realización del ejercicio.
![implementación p6](https://github.com/jlopeza2020/wiki/blob/main/p6.jpg "implementación p6")

# Semana del 8 al 14 de noviembre
El miércoles 10 de noviembre hemos dado el tema 5 de teoría y el jueves 11 hemos tenido toda la clase para hacer la práctica 7 que trata del interruptor de lengüeta (o reed switch).
## Práctica 7:
### 1. Implementación de la práctica
En la imagen se puede ver un LED rojo, una resistencia de 220 ohmios, un interruptor de lengüeta y el imán usado para inducir sobre el interruptor. 
![implementación p7](https://github.com/jlopeza2020/wiki/blob/main/p7.jpg "implementación p7")

# Semana del 15 al 21 de noviembre
El miércoles 17 de noviembre se nos ha introducido el tema 6 y el jueves 18 de noviembre tuvimos toda la clase para poder empezar con la práctica 8 que trata de controlar el riego de una planta.
## Práctica 8:
### 1. Implementación de la práctica
En la imagen se puede ver el sensor de humedad conectado a una planta y los dos Ledes para facilitar al usuario el funcionamiento del sensor. Todo ello, junto a la caja que guarda a las plantas, conforma nuestro producto estrella: B-Water...plants.
![implementación p8](https://github.com/jlopeza2020/wiki/blob/main/humedadPlanta.jpg "implementación p8")

# Semana del 22 al 28 de noviembre
El miércoles 24 de noviembre hemos dado el tema 7 de teoría y el jueves 25 el tema 8 de teoría.

# Semana del 29 de noviembre al 5 de diciembre
Esta semana está dedicada para terminar las prácticas 5,6,7 y 8.

### Muy pronto llegarán nuevas noticias mías, ¡HASTA LA PRÓXIMA!
