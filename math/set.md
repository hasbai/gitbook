# 集合

## 基本概念

把一些确定的对象看成一个整体就形成了一个集合（set），集合常用大写字母表示；集合里的各个对象叫做集合的元素，通常用小写字母表示。

#### 集合的性质

1. 确定性：每一个对象都能确定是不是某一集合的元素，没有确定性就不能成为集合，例如“个子高的同学”“很小的数”都不能构成集合。这个性质主要用于判断一个集合是否能形成集合。
2. 互异性：集合中任意两个元素都是不同的对象。如写成{1，1，2}，等同于{1，2}。互异性使集合中的元素是没有重复，两个相同的对象在同一个集合中时，只能算作这个集合的一个元素。
3. 无序性：{a,b,c}{c,b,a}是同一个集合。

#### 相互关系

元素与集合的关系：元素与集合的关系有“属于”（∈）和“不属于”（∉）两种。

集合与集合之间的关系：某些指定的对象集在一起就成为一个集合。

* 含有有限个元素叫有限集；
* 含有无限个元素叫无限集；
* 不含任何元素的集叫“空集”，记做“∅”，空集是任何集合的子集，空集是任何非空集的真子集；
* 任何集合是它本身的子集
* 子集，真子集都具有传递性。

#### 集合的表示

