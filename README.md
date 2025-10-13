# quantum chemistry
some views of the procedure of studying

**比较函数的非定域算符和向量的非定域算符**\
**compare the functions' nonlocal operator with the vectors' nonlocal operator**  

for the function
$b(x)=Oa(x)=\int dx' O(x, x')a(x')$

for the vector
$b_i = \sum_j O_{ij} a_j$

这个里面的 $a(x')$ 是 $a(x) = \sum_{i} \psi_{i}(x) a_{i}$  
可以看作类似傅立叶级数组合 并定义 $\int_{x_1}^{x_2} dx \psi_{i}^{*}(x) \psi_{j}(x) = \delta_{ij}$  
现在引入无限完备基组 $\int dx |x\rangle \langle x| = 1$ 类似于之前的向量基组完备定义  
$\int dx \langle a|x \rangle \langle x|b \rangle = \langle a|b \rangle$  
$|b \rangle$ 可以看作是之前的向量空间中的一个基或一个向量， $\langle x|b \rangle$ 就视为在向量空间中的基或向量在函数基中的投影，投影的值就是在该x值时的值  
$\psi_i^*(x) = \langle i|x \rangle$ , $\psi_j(x) = \langle x|j \rangle$

**变分法**\
**the vatiation method**
