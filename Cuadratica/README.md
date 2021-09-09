# Cuadrática

Construye un programa para calcular los valores de la ecuación cuadrática `ax^2+bx+c` usando la fórmula cuadrática. (https://www.varsitytutors.com/hotmath/hotmath_help/spanish/topics/quadratic-formula)

El programa debe leer tres valores enteros a, b y c, y encontrar los valores de x, considerando las siguientes restricciones:
- Si a = 0 y b = 0 se debe desplegar el mensaje `"No tiene solucion”`.
- Si a = 0 y b != 0 se debe despejar el valor de x = –c/b y mostrar este valor.
- Si a != 0 y b != 0 se debe calcular el discriminante (b^2-4ac).
      * Si el valor del discriminante es negativo debe mostrar el mensaje `"Raices complejas"`.
      * Si el valor del discriminante es positivo debe calcular y mostrar los dos valores de x, una en cada renglón.
      * En caso de que el discriminante sea cero se debe mostrar sólo un valor de x = -b/(2a).

**Entradas**
- Los tres valores enteros a, b, c uno en cada renglón y en ese orden.

**Salidas**
- El valor de la o las raices (si es el caso) uno en cada renglón, o alguno de los mensajes `"No tiene solucion"` o `"Raices complejas"`.

Estos son algunos ejemplos de ejecución del programa. La salida del programa debe de ser exactamente de la siguiente forma:

```plaintext
Da el valor de a: 1
Da el valor de b: 2
Da el valor de c: 3
Raices complejas

Da el valor de a: 0
Da el valor de b: 1
Da el valor de c: 2
-2.0

Da el valor de a: 1
Da el valor de b: 5
Da el valor de c: 6
-2.0
-3.0

Da el valor de a: 0
Da el valor de b: 0
Da el valor de c: 2
No tiene solucion
```

**NOTA: Para mostrar la salida solamente imprime las variables en las que tienes el 
resultado de los cálculos.**