集合的表示方法集合常用大写拉丁字母来表示，如：A，B，C…集合中的元素则用小写的拉丁字母来表示，如：a,b,c…拉丁字母只是相当于集合的名字，没有任何实际的意义。将拉丁字母赋给集合的方法是用一个等式来表示的，例如：![{\displaystyle A=\\{\ldots \\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a37eef2eca8d1696683173545cadfbbaf5401e33)的形式。等号左边是大写的拉丁字母，右边花括号括起来的，括号内部是具有某种 共同性质的数学元素。有多种方法表示集合，其中常用的有列举法和描述法：

1. 列举法：常用于表示有限集合，把集合中的所有元素一一列举出来﹐写在大括号内﹐这种表示集合的方法叫做列举法。{1，2，3，……}
2. 描述法：常用于表示无限集合，把集合中元素的公共属性用文字﹐符号或式子等描述出来﹐写在大括号内﹐这种表示集合的方法叫做描述法。![{\displaystyle \\{x|P\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/52d87be8ed119fd645cbe93b0ad7feba16708087)为该集合的元素的一般形式，![{\displaystyle P}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/b4dc73bf40314945ff376bd363916a738548d40a)为这个集合的元素的共同属性。如：小于![\pi](https://wikimedia.org/api/rest\_v1/media/math/render/svg/9be4ba0bb8df3af72e90a0535fabcc17431e540a)的正实数组成的集合表示为：![{\displaystyle \\{x|0\<x<\pi \\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/fb68fcb440756c642256e2ef9434125477e31fc0)
3. 图式法：为了形象表示集合，我们常常画一条封闭的曲线（或者说圆圈），用它的内部表示一个集合。

#### 特殊集合的表示

1. 全体非负整数的集合通常简称非负整数集（或自然数集），记作![{\mathbb  {N\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/fdf9a96b565ea202d0f4322e9195613fb26a9bed)
2. 非负整数集内排除0的集，也称正整数集，记作![{\displaystyle \mathbb {N} \_{\mathbb {+} \}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/1093142a332231c2907230859a1a02efb63c0db1)或![{\displaystyle \mathbb {N} ^{\mathbb {\*} \}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/63b029f16efd9832dd98d2284645540292c4238b)
3. 全体整数的集合通常称作整数集，记作![{\displaystyle \mathbb {Z} }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/449494a083e0a1fda2b61c62b2f09b6bee4633dc)
4. 全体有理数的集合通常简称有理数集，记作![{\displaystyle \mathbb {Q} }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c5909f0b54e4718fa24d5fd34d54189d24a66e9a)，![{\displaystyle \mathbb {Q} =\\\{{\frac {p}{q\}}|p\in Z,q\in N,{\text{且 \}}\\,p,q\\,{\text{互 質 \}}\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/33b47d171f9dc57352eac3fc48d9b00a442085a1)
5. 全体实数的集合通常简称实数集，记作![{\mathbb  {R\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/786849c765da7a84dbc3cce43e96aad58a5868dc)
6. 复数集合记作![{\displaystyle \mathbb {C} }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f9add4085095b9b6d28d045fd9c92c2c09f549a7)

## 集合的运算

集合的三种运算法则

* 并集：以属于A或属于B的元素为元素的集合称为A与B的并（集），记作![{\displaystyle A\cup B}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/cdb575990bcfbcdf616aa6fd76e8b30bf7fd2169)（或![{\displaystyle B\cup A}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ff4c451478725278273ef879a5c0427f9662b21f)），读作“A并B”（或“B并A”），即![{\displaystyle A\cup B=\\{x|x\in A,{\text{或 \}}\\,x\in B\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ca4af7cb3d567cac405200ca8937e8efcc27a4c5)
* 交集：以属于A且属于B的元素为元素的集合称为A与B的交（集），记作![{\displaystyle A\cap B}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/bb27b38cf9eac6060e67b61f66cd9beec5067f81)（或![{\displaystyle B\cap A}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f064f17374503446af418299b2c9ebc5a7a10eaf)），读作“A交B”（或“B交A”），即![{\displaystyle A\cap B=\\{x|x\in A,{\text{且 \}}\\,x\in B\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/25574425454576fa7f935b8625616a71dfb85839)
* 补集：是从差集中引出的概念，指属于全集U不属于集合A的元素组成的集合称为集合A的补集，记作![{\displaystyle C\_{U}A}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/d4f52608980fcae7c2ed16dcdd2cdac1c65802da)，即![{\displaystyle C\_{U}A=\\{x|x\in U,{\text{且 \}}\\,x{\text{不 属 于 \}}\\,A\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/274a371283073db1ad7baf11e64f04527d7904fc)
* 在研究集合时，会遇到有关集合中的元素个数问题，我们把有限集合A的元素个数记为card(A)。例如![{\displaystyle A=\\{a,b,c\\\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/06b9d8908ec344da80af17b035774ba65e9cc818)，则 $$card(A)=3$$
  * card(A∪B)=card(A)+card(B)-card(A∩B)
  * card(A∪B∪C)=card(A)+card(B)+card(C)-card(A∩B)-card(B∩C)-card(C∩A)+card(A∩B∩C)
* 集合吸收律：![{\displaystyle A\cup (A\cap B)=A}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/f0dae78850c5e93789cea0dc6796f98e748ef69f) ; ![{\displaystyle A\cap (A\cup B)=A}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/da2cf46f728500a3dd203690e54bc0b021a32047)
* 集合求补律：![{\displaystyle A\cup C\_{U}A=U}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c3ef525543bd050e03ccec17fa206fcfb973969f) ; ![{\displaystyle A\cap C\_{U}A=\varnothing }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/ed1f4db71461060cc6842aa90bc9061e49c70d54)
* 设A为集合，把A的全部子集构成的集合叫做A的幂集
*   德摩根律 ![{\displaystyle A-(B\cup C)=(A-B)\cap (A-C)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c51c11a854b81fa8b6f0e5e4189c4608b717ae06)

    ![{\displaystyle A-(B\cap C)=(A-B)\cup (A-C)}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/0f3974d29b62e43272d36a4891f09af3945b7fc0)\
    ![{\displaystyle C\_{U}(B\cup C)=C\_{U}B\cap C\_{U}C}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/a14c887b3adc7724ac56abd86521623673a7a7a2)

    ![{\displaystyle C\_{U}(B\cap C)=C\_{U}B\cup C\_{U}C}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/7c965eb1b33a196358faaf448385a8ce877f420b)

    ![{\displaystyle \sim \varnothing =E\sim E=\varnothing }](https://wikimedia.org/api/rest\_v1/media/math/render/svg/dfbe51642b293e535286a256c9da637eb549c5b6)
