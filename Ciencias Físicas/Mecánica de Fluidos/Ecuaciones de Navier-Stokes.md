
Estas ecuaciones representan la [[2° Ley de Newton]] de la conservación del momentum, aplicada a  
un elemento de volumen de [[Fluido Newtoniano]] viscoso generalizado.

Para un [[Fluido Incompresible]] y de [[Viscosidad]] uniforme, se tienen las siguientes relaciones:
$$
	dm \frac{D \vec{v}}{Dt} = d \vec{F}_m + d \vec{F}_s \quad \rightarrow \quad  \rho \frac{Du_i}{Dt} = \rho g_i + \sum_{j}^{} {\frac{\partial \tau _{ij}}{\partial x_j}}
$$
- $F_m$ : Fuerzas másicas en el fluido.
- $F_s$ : Fuerzas superficiales en el fluido.
- $\rho$ : [[Densidad]] del fluido.
- $g_i$ : [[Gravedad]] en la $i$-ésima dirección.
- $\tau _{ij}$ : [[Tensor de Esfuerzos Viscosos]] del fluido.

## Forma Diferencial

El lado izquierdo corresponde a la [[Derivada Material]]. 
$$
	\frac{D(\rho \vec{v})}{Dt} = \frac{\partial (\rho \vec{v})}{\partial t} + (\vec{v}\cdot\nabla)(\rho\vec{v}) = \rho\vec{g} - \rho\vec{a} - \nabla p + \mu\nabla^2\vec{v}
$$
- $\vec{a}$ : [[Campo de Aceleración]] en el fluido.
- $p$ : [[Campo de Presión]] en el fluido.
- $\mu$ : [[Viscosidad]] del fluido.

### [[Coordenadas Cartesianas]]

$$
	\rho \left( \frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} + v \frac{\partial u}{\partial y} + w \frac{\partial u}{\partial z} \right) = - \rho a_x - \frac{\partial p}{\partial x} + \mu \left( \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2} \right)
$$

$$
	\rho \left( \frac{\partial v}{\partial t} + u \frac{\partial v}{\partial x} + v \frac{\partial v}{\partial y} + w \frac{\partial v}{\partial z} \right) = - \rho a_y - \frac{\partial p}{\partial y} + \mu \left( \frac{\partial^2 v}{\partial x^2} + \frac{\partial^2 v}{\partial y^2} + \frac{\partial^2 v}{\partial z^2} \right)
$$

$$
	\rho \left( \frac{\partial w}{\partial t} + u \frac{\partial w}{\partial x} + v \frac{\partial w}{\partial y} + w \frac{\partial w}{\partial z} \right) = \rho g - \rho a_z - \frac{\partial p}{\partial z} + \mu \left( \frac{\partial^2 w}{\partial x^2} + \frac{\partial^2 w}{\partial y^2} + \frac{\partial^2 w}{\partial z^2} \right)
$$

### [[Coordenadas Cilíndricas]]

$$
	r
$$

$$
	\theta 
$$

$$
	z
$$

