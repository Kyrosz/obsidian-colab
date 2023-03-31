**Ejercicio 1**
Para demostrar que si $(X,d)$ es un [[espacio métrico]] y el conjunto $X$ tiene al menos $n$ elementos, entonces

$d(x_1, x_n) ≤ d(x_1, x_2) + d(x_2, x_3) + . . . + d(x_{n−1}, x_{n}),$

se puede utilizar la desigualdad triangular de la métrica $d$ de la siguiente manera:

$d(x_1, x_n) = d(x_1, x_2) + d(x_2, x_n) ≤ d(x_1, x_2) + d(x_2, x_3) + d(x_3, x_n) ≤ ... ≤ d(x_1, x_2) + d(x_2, x_3) + ... + d(x_{n-1}, x_n)$ 
donde en cada paso utilizamos la desigualdad triangular y las definiciones de los puntos de la sucesión.

Por lo tanto, hemos demostrado que:

$d(x_1, x_n) ≤ d(x_1, x_2) + d(x_2, x_3) + ... + d(x_{n-1}, x_n)$ 

**Ejercicio 2**
Si (X, d) es un espacio métrico. Demuestre que $|d(x, y) − d(z, w)| ≤ d(x, z) + d(y, w)$ 

Podemos utilizar la desigualdad triangular en la metrica $d$ de la siguiente manera:
$$ 


