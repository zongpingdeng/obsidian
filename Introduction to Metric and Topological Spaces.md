单变量微积分和实数   $\implies$ Metric Space  $\implies$   topological spaces


From the point of view of analysis, topology is the study of continuity, while from the point of view of geometry, it is the study of those properties of geometric objects which are preserved when the objects are stretched, compressed, bent, and otherwise mistreated--everything is legitimate except tearing apart and sticking together

The Cartesian product A $\times$  B of sets A, B is the set of all ordered pairs (a, b) where a $\in$  A, b $\in$ B

It is preferable to define a map as a pair of sets X, Y together with a certain type of subset of X x Y (intuitively the graph of f).Persisting with our way of thinking about f, we define the graph of f to be the subset $G_J$ = {(x, y) $\in$ X x Y : f(x) = y} of XxY.

Formally an infinite sequence of real numbers is a map  s : $\mathbb{N}$  $\to$  $\mathbb{R}$ 


Definition 5.1  A function $f : \mathbb{R}^n \to  \mathbb{R}$  is continuous at a point a $\in \mathbb{R}^n$ , say $a$ = ($a_1, a_2, ... , a_n$ ), if given $\epsilon$ > 0 there exists $\delta$  > 0  such that $\vert f(x)- f(a)\vert$< $\delta$  for every $x = (x_1, x_2, ... , x_n)$ satisfying

$\sqrt{\sum_{i=1}^n{(x_i - a_i)^2}} < \delta$     


(Ml) For all x, y $\in$ X, d(x, y) $\ge$ 0; and d(x, y) = 0 iff x = y.
(M2) For all x, y $\in$ X, d(y, x) = d(x, y).
(M3) For all x, y, z  $\in$ X, d(x, z) $\le$ d(x, y) + d(y, z).
Definition 5.2  A metric space consists of a non-empty set X together with a function 
d : X $\times$  X $\to \mathbb{R}$  such that (Ml), (M2), and (M3) above hold.


Definition 5.3 Suppose that ($X, d_x$) and ($Y, d_y$) are metric spaces and let $f : X \to Y$ be a map.
(a) We say $f$ is continuous at $x_0$ $\in  X$ if given $\epsilon$  > 0, there exists $\delta$  > 0 such that $d_y(f(x), f(x_0)) < \epsilon$  whenever $d_x(x, x_0) < \delta$ .
(b) We say $f$ is continuous if $f$ is continuous at every $x_0 \in  X$. When there are other metrics around we say '$f$ is $(d_x, d_y )$-continuous'.


定义1.6 对于有限集合A,称A的元素个数为集合的基数(cardinal)或阶(order),记为$\vert A \vert$ ,card(A)或者#A,约定$\vert \emptyset \vert$ = 0,对于无线集合A，形式地记$\vert A \vert = \infty$ 

Definition 7.1 A topological space T =($X, \mathcal{T}$) consists of a non-empty set $X$ together with a fixed family $\mathcal{T}$ of subsets of $X$ satisfying
(T1) $X$, $\emptyset$ $\in$  $\mathcal{T}$,
( T2) the intersection of any two sets in $\mathcal{T}$ is in $\mathcal{T}$,
( T3) the union of any collection of sets in $\mathcal{T}$ is in $\mathcal{T}$.

The family $\mathcal{T}$ is called a topology for X, and the members of $\mathcal{T}$ are called the open sets of $T$



Metric space 中 metric的类型， $d_0$ $d_1$ $d_2$ $d_\infty$ 

$d_0$ discrete metric

$d_0(x,y)$ = $\{\begin{array} = 1, x \ne y \\ 0, x = y \end{array}$  


Open Set 需要从拓扑空间中获取，拓扑空间中的开集是定义确定的，只要是处于拓扑空间中的集合，必然是开集。



