
El tensor de esfuerzos viscosos posee las siguientes relaciones con las [[Ecuaciones de Navier-Stokes]]:


En [[Coordenadas Cartesianas]]:

$$
	\begin{align}
	\sigma _x &= -p + 2 \mu \frac{\partial u}{\partial x} & \tau _{xy} &= \mu \left( \frac{\partial u}{\partial y} + \frac{\partial v}{\partial x} \right) \\
	\sigma _y &= -p + 2 \mu \frac{\partial v}{\partial y} & \tau _{xz} &= \mu \left( \frac{\partial u}{\partial z} + \frac{\partial w}{\partial x} \right) \\
	\sigma _z &= -p + 2 \mu \frac{\partial w}{\partial z} & \tau _{yz} &= \mu \left( \frac{\partial v}{\partial z} + \frac{\partial w}{\partial y} \right)
	  \end{align}
$$
- $\sigma_i$ : [[Esfuerzo Normal]] del fluido.
- $p$ : [[Presión]] del fluido.
- $\mu$ : [[Viscosidad]] del fluido.
- $\tau_{ij}$ : [[Esfuerzo de Corte]] del fluido.

En [[Coordenadas Cilíndricas]]:

$$
	\begin{align}
	\sigma_r &= - p + 2\mu\frac{\partial v_r}{\partial r} & \tau _{r \theta } &= \mu \left[ 
r \frac{\partial }{\partial r} \left( \frac{v_\theta }{r}  \right) + \frac{1}{r} \frac{\partial v_r}{\partial \theta} \right] \\
    \sigma_\theta &= - p + 2\mu \left( \frac{1}{r}\frac{\partial v_\theta }{\partial \theta} + \frac{v_r}{r} \right) & \tau _{\theta z} &= \mu \left( \frac{\partial v_\theta }{\partial z} + \frac{1}{r} \frac{\partial v_z}{\partial \theta} \right)  \\
    \sigma_z &= - p + 2\mu\frac{\partial v_z}{\partial z} & \tau_{rz} &= \mu \left( \frac{\partial v_r}{\partial z} + \frac{\partial v_z}{\partial r} \right)  
	  \end{align}
$$

