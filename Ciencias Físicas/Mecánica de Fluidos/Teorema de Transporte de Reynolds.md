
El Teorema de Transporte de Reynolds (TTR) es el [[Análisis Integral]] del balance o cambio temporal de una propiedad en un medio fluido:

$$
	\frac{d N}{d t} = \frac{\partial }{\partial t}\int_{V}^{} {\eta } \rho dV + \int_{\partial V}^{} {\eta } \rho \vec{v}\cdot d\vec{S}
$$
- $\eta,N$ : [[Propiedad Intensiva y Extensiva]] del fluido, respectivamente.
- $\rho$ : [[Densidad]] del fluido.
- $V$ : [[Volumen de Control]].
- $\partial V, S$ : [[Superficie de Control]].

### TTR de [[Masa]]

Sea $N=m$ , $\eta =1$ :

$$
	\frac{d m}{d t} = 0 = \frac{\partial }{\partial t}\int_{V}^{} { } \rho dV + \int_{\partial V}^{} { } \rho \vec{v}\cdot d\vec{S}
$$
- $m$ : [[Masa]] de fluido.

### TTR de [[Momentum]]

Sea $N=m\vec{v}$ , $\eta = \vec{v}$ :

$$
	\frac{d (m\vec{v})}{d t} = \vec{F}_m + \vec{F}_s = \frac{\partial }{\partial t}\int_{V}^{} {\vec{v} } \rho dV + \int_{\partial V}^{} {\vec{v}\cdot  } \rho \vec{v}\cdot d\vec{S}
$$
- $\vec{F}_m$ : Fuerzas másicas en el fluido.
- $\vec{F}_s$ : Fuerzas superficiales en el fluido.

### TTR de [[Momento Angular]]

Sea $N=\vec{r}\times m\vec{v}$ , $\eta = \vec{r}\times \vec{v}$ :

$$
	\frac{d (\vec{r}\times m\vec{v})}{d t} = \vec{T}_{eje} = \frac{\partial }{\partial t}\int_{V}^{} {(\vec{r}\times \vec{v}) } \rho dV + \int_{\partial V}^{} {(\vec{r}\times \vec{v})\cdot  } \rho \vec{v}\cdot d\vec{S}
$$
- $\vec{T}_{eje}$ : [[Torque]] en el eje.
- $\vec{r}$ : [[Palanca]].

### TTR de [[Energía]]

Sea $N=E$ , $\eta = e$ :

$$
	\frac{d E}{d t} = \dot{Q} + \dot{W} = \frac{\partial }{\partial t}\int_{V}^{} {e } \rho dV + \int_{\partial V}^{} {e  } \rho \vec{v}\cdot d\vec{S}
$$
- $E$ : [[Energía]] total del sistema.
- $\dot{Q}$ : [[Transferencia de Calor]] del sistema.
- $\dot{W}$ : [[Potencia Mecánica]] del sistema. 
- $e$ : [[Energía]] específica del sistema.
- $\vec{F}_m$ : Fuerzas másicas en el fluido.
- $\vec{F}_s$ : Fuerzas superficiales en el fluido.




