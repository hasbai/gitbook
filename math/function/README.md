---
description: 中学数学中，函数是将代数与几何联系起来的重要工具，函数的知识和思想贯了穿数学各个阶段、各个领域的学习
---

# 函数

函数和平面几何同样都是在初中考察较多的知识板块，但是平面几何知识在高中及后续课程中只需要作一般程度的了解（差不多会运用勾股定理、相似比解决简单直接的问题即可），重在从直观的图形性质探究中领悟其中的论证思想（反证、逆推、类比、借助辅助线，层层抽丝剥茧）；而函数的知识和思想都贯穿数学各个阶段、各个领域的学习，显然重要得多、具有深挖的价值。

函数相关章节的核心思想包括：

* 利用待定系数法或对比系数法确定含未知参数的函数。
* 理解各个关键参数对函数图象的影响，理解函数的图象变换。
* 理解函数解析式、函数图象、方程、不等式之间的相互联系。

## 函数的概念

### 函数的定义

定义：对于两个[集合](../set.md)X、Y，一个函数（function）就是使得对于每个![{\displaystyle x\in X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3e580967f68f36743e894aa7944f032dda6ea01d)，都能够对应某一个确定的![{\displaystyle y\in Y}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/cee1c0ec36a82f33f5e3d7434d5667881b4ec323)。

其中集合X叫做此函数的定义域（domain），Y叫做此函数的值域。对于每一个![{\displaystyle x\_{0}\in X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1b79e955b57dd7aada93b8afd459996ae941d480)，它在对应关系下的取值记作![{\displaystyle f(x\_{0})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/27cf1dbaefc6038a22779fb2943aff758a592a3a)，叫做该点的函数值。一个函数的所有可能取到的函数值所组成的集合叫做函数的值域（range）。

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Codomain2.SVG" alt=""><figcaption><p>函数与映射</p></figcaption></figure>

### 函数的特性

1. 函数的单调性：设![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)定义域为![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)，区间![{\displaystyle I\subseteq D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/9d609b0e7534f5d140ba0e5c32a05c3d647d22db),如果对于区间I上的任意两点![{\displaystyle x\_{1\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a8788bf85d532fa88d1fb25eff6ae382a601c308),![{\displaystyle x\_{2\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d7af1b928f06e4c7e3e8ebfd60704656719bd766)，当![{\displaystyle x\_{1}\<x\_{2\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ab5be810f318d1d4a506c86442106aab197a8d02)时，总有![{\displaystyle f(x\_{1})\<f(x\_{2})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2a4c41118c4f16101fb3939afd888dd388bc5ff0),我们就称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle I}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/535ea7fc4134a31cbe2251d9d3511374bc41be9f)上单调递增，若是![{\displaystyle f(x\_{1})>f(x\_{2})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/6311173f027de21fc04a7e26f3d5f8e82bd635a7)，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle I}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/535ea7fc4134a31cbe2251d9d3511374bc41be9f)上单调递减.
2. 函数的奇偶性：设![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的定义域![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)关于原点对称，如果对任一![{\displaystyle x\in D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/aaf3e2c3607ccf1c1d7ee6620b44ef9d9e2e1f6f)，有![{\displaystyle f(-x)=f(x)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/185fd2e78903788bc5756b067d0ac6aae1846724)恒成立,则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)上为偶函数，如果![{\displaystyle f(-x)=f(x)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/185fd2e78903788bc5756b067d0ac6aae1846724)恒成立，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在定义域![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)上为奇函数.
3. 函数的有界性：设![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的定义域为![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)，数集![{\displaystyle X\subseteq D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3a4e1f6c35d5ba93ce4785e85f56c06a2875fcf3)，若存在实数![{\displaystyle k}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c3c9a2c7b599b37105512c5d570edc034056dd40)，使![{\displaystyle f(x)\leqslant k}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1b7d084d0e866a47ad0dd7f7ad6348b424acdb72)对任意![{\displaystyle x\in X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3e580967f68f36743e894aa7944f032dda6ea01d)都成立，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab)上有上界，而![{\displaystyle k}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c3c9a2c7b599b37105512c5d570edc034056dd40)称为![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab)上的一个上界；如果存在正数![M](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f82cade9898ced02fdd08712e5f0c0151758a0dd)，使![{\displaystyle \left|f(x)\right|\leqslant M}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ed434b4fb4db2fafc4666faf886e46a4f5cc1336)对任意![{\displaystyle x\in X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/3e580967f68f36743e894aa7944f032dda6ea01d)都成立，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab)上有界，如果这样的![M](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f82cade9898ced02fdd08712e5f0c0151758a0dd)不能存在，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在![{\displaystyle X}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab)上无界.
4. 函数的周期性：设![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)的定义域为![{\displaystyle D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f34a0c600395e5d4345287e21fb26efd386990e6)，若存在一个正数![{\displaystyle T}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ec7200acd984a1d3a3d7dc455e262fbe54f7f6e0),使任意![{\displaystyle x\in D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/aaf3e2c3607ccf1c1d7ee6620b44ef9d9e2e1f6f)，有![{\displaystyle x+T\in D}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/7e8d0372beb43396469284db920ea40a1d7eddd8),且![{\displaystyle f(x+T)=f(x)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d267d80375326ebbc3c4efdc9d22a2feaa9bb325)恒成立，则称![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)为周期为![{\displaystyle T}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ec7200acd984a1d3a3d7dc455e262fbe54f7f6e0)的周期函数.

## 函数的图像

* 直角坐标系常识
* 直角坐标系中点到坐标轴的距离、点与点的距离
* 判断已知点关于原点或某条坐标轴的对称点的坐标
* 函数的概念、函数的图示法

平面上点![{\displaystyle P\_{1}(x\_{1},y\_{1}),P\_{2}(x\_{2},y\_{2})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/185e4c5d1453cecc25f1b6dd7a3ae9a35c75d0b8)间的距离为![{\displaystyle {\sqrt {(x\_{1}-x\_{2})^{2}+(y\_{1}-y\_{2})^{2\}}\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2b3e4697139b85446806c25733ffbedfc9adeff6)

### 函数图象与不等式

* 函数图象与不等式结合的问题
* 二次函数与二次不等式的关系

对于函数图象与不等式结合的问题，常常要从数形结合的思路入手

相关例题1： 已知当x > 1时，y = x+a的图象总在![{\displaystyle y={\frac {1}{x\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d0871f6114093b98d171970f2974952524b02d1b)的图象上方，求a的取值范围

相关例题2： 设曲线A的方程为y = - x + a，曲线B的方程为![{\displaystyle y={\frac {2}{x\}}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/dc1a40cf1a5102dbd24526dcfed741077ba45aff)。设A与B有2个不同的交点，求a的取值范围。

移项后整理后一侧为零，另一侧为二次三项式的不等式叫做二次不等式（quadratic inequality）。对于二次不等式，可以使用更直接的方法求解，即因式分解后判断各项因子的正负来决定答案的范围。

二次不等式的标准求解步骤：

1. 借助移项技巧，确保将不等式的一侧转变为零，另一侧变为二次三项式。
2. 尝试求解对应方程的根，并对二次三项式分解因式。
3. 当因式分解可行时，以根作为分界点，将整个实数轴划分为2个或3个区间。
4. 根据x在每个不同的区间上的取值情况，判断应该选择哪些区间作为问题答案

提示：\
(1)易知x在同一区间内变化时，对应二次三项式的取值正负始终相同，故只需要考虑不同区间之间的差异。(2)当对应的二次方程的确有根时，答案只可能是取中间或取两侧的区间。

通过简单的观察和尝试，我们可以总结出如下经验：

* 在划出的最左侧区间和最右侧区间上，二次三项式结算结果的符号始终与二次项系数的正负号相同。
* 不妨假设x很大（比方程最大的根还要大），此时只要看二次项系数是否大于0（也即是否符合不等号方向要求），即可确定是否能取左右两侧的区间。
* 当确保二次项系数大于0时，可以按照“大于取两边，小于取中间”的口诀快速确定答案范围

&#x20;相关例题3： 解不等式x(x-2) > 0
