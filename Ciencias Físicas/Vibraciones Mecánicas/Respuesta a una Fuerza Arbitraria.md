
A partir de la definición de [[Respuesta a un Impulso]], es posible definir un modelo a una respuesta para una fuerza arbitraria. Esto se logra separando la fuerza de excitación en un **conjunto de impulsos infinitesimales**, calculando la respuesta a cada impulso y sumándolas para conseguir la respuesta total.

La respuesta al [[Impulso]] en $t_i$ viene dada por:

$$
	\Delta x(t_i) = F(t_i) h(t-t_i) \Delta t
$$


La **respuesta total**, luego de $N$ intervalos, es:

$$
	x(t_N) = \sum_{i=1}^{N} {F(t_i)h(t-t_i) \Delta t}
$$

En el [[Límite]] cuando $\Delta t \to 0$ , es decir, $N \to \infty$ , la **respuesta total** es:

$$
	x(t) = \int_{0}^{t} {F(\tau ) h(t- \tau )} d\tau = \int_{0}^{t} {F(t - \tau ) h(\tau )} d\tau
$$

A esta [[Integral]] se le conoce como [[Integral de Convolución]].
