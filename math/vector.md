---
description: 向量是代数从低维走向高维的基石
---

# 向量

向量起源于物理学研究，后来在数学中也成为重要工具，广泛用于空间位置关系、高维数据与高维线性数量关系的表达。向量的用途广泛也体现在它同时沟通了代数、几何和三角函数，从向量及其运算会进一步衍生出矩阵、张量的概念，用于表达某些更高维的信息变化。向量的用途并不局限于物理学、工程力学和传统的数学，在统计决策和机器学习中，使用向量可以简化高维线性关系的表达，使其形式更紧凑；在计算机图形学中，使用向量也有助于简化有关运动和旋转的计算与表达。

## 基本概念

向量（vector）也译为矢量，是一种**既带有大小信息，又带有方向信息**的量。以前学过的不带有方向信息的可运算量则被叫做标度量（scalar）或标量、纯量。

向量的**几何意义是从起点到指定终点的有方向的连线段**。线段的方向就是向量的方向，方向用线段末端的箭头标出；线段的长度代表向量的大小（magnitude），也叫做向量的模（module）或长度（length）或规范数（norm）。可以在空间中任意平移的向量叫做自由向量（free vector），数学上考虑的向量都是这种自由向量。

* 零向量：长度为0的向量叫做零向量，记作 $$\vec 0$$。零向量的方向是任意的，可以说它是朝向所有的方向，零向量与任意向量平行。
* 单位向量：长度为1的向量叫做单位向量。
* 平行向量：方向相同或相反的成对或多个向量叫做平行向量，也叫共线向量（不等同于向量在同一条直线上）。
* 垂直向量：两个非零向量所在的直线彼此垂直，就称这两个向量彼此垂直，或者说是一对垂直向量。
* 相等向量：长度相等且方向也相同的向量叫做相等向量。向量之间的相等仍然用普通的等于号表示。
* 负向量：与向量 $$\vec a$$ 的长度相等、方向相反的向量叫做 $$\vec a$$ 的负向量，记作 $$-\vec a$$ 。$$\vec a - \vec b = \vec a + (-\vec b)$$

## 向量的加减法

向量的加法满足**平行四边形法则**（parallelogram law of addition vector addition）：从一个中心点发出的两个向量可以构成一个平行四边形，它们的合向量是起点为原点、以两个分向量为边所形成的平行四边形的那条对角线。

借助巧妙平移，还可知向量的加法满足**三角形法则**：平移两个向量，使它们一首一尾连接起来并从坐标系原点出发，则从原点直接连到终点的向量就为向量相加的结果。看起来得到的结果向量与参与相加的两个向量刚好构成一个三角形。

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Parallelogram_law.svg" alt=""><figcaption><p>平行四边形法则</p></figcaption></figure>

向量的加法满足：

