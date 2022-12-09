

Fields（域） are all about operations (like addition and multiplication)
Euclidean spaces are all about space
我们需要处理跟高纬度的空间，例如$R^k$ ，我们需要有一种方式来关联高纬度空间中的两个元素，度量空间就是在这个背景下引入的，度量空间中引入了点和距离函数的概念。

度量空间定义：
Defifinition 9.1. (Metric Space)
Property 1. (Distance) d(p, q) > 0 if p$\neq$q, while d(p, p) = 0.
Property 2. (Symmetry) d(p, q) = d(q, p).
Property 3. (Triangle Inequality) d(p, q) ≤ d(p,r) + d(r, q)
The elements of X are called points, and d is called the distance function or metric


有界集：
Defifinition 9.3. (Bounded Set) 有界集
$\exists$q $\in$ X , $\exists$ M $\in$ R such that $\forall$ p $\in$ E , d(p,q) $\leq$ M

邻域：
Defifinition 9.7. (Neighborhood) 
A neighborhood $N_r$(p) of radius r > 0 around a point p in a metric space X is the set
of all points in X whose distance from p is less than r
$N_r$(p)={q $\in$ X | d(p,q) < r}

极限点:
Defifinition 9.9. (Limit Point)
A point p is a limit point of a subset E of a metric space X if every neighborhood of p contains at least one point of E
$\forall$r>0, $N_r$(p)$\cap$E$\neq${p} and $\neq\varnothing$ 
定义 9.9 (极限点)
设 E 是度量空间 X 的一个子集．如果点 p 的每个邻域都包含 E 的至少一点(p本身除外)，那么 p就是 E 的极限点．

由定义可知，极限点 p ∈ E 的每一个邻域都至少包含 E 的另一个点．事实上，p 的每一个邻域都包含 E 中无穷多个点,因为p有无穷多个邻域．

Limit points : 极限点 **cluster points** : **聚点** **accumulation points** : **累积点**
non–limit point that is in E is called an isolated point (孤立点) of E

闭集:
Defifinition 9.13. (Closed Set)
A subset of a metric space is closed if it contains all of its limit points.

稠密集:
两种情况都成立：
1， A subset E of a metric space X is dense in X if every point of X is a point of E and a limit point of E
2，A subset E of a metric space X is dense in X if every point of X is a point of E or a limit point of E


内点:
Defifinition 9.19. (Interior Point) 
$\exists$r > 0 such that $N_r$ (p)  $\subset$ E

开集:
Defifinition 9.21. (Open Set) 
$\forall$ p $\in$ E, $\exists$r> 0 such that $N_r$(p) $\subset$ E

完备集：
Defifinition 9.24. (Perfect Set)
A subset of a metric space is perfect if it is closed and if all of its points are limit points.


