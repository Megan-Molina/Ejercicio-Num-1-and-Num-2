# Ejercicio-Num-1-and-Num-2
Ejercicio en clase
Ejercicio 1:
Dada la función f(x)=x3−6x2+11x−6:
a) Demuestra que tiene una raíz en el intervalo [1.5,2.5].
b) Aplica el método de bisección con 3 iteraciones.
c) Aplica el método de la regla falsa con 3 iteraciones.

Ejercicio 2:
Dada la función f(x)=x3−2x−5:
a) Aplica Newton-Raphson con x0=2 (3 iteraciones).
b) Usa el método de la secante con x0 = 1 y x1 = 2 (3 iteraciones).
Preguntas

1. Compara la velocidad de convergencia de los métodos.
   - Métodos lineales (Bisección, Falsa Posición, Punto Fijo) son lentos pero seguros.
   - Métodos superlineales (Secante, Muller) son más rápidos pero menos robustos.
   - Métodos cuadráticos (Newton-Raphson, Iteración Cuadrática) son rápidos pero pueden divergir si el punto inicial no es adecuado.
   
2. Explica cuándo usar métodos cerrados vs. abiertos.
   - Usa métodos cerrados cuando necesitas garantizar la convergencia. Estos métodos son ideales cuando conoces un intervalo en el que la función cambia de signo. Esto significa que si f(a)⋅f(b)<0, hay al menos una 
     raíz en el intervalo [𝑎,𝑏] [a,b].

   - Usa métodos abiertos cuando tienes una buena aproximación inicial de la raíz y necesitas rapidez. Estos métodos, como el de Newton-Raphson o la secante, convergen mucho más rápido que los métodos cerrados si 
     el punto inicial está lo suficientemente cerca de la raíz.
