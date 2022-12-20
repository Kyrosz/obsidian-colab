
La ecuación de la presión hidrostática es la expresión de que los cambios en el [[Campo de Presión]] (es decir, su [[Gradiente]]) de un medio fluido son proporcionales al [[Campo de Aceleración]] del mismo, las cuales se deben a las fuerzas másicas actuando en él.

En [[Notación Vectorial]]:
$$
	\nabla p = \rho \vec{g} - \rho \vec{a}
$$
- $p$ : [[Campo de Presión]] del medio fluido.
- $\rho$ : [[Densidad]] del fluido.
- $\vec{g}$ : Campo de [[Gravedad]] en el fluido.
- $\vec{a}$ : [[Campo de Aceleración]] en un [[Sistema de Referencia No Inercial]].

**La componente de gravedad es positiva** ya que es directamente proporcional. En cambio, **la componente de aceleración es negativa** ya que genera una fuerza en sentido opuesto.

En [[Notación Indicial]]:
$$
	\frac{\partial p}{\partial x_i} = \rho g_i - \rho a_i
$$

En [[Coordenadas Cartesianas]], basta con reemplazar la componente $i$ en la notación indicial por las componentes $x$, $y$, $z$.

En [[Coordenadas Cilíndricas]]:



### Análisis

Para **deducir** estas ecuaciones, se utiliza el [[Análisis Diferencial]]. 

En **coordenadas cartesianas**:

Analizando un [[Cubo Diferencial]] en el caso de coordenadas cartesianas.

Primero se analiza la **función escalar de la presión**, $p=p(x,y,z)$, en cada cara del cubo:
![[fig-cubo-diferencial.png]] ![[fig-cubo-diferencial-presion.png]]
Se asume conocida la demostración de que **la presión hidrostática en un punto no depende de la dirección desde la cual se trace una superficie** ([[Sentido de Aplicación de la Presión]]).

Al tratarse de un espacio diferencial, el cambio de la presión respecto a cada dirección puede **aproximarse con una expansión en [[Serie de Taylor]] de primer orden**, ya que los términos de mayor orden son **despreciables**.

Los **cambios** ocurren tras un **desplazamiento** $dx_i/2$  desde el centro del cubo, a cada una de las caras. Por lo tanto, tenemos la siguiente aproximación:

