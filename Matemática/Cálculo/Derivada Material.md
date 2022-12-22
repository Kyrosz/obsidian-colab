
La derivada material es una definición utilizada para referirse al caso en que **la función derivada** (ya sea escalar o vectorial) **depende del espacio y del tiempo**. Para reconocerla, se escriben los diferenciales en mayúscula.

$$
	\frac{D(N)}{Dt} = \frac{d (N)}{d t} = \frac{\partial (N)}{\partial t} + \left( \vec{v} \cdot \nabla \right) \cdot (N)
$$
Donde $N = N(x_1,x_2,x_3,t)$ es una función continua y diferenciable en todo el espacio donde vive el medio.

**Desarrollo en [[Coordenadas Cartesianas]]:**
Aplicando derivación temporal a $N(x,y,z,t)$ y descomponiendo por [[Regla de la Cadena]]: 

$$ \frac{d N(x,y,z,t)}{d t} = \left( \frac{\partial N}{\partial x} \cdot \frac{d x}{d t} \right) + \left( \frac{\partial N}{\partial y} \cdot \frac{d y}{d t} \right) + \left( \frac{\partial N}{\partial z} \cdot \frac{d z}{d t} \right) + \frac{\partial N}{\partial t} $$
Notando que las derivadas de las coordenadas corresponden a las velocidades en dichas direcciones, es decir, $dx_i/dt = v_i$ :
$$  \frac{d N}{d t} = \frac{\partial N}{\partial x} \cdot u + \frac{\partial N}{\partial y} \cdot v + \frac{\partial N}{\partial z} \cdot w + \frac{\partial N}{\partial t}  $$
Se busca un operador que pueda evaluarse en la función $N$. Para ello se despeja $N$ del resto de operaciones. Cambiando el orden de los productos y despejando $N$:
$$  \frac{d N}{d t} = u \cdot \frac{\partial N}{\partial x} + v \cdot \frac{\partial N}{\partial y} + w \cdot \frac{\partial N}{\partial z} + \frac{\partial N}{\partial t}  $$
$$  \frac{d N}{d t} = \left( u \cdot \frac{\partial }{\partial x} \right) N + \left( v \cdot \frac{\partial }{\partial y} \right) N + \left( w \cdot \frac{\partial }{\partial z} \right) N + \frac{\partial N}{\partial t}  $$
Definiendo el vector velocidad:
$$ \left( u,v,w \right) = \vec{v} $$
Recordando la definición del [[Operador Nabla]] (vectorial):
$$ \nabla = \left( \frac{\partial }{\partial x},\frac{\partial }{\partial y},\frac{\partial }{\partial z} \right) $$
Notando que se tiene un producto punto entre la velocidad y el operador $\nabla$ se reescribe la fórmula de manera que se obtenga la definición de derivada material:
$$ \frac{d N}{d t} = \left( \vec{v}\cdot \nabla  \right)\cdot N + \frac{\partial N}{\partial t} \qquad\blacksquare $$

