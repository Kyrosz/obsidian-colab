
La derivada de una función por su definición de [[Límite]]:
$$ 
	\frac{d f(x)}{d x} = f'(x) = \lim_{h \to 0} {\frac{f(x+h) - f(x)}{h}} 
$$

## Propiedades

### Suma
La suma de derivadas de funciones es igual a la derivada de sumas de funciones:
$$
	(f_1 + f_2 + \cdots  + f_n)'(x) = f_1' + f_2' + \cdots + f_n'
$$
### Producto
La derivada del producto de dos funciones es igual al producto de la derivada de la primera con la segunda, sumada al producto de la primera con la derivada de la segunda.
$$
	\left( f \cdot g \right)'(x) = f'\cdot g + f \cdot g'
$$
### División
La derivada del cociente de dos funciones:
$$
	(f\div g)'(x) = \frac{f' \cdot g - f \cdot g'}{g^2}
$$

## Algunas Derivadas Importantes

### Función Constante
$$
	\frac{d }{d x} (\text{cte}) = 0
$$
**Demostración:**
Sea $f(x)=C$. Usando la definición del límite y considerando que $f(x+h)=C$:
$$
	 f'(x) = \lim_{h \to 0} {\frac{C-C}{h}} = 0 \qquad\blacksquare 
$$

### Función Lineal
$$ \frac{d }{d x} (x) = 1 $$
**Demostración:**
Sea $f(x)=x$. Usando la definición del límite:
$$ f'(x) = \lim_{h \to 0} {\frac{x+h-x}{h}} $$
$$ f'(x) = \lim_{h \to 0} {\left( \frac{h}{h} \right)} = 1 \qquad\blacksquare $$

### Monomio de Grado n
$$ \frac{d }{d x}(x^n) = nx^{n-1} $$
**Demostración:**
Sea $f(x) = x^n$. Usando la definición del límite:
$$ \begin{align}
 f'(x) &= \lim_{h \to 0} {\frac{(x+h)^n-x^n}{h}} \\
  \end{align} $$
Recordando la definición del [[Binomio de Newton]]:
$$ (x + h)^{n} = \sum_{k=0}^{n} {\begin{pmatrix}
    n \\
    k \\
    \end{pmatrix}x^{n-k}h^k} $$
Rearmando la ecuación del límite:
$$
	\begin{align}
 (x + h)^{n} - x^n &= \left( \sum_{k=0}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}h^k} \right) - x^n \\
  &= \sum_{k=1}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}h^k}
  \end{align}
$$
$$
	\begin{align}
 ((x + h)^{n} - x^n)/h &= \left( \sum_{k=1}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}h^k} \right) / h \\
 &= \sum_{k=1}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}h^{k-1}}
  \end{align}
$$
Luego:
$$
	\begin{align}
 f'(x) &= \lim_{h \to 0} {\left( \sum_{k=1}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}h^{k-1}} \right)} \\
  &= \sum_{k=1}^{n} {\begin{pmatrix} n \\ k \\ \end{pmatrix}x^{n-k}\cdot 0^{k-1}}
  \end{align}
$$
La sumatoria anterior es nula $\forall k \neq 1$:
$$
	\begin{align}
 f'(x) &= \begin{pmatrix} n \\ 1 \\ \end{pmatrix} x^{n-1} \cdot 0^0 \\
  f'(x) &= nx^{n-1} \qquad\blacksquare
  \end{align}
$$

