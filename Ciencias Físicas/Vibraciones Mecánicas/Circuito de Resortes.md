
Para cualquier configuración de resortes en serie o paralelo, es posible definir una fuerza total del circuito, igual al producto de su rigidez total y su deflexión total:

$$
	f = k \Delta \quad\text{[N]}
$$
- $f$ : [[Ley de Hooke (Elasticidad)|Fuerza Elástica]] del circuito. 
- $k$ : [[Coeficiente de Rigidez]] del circuito.
- $\Delta$ : Deflexión del circuito.

# Circuito en Serie

Para $N$ resortes en serie.

#### Fuerza Total

La fuerza ejercida en cada resorte es equivalente:

$$
	f = f_1 = f_2 = \cdots = f_N
$$
#### Rigidez Total

EL [[Coeficiente de Rigidez]] total es igual al inverso de la suma de los inversos de cada coeficiente.

$$
	k = \sum_{i}^{N} {\left( \frac{1}{k_i} \right)^{-1}}
$$
#### Deflexión Total

La deflexión total es la suma de las deflexiones de cada resorte:

$$
	\Delta = \sum_{i}^{N} {\Delta_i} = \sum_{i}^{N} {\frac{f_i}{k_i}} = f \sum_{i}^{N} {\frac{1}{k_i}}
$$

# Circuito en Paralelo

Para $N$ resortes en paralelo.

#### Fuerza Total

La fuerza total es la suma de la fuerza en cada resorte:

$$
	f = \sum_{i}^{N} {f_i}
$$
#### Rigidez Total

La rigidez total es la suma de la rigidez de cada resorte:

$$
	k = \sum_{i}^{N} {k_i}
$$
#### Deflexión Total

La deflexión de cada resorte es equivalente:

$$
	\Delta = \Delta_1 = \Delta_2 = \cdots = \Delta_N 
$$

