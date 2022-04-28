# inverso-multiplicativo-modular
Grupo:
- Diego Enrique Zegarra Zenteno
- Rodrigo Del Piero Melendez Flores
- Leonardo Alonso Ramirez Quiroz

Primero insertamos el Algoritmo Extendido de Euclides que desarrollamos hace un tiempo, después crearemos la función inversa, en la que primero crearemos las variables "x" y "y" para el Algoritmo Extendido de Euclides; seguidamente, desarrollamos la función poniendo de parámetro los números que solicitamos en la función inversa (a y n), de ahí sacamos el mcd y como en la función los cambios que se hacen en x y y se guardan para después de la función pasamos a desarrollar el inverso, primero si el mcd es uno se desarrolla si no el inverso no existiria, despues comprobaremos si x está en el rango de Zn si este está en el rango (0 <= x <= n-1) significa que sí podremos continuar con la operación de x modulo n solo que a este le sumaremos una n y a ese modulo de n de nuevo para así poder cambiarle el simbolo cuando el resultado sea negativo, de ahí imprimimos el resultado y si x no estaba nos imprimira que no esta en el rango.

Ejemplo: 
 a=15
 n=8
 inverso=7
