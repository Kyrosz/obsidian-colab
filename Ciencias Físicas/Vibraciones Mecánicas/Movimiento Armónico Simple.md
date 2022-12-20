
## Ec. de Movimiento

EDO de 2° grado:

$$
	\ddot{x} + \omega _n^2 x = 0
$$
- $\omega _n$ : [[Frecuencia Natural]].

### Sistema Masa - Resorte

Oscilación de una masa adherida al extremo de un resorte:

$$
	m \ddot{x} + kx = 0
$$
- $m$ : [[Masa]] adherida al resorte.
- $k$ : [[Coeficiente de Rigidez]] del resorte.

### Sistema Disco y Eje

Oscilación de un disco adherido al extremo de un eje:

$$
	J \ddot{\theta } + k \theta = 0
$$
- $J$ : [[Momento de Inercia]] del disco.

### [[Péndulo Simple]]

Oscilación de una masa adherida al extremo de una barra:

$$
	l\ddot{\theta } + g \theta = 0
$$
- $l$ : Largo del péndulo.
- $g$ : [[Gravedad]].

## Solución

Definiendo una fase:

$$
	x(t) = A \sin{(\omega_nt + \phi)}
$$

Aplicando **condiciones de borde**:

$$
	x(t) = \frac{\sqrt{\omega_n^2x_0^2+v_0^2}}{\omega_n} \sin{\left( \omega_n t + \tan^{-1}{\left( \frac{\omega_nx_0}{v_0} \right)} \right)}
$$

Donde las condiciones de borde son:

$$
	x_0 = x(0) = A \sin{\phi}
$$
$$
	v_0 = \dot{x}(0) = \omega_nA \cos{\phi}
$$

Donde la **amplitud** y la **fase** son, respectivamente:

$$
	A = \frac{\sqrt{\omega_n^2x_0^2+v_0^2}}{\omega_n} \quad\text{[m]}
$$
$$
	\phi = \tan^{-1}{\left( \frac{\omega_nx_0}{v_0} \right)} \quad\text{[rad]}
$$

**Forma simplificada** con condiciones de borde:

$$
	x(t)  = \frac{v_0}{\omega_n}\sin{(\omega_n t)} + x_0 \cos{(\omega_n t)}
$$

