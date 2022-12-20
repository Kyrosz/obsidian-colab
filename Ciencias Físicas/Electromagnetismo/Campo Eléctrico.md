
$$ \vec{E}(\vec{r}) = \frac{q}{4 \pi\epsilon_0} \frac{\vec{r} - \vec{r}'}{\left|\left| \vec{r} - \vec{r}' \right|\right|^3} = \frac{\vec{F}_q}{q} $$
- $q$ : [[Carga Eléctrica]].
- $\varepsilon _0$ : Permitividad del vacío ([[Constantes Físicas]]).
- $\vec{F}_q$ : [[Ley de Coulomb|Fuerza de Repulsión Eléctrica]].

## Fuentes Compuestas

### Fuentes Discretas

La [[Carga Eléctrica]] se encuentra en un punto del espacio:
$$
	\vec{E}(\vec{r}) = \frac{1}{4 \pi\epsilon_0} \sum_{k=1}^{N} {q_k \frac{\vec{r} - \vec{r_k}'}{\left|\left| \vec{r} - \vec{r_k}' \right|\right|^3}}
$$
### Fuentes Continuas

La [[Carga Eléctrica]] se encuentra distribuida en el espacio:
$$
	\vec{E}(\vec{r}) = \frac{1}{4 \pi\epsilon_0} \int_{}^{} {\frac{\vec{r} - \vec{r}'}{\left|\left| \vec{r} - \vec{r}' \right|\right|^3}} dq(\vec{r}')
$$
#### Fuente Lineal o Filiforme

La [[Carga Eléctrica]] se distribuye a lo largo de una línea.
$$
	\vec{E}(\vec{r}) = \frac{1}{4 \pi\epsilon_0} \int_{}^{} {\frac{\vec{r} - \vec{r}'}{\left|\left| \vec{r} - \vec{r}' \right|\right|^3}} \lambda(\vec{r}')dr'
$$
- $\lambda(\vec{r}')$ : Densidad lineal o filiforme de carga.

#### Fuente Superficial

La [[Carga Eléctrica]] se distribuye en una [[Superficie]]:
$$
	\vec{E}(\vec{r}) = \frac{1}{4 \pi\epsilon_0} \int\int_{}^{} {\frac{\vec{r} - \vec{r}'}{\left|\left| \vec{r} - \vec{r}' \right|\right|^3}} \sigma(\vec{r}')dS'
$$
- $\sigma(\vec{r}')$ : Densidad superficial de carga.

#### Fuente Volumétrica

La [[Carga Eléctrica]] se distribuye en un [[Volumen]]:
$$   \vec{E}(\vec{r}) = \frac{1}{4 \pi\epsilon_0} \int\int\int_{}^{} {\frac{\vec{r} - \vec{r}'}{\left|\left| \vec{r} - \vec{r}' \right|\right|^3}} \rho(\vec{r}')dV'  $$
- $\rho(\vec{r}')$ : Densidad volumétrica de carga.