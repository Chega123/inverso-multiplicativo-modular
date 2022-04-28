# inverso-multiplicativo-modular
Grupo:
- Diego Enrique Zegarra Zenteno
- Rodrigo Del Piero Melendez Flores
- Leonardo Alonso Ramirez Quiroz

primero insertamos el algoritmo extendido de euclides que desarrollamos hace un tiempo, despues crearemos la funcion inversa, en la que primero crearemos variable "x" y "y" para el algoritmo extendido de euclides, de ahi desarrollamos la funcion poniendo de parametro los numeros que solicitamos en la funcion inversa (a y n) de ahi sacamos el mcd y como en la funcion los cambios que se hacen en x y y se guardan para despues de la funcion pasamos a desarrollar el inverso, primero si el mcd es uno se desarrolla si no el inverso no existiria, despues comprobaremos si x esta en el rango de Zn si este esta en el rango (0<=x<=n-1) significa que si podremos continucar con la operacion de x modulo n solo q a este le sumaremos una n y a eso modulo de n de nuevo para asi poder cambiarle el simbolo cuando el resultado sea negativo, de ahi imprimimos el resultado y si x no estaba nos imprimira que no esta en el rango

Ejemplo 
a=15
n=8
inverso=7
