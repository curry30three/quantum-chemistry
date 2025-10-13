# quantum chemistry
some views of the procedure of studying

**比较函数的非定域算符和向量的非定域算符**\
**compare the functions' nonlocal operator with the vectors' nonlocal operator**  

for the function
$b(x)=Oa(x)=\int dx' O(x, x')a(x')$

for the vector
$b_i = \sum_j O_{ij} a_j$

这个里面的 $a(x')$ 是 $a(x) = \sum_{i} \psi_{i}(x) a_{i}$
这是狄拉克符号 (Dirac Notation) 在量子力学中的应用，
它将函数空间与向量空间联系起来。\
```math
\int_{x_1}^{x_2} dx \, \psi_{i}^{*}(x) \psi_{j}(x) = \delta_{ij}
> 可以看作类似傅立叶级数的定义
现在引入无限完备基组：
\int dx \, |x\rangle \langle x| = \hat{1}
类似于之前的向量基组完备定义，可以得到：
\langle a|b \rangle = \int dx \, \langle a|x \rangle \langle x|b \rangle
在这里，$|b \rangle$ 可以看作是之前的向量空间中的一个基或一个向量，
而 $\langle x|b \rangle$ 就视为在向量空间中的基或向量在函数基中的投影，
投影的值就是在该 $x$ 值时的值。  
因此，我们有对应关系：
\psi_i^*(x) = \langle i|x \rangle, \quad \psi_j(x) = \langle x|j \rangle
**变分法**\
**the vatiation method**