* 交换律：![{\displaystyle {\vec {a\}}+{\vec {b\}}={\vec {b\}}+{\vec {a\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ec2b7482da2847013fa5de8900757c561b98c815)
* 结合律：![{\displaystyle ({\vec {a\}}+{\vec {b\}})+{\vec {c\}}={\vec {a\}}+({\vec {b\}}+{\vec {c\}})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/12ed900827a380a8ff59c669a64eec705577b54c)

由向量符号及其加法，可以将三角不等式表述为： $$| \overrightarrow {AC}| \le | \overrightarrow {AB}|+| \overrightarrow {BC}|$$ 或 $$|\vec a + \vec b| \le |\vec a| + |\vec b|$$&#x20;

### 例题

1. 化简下列各式：

* ![{\displaystyle {\vec {AB\}}+{\vec {CA\}}+{\vec {BC\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1d63b2f63900345172f1b30e3e28df9a8003bed8)
* ![{\displaystyle -{\vec {OE\}}+{\vec {OF\}}-{\vec {OD\}}-{\vec {DO\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/692425b46ebdcef5d41b825df9a9653566e1e0b8)
* ![{\displaystyle ({\vec {AB\}}+{\vec {MB\}})+{\vec {BO\}}+{\vec {OM\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a1004277d1d8b9c121b7ff9442ddf069cfb26240)
* ![{\displaystyle {\vec {OA\}}+{\vec {OC\}}+{\vec {BO\}}+{\vec {CO\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/09b8b32d948802e522d038ea8707b93a601fdcb3)
* ![{\displaystyle {\vec {AB\}}-{\vec {AC\}}+{\vec {BD\}}-{\vec {CD\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/09dfaccff190169a6af94106997438a0bd1d39a5)
* ![{\displaystyle {\vec {OA\}}-{\vec {OD\}}+{\vec {AD\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1404fb618d8763a336e04045640c9c54fc14afcf)
* ![{\displaystyle {\vec {AB\}}-{\vec {AD\}}-{\vec {DC\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d702017d684330f4b563ff1e6a3086235b4bd30e)
* ![{\displaystyle {\vec {NQ\}}+{\vec {QP\}}+{\vec {MN\}}-{\vec {MP\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/0d66cceb3bddc9573ff43509523168e3cdc4e638)

2. 若A、B、C、D是平面内任意四点，则下列各式中正确的有(    )。

A. ![{\displaystyle {\vec {AC\}}+{\vec {BD\}}={\vec {BC\}}+{\vec {AD\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/b843e2f2e7e2ead8fa672ae8a65ade72a48a3bdf)

B. ![{\displaystyle {\vec {AC\}}-{\vec {BD\}}={\vec {DC\}}+{\vec {AB\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2a7e08392bc725149e38db73380773491d8fb3ec)

C. ![{\displaystyle {\vec {AB\}}-{\vec {AC\}}-{\vec {DB\}}={\vec {DC\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/92f0609f30f6b1bd58c5cc34c6a98326022638e5)

D. ![{\displaystyle {\vec {AB\}}+{\vec {BC\}}-{\vec {AD\}}={\vec {DC\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/70572f247451e442bba21b7144e3a843ea46c258)

3. ![{\displaystyle a,b}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/181523deba732fda302fd176275a0739121d3bc8)为2个相互垂直的单位向量，![{\displaystyle {\vec {OP\}}={\vec {a\}},{\vec {OQ\}}={\vec {b\}},{\vec {OR\}}=r{\vec {a\}}+k{\vec {b\}},r\in \mathbb {R} ,k\in \mathbb {R} }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/59c8a6d3222e0814e0562a12f91867c8399ce2ef)，三角形PQR为等边三角形，则k和r的取值为(    )。

A.![{\displaystyle k=r={\frac {-1\pm {\sqrt {3\}}}{2\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/58d14ac41ab273f3231ccfa23efafa62bcec8dcf)\
B.![{\displaystyle k=r={\frac {1\pm {\sqrt {3\}}}{2\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d01a2eae5a7eb09d937ec7f712f2f72db817006f)\
C.![{\displaystyle k={\frac {-1\pm {\sqrt {3\}}}{2\}},r={\frac {1\pm {\sqrt {3\}}}{2\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/dd369c9f730b5ed320fecd9db4d024d2611174de)

D.![{\displaystyle k={\frac {1\pm {\sqrt {3\}}}{2\}},r={\frac {-1\pm {\sqrt {3\}}}{2\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3fa2ed0e2f9edfbdc5f4fa7501f138516280cfe9)

4. &#x20;设正六边形的6个顶点按逆时针顺序依次为ABCDEF，记![{\displaystyle {\vec {a\}}={\vec {AB\}},{\vec {b\}}={\vec {AF\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/6f3ff8727ef344a5c31a411444cefadd277b487a)，试用含![{\displaystyle {\vec {a\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/546e6615827e17295718741fd0b86f639a947f16)和![{\displaystyle {\vec {b\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3c9ef58be7103eb0b2bfcb460df23430f6a36216)的代数式分别表示出![{\displaystyle {\vec {AC\}},{\vec {AD\}},{\vec {AE\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d17d6cb9bcc663b4fe72bb68529cb309c5b47607)
5. 已知矩形ABCD的长为![{\displaystyle 2{\sqrt {3\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2cdf91246d2cd0e905a1aaf5b4b85cfc5a5879cd)，宽为2，记![{\displaystyle {\vec {a\}}={\vec {AB\}},{\vec {b\}}={\vec {BC\}},{\vec {c\}}={\vec {AC\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/9db9fc3888cb0a23f773cd0af0aea4a0047a8a55)，请画图表示出向量![{\displaystyle {\vec {a\}}+{\vec {b\}}+{\vec {c\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/5c4c103d57838d10bc076fea70061888c56cad61)并求出其模的大小
6. &#x20;已知平面上有不共线的4个点O、A、B、C。若![{\displaystyle {\vec {OA\}}-3{\vec {OB\}}+2{\vec {OC\}}={\vec {0\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/8bc5c802621b3c4305fa949779abb75ce5617b07)，求![{\displaystyle {\frac {|{\vec {AB\}}|}{|{\vec {BC\}}|\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/38971a453bcba2b0b90e7d6ed3c2dfff1f27e9a8)的值。
7. &#x20;利用向量方法求证：对角线相互平分的四边形是平行四边形。



