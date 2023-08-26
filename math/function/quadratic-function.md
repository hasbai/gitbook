# 二次函数

## 二次函数与二次方程

对二次方程配方、移项、开方后，可得求根公式： $$x=\dfrac {-b\pm {\sqrt {b^{2}-4ac}}}{2a}$$

在许多问题中，我们更关心的是方程实数解的数量，而不一定需要求出具体的解。设实数解的个数为m，为判断求根公式的所得结果在实数范围内是否有效，规定二次方程解的判别式（discriminant） $$\Delta$$ 为：

<figure><img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/8dac85a1c5e6f573eb9943cbc67a0cf7971f782c" alt=""><figcaption></figcaption></figure>

提示：这是因为当方程在实数范围内无解时，仍然可以出于某些特殊需要为其规定复数解等其它形式的解。

### 图像

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Polynomialdeg2.svg/1920px-Polynomialdeg2.svg.png" alt="" width="375"><figcaption><p>二次函数</p></figcaption></figure>

若从函数角度研究二次三项式，则由二次函数图象的直观规律和配方后的结果还可以知道下列关键信息：

* 二次项系数a决定开口，a > 0时开口朝上，a < 0时开口朝下， $$|a|$$ 越大开口越小。
* 二次函数的顶点坐标（最值）为  $${\displaystyle (-{\frac {b}{2a}},{\frac {4ac-b^{2}}{4a}})}$$&#x20;
* 二次函数的对称轴为  $$x=-\dfrac {b}{2a}$$&#x20;

函数图象与对应方程的关系：

* 函数图象与x轴有交点：方程有解；
* 函数图象与x轴有n个交点：方程有n个解；
* 函数图象与x轴没有交点：方程无解。

由此可知，判别式除了可以用于二次方程的解的计数，也可以用于二次图象与x轴交点的计数。

**注意：当二次项系数中含有参数的时候，需要讨论二次项系数是否为零。**

### 二次函数的形式

