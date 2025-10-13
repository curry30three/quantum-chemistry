# quantum chemistry
some views of the procedure of studying

**比较函数的非定域算符和向量的非定域算符**\
**compare the functions' nonlocal operator with the vectors' nonlocal operator**  

for the function
$b(x)=Oa(x)=\int dx' O(x, x')a(x')$

for the vector
$b_i = \sum_j O_{ij} a_j$

这个里面的
$a(x')$
是
$a(x) = \sum_{i} \psi_{i}(x) a_{i}$
可以看作类似傅立叶级数组合并定义：
$$
\int_{x_1}^{x_2} dx \, \psi_{i}^{*}(x) \psi_{j}(x) = \delta_{ij}
$$
现在引入无限完备基组：
$$
\int dx \, |x\rangle \langle x| = 1
$$
这类似于之前的向量基组完备定义，可以推导出：
$$
\int dx \, \langle a|x \rangle \langle x|b \rangle = \langle a|b \rangle
$$
在这里，$|b \rangle$ 可以看作是向量空间中的一个向量，而 $\langle x|b \rangle$ 就视为该向量在位置基 $|x\rangle$ 上的投影，其结果就是波函数在该点的值。因此，我们有如下对应关系：
$\psi_i^*(x) = \langle i|x \rangle$ , $\psi_j(x) = \langle x|j \rangle$


**变分法**\
**the vatiation method**