### Seno
$$ \frac{d }{d x} \left( \sin{x} \right) = \cos{x} $$
**Demostración:**
Sea $f(x)=\sin{(x)}$. Usando la definición del límite:
$$ f'(x) = \lim_{h \to 0} {\frac{\sin{(x+h)} - \sin{(x)}}{h}} $$
Usando la propiedad del seno de la suma:
$$ \sin{(x+h)} = \sin{(x)}\cos{(h)} + \sin{(h)}\cos{(x)} $$
$$
	\begin{align}
 f'(x) &= \lim_{h \to 0} {\frac{\sin{(x)}\cos{(h)} + \sin{(h)}\cos{(x)} - \sin{(x)}}{h}} \\
  &= \lim_{h \to 0} {\frac{\sin{(x)}(\cos{(h)}-1) + \sin{(h)}\cos{(x)}}{h}} \\
  &= \sin{(x)}\lim_{h \to 0} {\left( \frac{\cos{(h)-1}}{h} \right)} + \cos{(x)}\lim_{h \to 0} {\left( \frac{\sin{(h)}}{h} \right)} \\
  f'(x) &= \cos{(x)} \qquad\blacksquare
  \end{align}
$$

### Coseno
$$ \frac{d }{d x} \left( \cos{x} \right) = -\sin{x} $$
**Demostración:**
Sea $f(x)=\cos{(x)}$. Usando la definición del límite:
$$ f'(x) = \lim_{h \to 0} {\frac{\cos{(x+h)} - \cos{(x)}}{h}} $$
Usando la propiedad del coseno de la suma:
$$ \cos{(x+h)} = \cos{(x)}\cos{(h)} - \sin{(x)}\cos{(h)} $$
$$ \begin{align}
  f'(x) &= \lim_{h \to 0} {\frac{\cos{(x)}\cos{(h)} - \sin{(x)}\sin{(h)} - \cos{(x)}}{h}} \\
  &= \lim_{h \to 0} {\frac{\cos{(x)}(\cos{(h)}-1) - \sin{(x)}\sin{(h)}}{h}} \\
  &= \cos{(x)}\lim_{h \to 0} {\left( \frac{\cos{(h)-1}}{h} \right)} - \sin{(x)}\lim_{h \to 0} {\left( \frac{\sin{(h)}}{h} \right)} \\
  f'(x) &= -\sin{(x)} \qquad\blacksquare
  
  \end{align}$$

### Logaritmo Natural
$$ \frac{d }{d x} \left( \ln{x} \right) = \frac{1}{x} $$
**Demostración 1:**
Sea $f(x) = \ln{(x)}$. Usando la definición del límite:
$$ \begin{align}
f'(x) &= \lim_{h \to 0} {\frac{\ln{(x+h)} - \ln{(x)}}{h}} \\
  &= \lim_{h \to 0} {\left( \frac{1}{h} \ln{\left( \frac{x+h}{x} \right)} \right)} \\
  &= \lim_{h \to 0} {\left( \ln{\left( 1+ \frac{h}{x} \right)^{1/h}} \right)} \\
 f'(x) &= \ln{\left( \lim_{h \to 0} { \left( 1 + \frac{h}{x} \right) ^{1/h} } \right)}
  \end{align} $$
Usando el cambio de variable $u = h/x$ para aplicar la definición de límite del [[Número e]]:
$$ \begin{align}
f'(x) &= \ln{\left( \lim_{u \to 0 } {\left( \left( 1 + u \right)^{1/ux} \right)} \right)} \\
 &= \ln{\left( \lim_{u \to 0} {\left( \left( 1+u \right) ^{1/u} \right) ^{1/x}} \right)} \\
 &= \ln{\left( e^{1/x} \right)} \\
 f'(x) &= \frac{1}{x} \qquad\blacksquare
  \end{align}  $$
**Demostración 2:**
Sea $y=\ln{x}$. Aplicando exponencial:
$$ \begin{align}
e^y &= e^{\ln{x}} \\
e^y &= x
  \end{align}$$
Aplicando diferenciación implícita:
$$ \begin{align}
 \frac{d }{d x} \left( e^y \right) &= \frac{d }{d x} (x) \\
 \frac{d y}{d x} e^y &= 1 \\
 \frac{d y}{d x} &= \frac{1}{e^y} \\
 \frac{d y}{d x} &= \frac{1}{x} \qquad\blacksquare
  \end{align} $$
