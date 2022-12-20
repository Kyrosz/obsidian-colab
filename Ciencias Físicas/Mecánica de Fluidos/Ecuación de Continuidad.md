
La ecuación de continuidad es la aplicación de la ley de [[Conservación de la Materia]] a un medio fluido. Establece que el **balance de materia** entre el **flujo que entra y sale** a través de la superficie cerrada de un [[Volumen de Control]] (llamada [[Superficie de Control]]), más los **cambios temporales dentro del volumen**, es nulo.

En su forma integral, equivalente al [[Teorema de Transporte de Reynolds]] aplicado a la propiedad de [[Masa]], es:
$$
	0 = \frac{\partial }{\partial t} \int_{V}^{} {\rho} dV + \int_{\partial{V}}^{} {\rho \vec{v}\cdot} d\vec{S}
$$
- $\rho$ : [[Densidad]] del fluido.
- $V$ : [[Volumen de Control]] (VC).
- $\partial V,S$ : [[Superficie de Control]] (SC).

En términos de [[Flujo Másico]] de entrada y de salida:
$$
	\sum_{in} \dot{m} = \sum_{out} \dot{m}
$$

## Forma Diferencial

Con un [[Análisis Diferencial]] y una expansión en [[Serie de Taylor]] de primer orden para un elemento de volumen, la ecuación de continuidad queda de la siguiente forma vectorial:
$$
	\nabla{(\rho \vec{v})} = 0
$$


### [[Coordenadas Cartesianas]]

Sea $\vec{v} = (u,v,w)$:
$$
	\frac{\partial (\rho u)}{\partial x} + \frac{\partial (\rho v)}{\partial y} + \frac{\partial (\rho w)}{\partial z} = 0
$$
Para un [[Fluido Incompresible]] ($\rho =\text{cte}$):
$$
	\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y} + \frac{\partial w}{\partial z} = 0
$$

### [[Coordenadas Cilíndricas]]

Sea $\vec{v} = (v_r,v_\theta,v_z)$:
$$
	\frac{\partial (\rho v_r)}{\partial r} + \frac{1}{r}\frac{\partial (\rho v_\theta)}{\partial \theta} + \frac{\partial (\rho v_z)}{\partial z} = 0
$$

Para un [[Fluido Incompresible]] ($\rho =\text{cte}$):
$$
	\frac{\partial v_r}{\partial r} + \frac{1}{r}\frac{\partial v_\theta }{\partial \theta} + \frac{\partial v_z}{\partial z} = 0
$$