* 一般式：![{\displaystyle y=ax^{2}+bx+c\quad (a\neq 0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/df4872f003dac212a8b6df6b79806b9bc1fccb3c)，其中a、b、c为常数。
* 顶点式：![{\displaystyle y=a(x-h)^{2}+k\quad (a\neq 0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/9b84e13505bf0449d35be36d387022a0fcb09687)其中，a、h、k为常数。
* 交点式（两点式）：![{\displaystyle y=a(x-x\_{1})(x-x\_{2})\quad (a\neq 0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/66162fe04caaa57597527e25838328c3622db739)，其中a为常数，![{\displaystyle x\_{1},x\_{2\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/188263943645114e27e316cc1be787861e5b67be)分别为二次函数与x轴的2个交点的横坐标。

容易发现：

* 顶点式是对一般式配方后的结果。
* 顶点式容易看出对称轴和最值大小；如果已知对称轴和最值大小，则用顶点式表示二次函数是最快捷的。
* 交点式容易看出图象与x轴的2个交点；如果已知图象与x轴的2个交点，则用交点式表示二次函数是最快捷的。

## 韦达定理

韦达定理（Vieta's laws）也叫韦达公式（Vieta's formulas），它给出了二次方程中根与系数的关系：

![{\displaystyle {\begin{cases}x\_{1}+x\_{2}=-{\frac {b}{a\}}\\\x\_{1}x\_{2}={\frac {c}{a\}}\end{cases\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/cc900de8c8f4e1d3b1c5145fc26468a66d6e299e)

### 常见用法

结合平方转化技巧构造两根之和与两根之积的形式：

$${\displaystyle {\begin{array}{l}|x_{1}-x_{2}|={\sqrt {(x_{1}-x_{2})^{2}}}={\sqrt {x_{1}^{2}+x_{2}^{2}-2x_{1}x_{2}}}={\sqrt {x_{1}^{2}+2x_{1}x_{2}+x_{2}^{2}-4x_{1}x_{2}}}\\={\sqrt {(x_{1}+x_{2})^{2}-4x_{1}x_{2}}}\quad (={\sqrt {(-{\frac {b}{a}})^{2}+4\cdot {\frac {c}{a}}}}={\sqrt {{\frac {b^{2}}{a^{2}}}+{\frac {4c}{a}}}}={\frac {\sqrt {b^{2}+4ac}}{a}})\end{array}}}$$

结合通分、颠倒等分式变形技巧构造两根之和与两根之积的形式： $${\displaystyle {\frac {1}{x_{1}}}+{\frac {1}{x_{2}}}={\frac {x_{2}+x_{1}}{x_{1}x_{2}}}\quad (={\frac {-{\frac {b}{a}}}{\frac {c}{a}}}=-{\frac {b}{c}})}$$

已知两根之和与两根之积，可以采用这种思路求解 $${\displaystyle |x_{1}-x_{2}|,{\frac {1}{x_{1}}}+{\frac {1}{x_{2}}},{\frac {x_{1}}{x_{2}}}+{\frac {x_{2}}{x_{1}}},x_{1}^{2}+x_{2}^{2},{\frac {1}{x_{1}^{2}}}+{\frac {1}{x_{2}^{2}}},|{\frac {1}{x_{1}}}+{\frac {1}{x_{2}}}|}$$的值。

## 专题探讨

### 二次函数的局部单调性及含参问题

在涉及二次函数的考试题目中，比较麻烦的是包含未知参数并将变量的取值范围限定在指定区间内的问题，经常会涉及分类讨论或数形结合的方法。

1. 已知二次函数![{\displaystyle f(x)=x^{2}-2x-4}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/340bee3dd9924ad6773e4ee5f30b122bd464b4ed)在区间\[-2, a]上的最小值为-5，最大值为4，求实数a的取值范围。
2. 已知二次函数![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)满足![{\displaystyle f(0)=2,f(x)-f(x-1)=2x+1}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/774db60c1c432c2511a49e160dc6658cdca0bed2)，求![{\displaystyle f(x^{2}+1)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/4858c1ac81a947b6e6582d7d0d0cb9764ba6d6b6)的最小值
3. 已知函数![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)为二次函数，不等式![{\displaystyle f(x)<0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f04fbc4426566fb1c320c9418e982baf23f8f2e7)的解集是(0, 5)，且![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在区间\[-1, 4]上的最大值为12。\
   (1) 求![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的解析式。\
   (2) 设函数![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在\[t, t+1]上的最小值为![{\displaystyle g(t)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/b84f700860ee7af27797d11ddfad3d185eb7af0e)，求![{\displaystyle g(t)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/b84f700860ee7af27797d11ddfad3d185eb7af0e)的表达式
4. &#x20;已知关于x的方程![{\displaystyle (m+1)x^{2}+2(2m+1)x+1-3m=0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/4b1e80b5106bfccf58a4b1535b6da40bc5596748)的2个根为![{\displaystyle x\_{1\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a8788bf85d532fa88d1fb25eff6ae382a601c308)、![{\displaystyle x\_{2\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d7af1b928f06e4c7e3e8ebfd60704656719bd766)，若![{\displaystyle x\_{1}<1\<x\_{2}<3}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/03f34e8bc90e5888ae9bdf6efb95cb159ef20ded)，求实数m的取值范围。

### 恒成立与存在性问题

恒成立问题一般都可以转化为最值问题。尤其是考试最常考的包含一个变量x和一个参数a的等式或不等式的恒成立问题，都可以通过将变量和参数分离到等式或不等式两端的方法，转换为2个函数![g(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c6ca91363022bd5e4dcb17e5ef29f78b8ef00b59)和![{\displaystyle h(x)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/02c07825dae28705df03d15daeb8844d49c4dbd4)的最值比较问题。

存在性问题则一般需要利用函数的单调性，并通过数形结合的思想求解。通过保证单调性和检查区间端点的函数值，就可以确定存在性条件。

1. 若关于x的不等式![{\displaystyle |x-4|+|x+3|\<a}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/51ca50bf6d35ec3421cc7f06ec0b96f5b0a42a3f)有实数解，求实数a的取值范围。
2. 若![{\displaystyle \forall x\in (0,{\frac {1}{2\}}\]}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/b8474bc88d20f7da58f0bbf5d3c61d64de46b7ed)，都有不等式![{\displaystyle -x+a+1\geq 0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f06e8a54a3debcad4411879d84c4a1a88e8b77f0)成立，求a的最小值。
3. 已知函数![{\displaystyle f(x)=-x^{2}+4x+m}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/7e22fa20e6406a87f3165e3fad6b50b76d1df870)，若![{\displaystyle \exists x\in \[0,1\],f(x)=0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/68f499ff7b136427dfe1536515f008c9f1cf666a)，求m的取值范围。
4. 已知函数![{\displaystyle f(x)=ax^{2}-4ax+b\quad (a>0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/227e9841f0ad0901c842d6c2927e9e5f5f8cc298)在区间\[0, 1]上有最大值1和最小值-2。\
   (1) 求a和b的值。\
   (2) 若在区间\[-1, 1]上，不等式![{\displaystyle f(x)>-x+m}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/04c0198a287792b0f8e6a75c54f2e9c87ab33527)恒成立，求实数m的取值范围。
5. 已知函数![{\displaystyle f(x)={\frac {x-1}{x+2\}},\quad x\in \[3,5\]}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/5c7d79a18ac22082bb7493dc5068a0917872c97c)。\
   (1) 判断并证明![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的单调性。\
   (2) 若不等式![{\displaystyle f(x)>a}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/5d63fe74aab23968171f56416cb3a2c326c9329f)在\[3, 5]上恒成立，求实数a的取值范围。\
   (3) 若不等式![{\displaystyle f(x)>a}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/5d63fe74aab23968171f56416cb3a2c326c9329f)在\[3, 5]上有解，求实数a的取值范围。
6. 已知函数![{\displaystyle g(x)=ax^{2}-2ax+1+b\quad (a>0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/686c4c0fc0cff16d7b6730865a3aaff93de1c3eb)在区间\[2, 3]上有最小值1和最大值4。设![{\displaystyle f(x)={\frac {g(x)}{x\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1f7c74e62bbef53d491fe0f2c5381e502dd89ae5)。\
   (1) 求a和b的值。\
   (2) 若不等式![{\displaystyle f(x)-kx-4\leq 0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/62228271b54c5d7c6205cd339a33804748f3fab8)在![{\displaystyle x\in \[-1,0)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/9a26250ddcdc05f92a05972080d3729999731c7e)时恒成立，求实数k的取值范围。

### 函数性质的综合问题

1. 已知函数![{\displaystyle f({\sqrt {x\}}+2)=3x+{\frac {1}{x\}}+2}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/fc9fe3bdee66bbf6437118da9eb1639bcb1ba930)，函数![{\displaystyle g(x)=1-2x+{\sqrt {x+2\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/94a706e86aac58bad01e2d77c0177eb3d206fed6)。\
   (1) 求![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的解析式，并写出其定义域。\
   (2) 求![g(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c6ca91363022bd5e4dcb17e5ef29f78b8ef00b59)的值域。
2. &#x20;已知函数![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)对任意的实数a和b都有![{\displaystyle f(a+b)=f(a)+f(b)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/822600027fb446b01dd1902d7d3864d9f0f905ba)，且当![{\displaystyle x>0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/80d24be5f0eb4a9173da6038badc8659546021d0)时，有![{\displaystyle f(x)>0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/af29e26aaac6c969d32c8afac1f33ae703f442c7)。\
   (1) 求证：![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\mathbb  {R\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/786849c765da7a84dbc3cce43e96aad58a5868dc)上是增函数。\
   (2) 求证：![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\mathbb  {R\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/786849c765da7a84dbc3cce43e96aad58a5868dc)上是奇函数。\
   (3) 若![{\displaystyle f(1)=1}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c23ec03a1dad7631fc47878cb66b800a538dff1c)，解不等式![{\displaystyle f(x^{2})-f(x+2)>4}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a05b7f30425dc750f1bbb4005e4a5213c2866334)。

### 解高次整式不等式的穿根法

穿根法也叫做根轴法、数轴标根法、零点分段法、区间法、穿针引线法，是一种按根的位置将数轴分段，再通过数形结合思想分析求解上述整式不等式（即p(x) > 0）的方法

我们知道，由二次函数的两根式和图象特点，容易求解二次不等式。例如对于(x-1)(x-2) > 0，可以设y = (x-1)(x-2)，由开口向上且经过x = 1、x = 2的二次函数图象特征可知，满足y > 0的点的横坐标分布的区域就在x < 1或x > 2的范围内。

类似地，这种方法也可以推广到高次的整式不等式。具体地，我们考虑求解形如p(x) > 0的问题，其中p(x)是关于x的多项式，步骤为：

1. 对p(x)作因式分解。如果无法因式分解，则此法无法解决问题。
2. 利用因式分解的结果，得到p(x) = 0的全部根。
3. 将根从小到大排序，作为分界点将x轴分割为多段区域。
4. 用一条连续的函数曲线粗略地串起所有的根，并保证：
   1. 曲线严格穿过所有的根，且每个根只要穿过一次。
   2. 每多穿过一个根就改变一次曲线上y值的正负。
   3. 如果有重根，则不穿过。
   4. 曲线在某个区间上的取值正负决定曲线在该区间上是位于x轴上方，还是下方。
5. 结合图象走势和不等号朝向，得到答案

注意：使用穿根法解不等式时，需要注意最高次项系数的正负。最高次项系数的正负如果看错了，则答案会取为完全相反的区间。

相关例题1： 分别解下列不等式：

(1) (x-1)(x-2)(x-3) > 0；(2) ![{\displaystyle x^{3}\geq 5x}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ab2a497650ed077498a3c84edbfa164871bc108e)

相关例题2： 解不等式![{\displaystyle (4-x^{2})(x-2)^{2}>0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/04dc62915ac3e81da1ff5cd8752409854fabe62f)

