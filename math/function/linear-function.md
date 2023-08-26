# 一次函数

* 了解直线斜率与截距的几何意义
* 根据直线与坐标轴的交点信息巧设截距式
* 掌握由定点信息求解析式（待定系数法）与由解析式求定点信息的做法
* 注意直线斜率不存在的情形

## 一次函数与直线

一次函数的图象是直线，其关系式 $$y=kx+b$$ 中的系数k对应于直线斜率，系数b对应于截距。因此 $$y=kx+b$$ 也叫做直线的斜截式方程。

<div data-full-width="false">

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Linear_Function_Graph.svg" alt="" width="375"><figcaption><p>一次函数的图像</p></figcaption></figure>

</div>

> 一次函数的图像都是直线吗？直线都能表示为一次函数吗？

除了斜截式以外，直线还可以有如下形式：

* 点斜式：![{\displaystyle y-y\_{1}=k(x-x\_{1})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2bcba6aa64529813434e624c6138910abcfd22ed)，其中k是斜率，且该直线过定点�(�1,�1)![{\displaystyle P(x\_{1},y\_{1})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/c40f1c73dac610d345c535db1cc111415a14d97c)
* 斜截式：y = kx + b，其中k是斜率，b是直线在y轴上的截距
* 两点式：![{\displaystyle {\frac {y-y\_{1\}}{x-x\_{1\}}}={\frac {y\_{1}-y\_{2\}}{x\_{1}-x\_{2\}}\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/426409df6f9e2f76156b3b9c4f77d9953ae2c853)，这样的直线过两定点![{\displaystyle P\_{1}(x\_{1},y\_{1}),P\_{2}(x\_{2},y\_{2})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/185e4c5d1453cecc25f1b6dd7a3ae9a35c75d0b8)
* 截距式：![{\displaystyle {\frac {x}{a\}}={\frac {y}{b\}}=1}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/0f73a301c50937a9d685e039a67cf74c14b17942)，这样的直线过定点![{\displaystyle A(a,0),B(0,b),a,b\neq 0}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/2d619cb5e1480be2d57ea8ab9b1adb94df66743b)
* 一般式：Ax + By + C = 0，A和B不可以同时为0。

其中的每一种形式都有其最适合使用的场合，我们为了方便称呼它们就根据列式的特点起了这些名字。在用待定系数法求解类型已知、包含未知参数的函数表达式时，应该根据涉及已知条件的多寡来设成形式最简洁的表达式。当直线斜率存在时，以上各种直线方程可相互转化。

## 一次函数的斜率

一次函数 $$f(x)=kx+b$$ 的斜率由 $$k$$ 给出，用于测量直线的倾斜程度。斜率就是直线与 $$x$$ 轴夹角的正切值。

通过2个点![{\displaystyle P\_{1}(x\_{1},y\_{1}),P\_{2}(x\_{2},y\_{2})}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/185e4c5d1453cecc25f1b6dd7a3ae9a35c75d0b8)的直线斜率公式：![{\displaystyle k={\frac {y\_{1}-y\_{2\}}{x\_{1}-x\_{2\}}\}}](https://wikimedia.org/api/rest\_v1/media/math/render/svg/6aa92d100f49bc8c3132df5a17544726197f657a)。

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Slope_picture.svg" alt=""><figcaption><p>斜率</p></figcaption></figure>

另一方面，斜率也表示一次函数 $$f(x)$$ 的**变化率**：每当输入x增加 $$\Delta x$$ 个单位时，输出就会改变$$k\Delta x$$ 个单位，也就是$$f(x+\Delta x)=f(x)+k\Delta x$$ 对于任意 $$\Delta x$$ 恒成立。如果斜率为正，那么函数![f(x)](https://wikimedia.org/api/rest\_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074)在增加，如果斜率为负，那么函数在减少。

对于非线性函数（如二次函数），函数在各处的变化率未必相同，但可以用函数在**该点处切线的斜率**来表示函数在该点的变化率（微积分中称为**导数**）。
