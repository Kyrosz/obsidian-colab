
La **fuerza neta** aplicada sobre un [[Cuerpo Rígido]] es igual a su cambio temporal de [[Momentum]].

$$
	\vec{F} = \frac{d(m\vec{v})}{dt} = m \vec{a}
$$
- $\vec{F}$ : [[Fuerza]] neta aplicada sobre el cuerpo.
- $m$ : [[Masa]] del cuerpo.
- $\vec{v}$ : Velocidad del cuerpo.
- $\vec{a}$ : Aceleración del cuerpo.

En su **forma diferencial** para cualquier sistema mecánico:

$$
	\vec{F} = m \ddot{x}
$$
- $\ddot{x}$ : Aceleración del sistema.

También aplica para el **torque neto** aplicado sobre el cuerpo, el cual es igual al cambio de [[Momento Angular]], respecto al eje de rotación.

$$
	\vec{T} = \frac{d (\vec{r}\times m \vec{v})}{d t} = \vec{r} \times m \vec{a} = I \cdot \vec{\alpha }
$$
- $\vec{T}$ : [[Torque]] neto en el cuerpo.
- $\vec{r}$ : [[Palanca]] del torque neto.
- $I$ : [[Momento de Inercia]] del cuerpo.
- $\vec{\alpha }$ : Aceleración angular del cuerpo.

En su **forma diferencial** para cualquier sistema mecánico:

$$
	\vec{T} = I \ddot{\theta }
$$
- $\ddot{\theta }$ : Aceleración angular del sistema, en torno al eje de rotación.

## Método de las Fuerzas

La suma de las fuerzas en una dirección es igual al cambio temporal de momentum en esa dirección:

$$
	m \ddot{x} = \sum_{i}^{} {F_{x,i}}
$$
- $F_{x,i}$ : $i$-ésima fuerza actuando en la dirección $x$.

Para el caso de **rotaciones**:

$$
	J \ddot{\theta } = \sum_{i}^{} {M_{\theta ,i}}
$$
- $J$ : [[Momento de Inercia]] del sistema, en torno al eje de rotación.
- $M_{\theta ,i}$ : $i$-ésimo [[Torque]], par o momento de rotación, en torno al eje de rotación.
