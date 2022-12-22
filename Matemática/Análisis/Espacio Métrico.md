
Un espacio métrico es un par ordenado $(E,d)$ donde $E$ es un conjunto no vació y $d$ es una [[Métrica (Distancia)]] sobre $E$ 

## Ejemplos 

$E:\mathbb{R}^{n}$, $d(x,y):=\sqrt{\sum_{j=1}^{n}\left | x_j-y_j \right |^{2}}$  con $x=(x_1,...,x_n)$ e $y=(y_1,...,y_n)$ 

Demostración:

(l) Si $x=y$, la igualdad $d(x,y)=0$ es directa. Por otro lado, si $d(x,y)=0$, $x=y$ se saca por contradicción.

Supongamos que $d(x,y)=0$ pero $x\neq y$ . Esto significa que existe algun subdindice $i \in \left \{ 1,...,n \right \}$ tq $x_i \neq y_i$. Entonces

$d(x,y)=0 \Rightarrow   \sqrt{\sum_{j=1}^{n}\left | x_j-y_j \right |^{2}}=0$    
$\Rightarrow \sum_{j=1}^{n}\left | x_j - y_j \right |^{2} =0$ 

terminar...
