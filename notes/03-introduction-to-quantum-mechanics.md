# 量子力学初步：从“电子绕核运动”到“电子态的概率分布”

第三章是整门原子物理中**理论观念变化最大、后续影响最深**的一章。

第一章研究“原子内部有什么”；第二章通过玻尔模型研究“电子可以处在哪些能量状态”；第三章则进一步追问：

> 电子到底以什么方式存在和运动？
> 为什么能量会量子化？
> 为什么电子没有确定的经典轨道？
> 原子的量子数究竟从哪里来？

课程复习提纲要求本章重点掌握：波粒二象性、不确定关系、波函数的统计解释、薛定谔方程、一维无限深势阱、力学量算符、角动量量子化和氢原子薛定谔方程。归一化的复杂计算、厄米算符和表象理论不是重点。

---

## 一、本章的整体逻辑

建议先记住下面这条主线：

```math
\boxed{
\text{玻尔模型的困难}
\rightarrow
\text{实物粒子波动性}
\rightarrow
\text{不确定关系}
\rightarrow
\text{波函数}
\rightarrow
\text{薛定谔方程}
\rightarrow
\text{能量本征值}
\rightarrow
\text{量子数和原子轨道}
}
```

其中每一步都在解决前一步留下的问题。

### 1. 玻尔模型解决了什么

玻尔模型成功解释了：

- 氢原子为什么有分立能级；
- 氢原子光谱为什么是线光谱；
- 能级为什么近似满足 $E_n\propto -1/n^2$ ；
- 玻尔半径和里德伯常数的数值。

### 2. 玻尔模型没有解决什么

玻尔模型的问题不是“计算不够精确”，而是其基本逻辑不统一。

玻尔同时使用了两套彼此矛盾的理论：

- 电子运动时使用经典力学；
- 电子辐射时又禁止使用经典电磁学；
- 角动量量子化 $L=n\hbar$ 是直接规定的；
- 电子跃迁也是直接规定的；
- 不能解释量子化为什么出现；
- 不能描述电子在原子中的真实空间分布；
- 对多电子原子、谱线强度、选择定则等问题无能为力。

所以玻尔模型属于“旧量子论”：

> 它把量子条件强行附加到经典轨道上，却没有真正建立微观世界的运动规律。

量子力学的任务，就是让玻尔理论中的量子化不再是人为规定，而成为方程求解的自然结果。

---

## 二、波粒二象性

---

### 1. 经典物理中的波与粒子

经典物理中，波和粒子是截然不同的。

#### 经典粒子

粒子的特点是：

- 有确定位置；
- 有确定动量；
- 有确定轨迹；
- 在空间中局域存在；
- 可以画出 $x(t)$ 。

例如子弹、行星、质点。

#### 经典波

波的特点是：

- 在空间中扩展；
- 可以发生干涉、衍射；
- 用振幅、频率、波长描述；
- 一般不具有确定轨迹。

例如水波、声波、电磁波。

经典物理认为：

```math
\text{一个对象要么是粒子，要么是波}
```

但微观实验告诉我们，这种二分法不成立。

---

### 2. 光的波粒二象性

光的波动性由下列现象证明：

- 干涉；
- 衍射；
- 偏振。

光的粒子性由下列现象证明：

- 黑体辐射；
- 光电效应；
- 康普顿效应；
- 单光子探测。

光子的能量和动量分别为

```math
E=h\nu=\hbar\omega
```

```math
p=\frac{h}{\lambda}=\hbar k
```

这里

```math
\omega=2\pi\nu,\qquad k=\frac{2\pi}{\lambda}
```

这两组关系非常重要：

```math
\boxed{E=\hbar\omega}
```

```math
\boxed{p=\hbar k}
```

它们把“粒子语言”中的 $E,p$ ，和“波语言”中的 $\omega,k$ 联系起来。

---

### 3. 德布罗意假设

1924年，德布罗意进行了一个大胆的类比：

> 既然原来被认为是波的光具有粒子性，那么原来被认为是粒子的电子，是否也具有波动性？

他提出：

```math
\boxed{\lambda=\frac{h}{p}}
```

对于非相对论粒子，

```math
p=mv
```

因此

```math
\boxed{\lambda=\frac{h}{mv}}
```

若已知粒子的非相对论动能

```math
E_k=\frac{p^2}{2m}
```

则

```math
p=\sqrt{2mE_k}
```

所以

```math
\boxed{\lambda=\frac{h}{\sqrt{2mE_k}}}
```

这就是考试中计算电子德布罗意波长最常用的公式。

---

### 4. 电子经过电压加速后的德布罗意波长

电子从静止经过电势差 $U$ 加速，获得动能

```math
E_k=eU
```

于是

```math
\lambda
=
\frac{h}{\sqrt{2m_e eU}}
```

代入常数，可得到一个非常实用的近似式：

```math
\boxed{
\lambda(\mathrm{Å})
\approx
\frac{12.27}{\sqrt{U(\mathrm V)}}
}
```

或

```math
\boxed{
\lambda(\mathrm{nm})
\approx
\frac{1.227}{\sqrt{U(\mathrm V)}}
}
```

这个公式适用于非相对论电子。若加速电压达到几十千伏以上，应考虑相对论修正。

---

### 5. 例题：54 eV电子的德布罗意波长

电子动能为

```math
E_k=54\ \mathrm{eV}
```

相当于电子经过 $54\ \mathrm V$ 电势差加速。

因此

```math
\lambda(\mathrm{Å})
=
\frac{12.27}{\sqrt{54}}
```

```math
\sqrt{54}\approx7.35
```

所以

```math
\lambda\approx1.67\ \mathrm{Å}
```

即

```math
\boxed{\lambda\approx0.167\ \mathrm{nm}}
```

这个尺度与晶格间距同数量级，因此电子可以被晶体衍射。

#### 做题启示

看见“电子动能为若干 eV”，通常立即想到：

```math
\lambda=\frac{h}{\sqrt{2m_eE_k}}
```

若动能数值正好以 eV 给出，也可以看成经过相同数值的电压加速。

---

### 6. 为什么宏观物体看不出波动性

设一粒灰尘质量

```math
m=1\ \mathrm{mg}=10^{-6}\ \mathrm{kg}
```

速度

```math
v=1\ \mathrm{mm/s}=10^{-3}\ \mathrm{m/s}
```

则

```math
\lambda=\frac{6.626\times10^{-34}}
{10^{-6}\times10^{-3}}
```

得到

```math
\lambda\approx6.6\times10^{-25}\ \mathrm m
```

如此短的波长根本无法通过普通实验观察。

所以不是宏观物体“没有”德布罗意波，而是：

```math
\boxed{\text{宏观物体的德布罗意波长小得无法显现}}
```

---

### 7. 波动性何时显现

衍射显著的基本条件是：

```math
\boxed{\lambda\sim d}
```

其中 $d$ 是障碍物、狭缝或晶格的特征尺度。

若

```math
\lambda\ll d
```

波动性通常不显著，经典粒子近似成立。

晶格常数约为

```math
d\sim10^{-10}\ \mathrm m
```

而几十电子伏电子的波长也是

```math
\lambda\sim10^{-10}\ \mathrm m
```

因此晶体是研究电子波动性的天然光栅。

---

### 8. 戴维孙—革末实验

戴维孙和革末让电子束轰击镍晶体，观察散射电子强度随角度的变化。

实验发现某些角度电子特别强，满足晶体衍射条件：

```math
\boxed{2d\sin\theta=n\lambda}
```

同时，由德布罗意公式计算出的电子波长与衍射测得的波长一致。

因此这个实验说明：

```math
\boxed{\text{电子确实具有波动性}}
```

注意：

> 实验并不是说明电子变成了一团经典水波，而是说明电子的运动状态具有相干叠加和衍射规律。

课件特别强调，晶体衍射是实物粒子波动性的实验检验，而戴维孙—革末实验和G.P.汤姆孙实验分别以反射和透射方式观察到了电子衍射。

---

## 三、波粒二象性的真正含义

这是本章最容易理解错的地方。

### 1. 错误理解一：电子是一颗小球，同时拖着一列波

这不准确。

如果把电子理解为小球，再给它附加一列经典波，就仍然没有摆脱经典概念。

### 2. 错误理解二：电子是一团连续分布的物质波

也不准确。

电子被探测时，总是以完整的电子出现：

- 电荷总是 $-e$ ；
- 质量总是 $m_e$ ；
- 探测器上出现一个局域的点。

电子不是被分成半个、四分之一电子落在不同地方。

### 3. 错误理解三：干涉是许多电子相互作用造成的

单电子双缝实验否定了这种说法。

即使每次只有一个电子通过双缝：

- 每个电子最终只在屏上留下一个点；
- 许多电子逐渐积累后，仍形成干涉条纹。

因此干涉不是电子之间相互作用造成的，而是：

```math
\boxed{\text{单个电子量子态的不同概率幅发生叠加}}
```

### 4. 正确理解

微观粒子既不是经典粒子，也不是经典波。

更准确地说：

- 探测结果体现粒子的原子性、不可分割性；
- 传播和演化体现概率幅的相干叠加性。

也就是：

```math
\boxed{
\text{量子对象}
=
\text{粒子式探测}
+
\text{波式概率幅传播}
}
```

课件将这种统一概括为：把微观粒子的“原子性”和波的“相干叠加性”统一起来。

---

## 四、不确定关系

---

### 1. 基本公式

位置和动量的不确定关系为

```math
\boxed{
\Delta x\,\Delta p_x\geq\frac{\hbar}{2}
}
```

类似地，

```math
\Delta y\,\Delta p_y\geq\frac{\hbar}{2}
```

```math
\Delta z\,\Delta p_z\geq\frac{\hbar}{2}
```

常见的数量级估算也写成

```math
\Delta x\,\Delta p_x\sim\hbar
```

但规范计算应优先使用

```math
\Delta x\,\Delta p_x\geq\frac{\hbar}{2}
```

---

### 2. “不确定”是什么意思

$\Delta x$ 不是仪器刻度，也不是简单的测量误差，而是位置分布的标准差：

```math
\Delta x
=
\sqrt{
\langle x^2\rangle-\langle x\rangle^2
}
```

同样，

```math
\Delta p_x
=
\sqrt{
\langle p_x^2\rangle-\langle p_x\rangle^2
}
```

因此，不确定关系表达的是：

> 一个量子态本身不可能同时具有任意精确的位置和动量分布。

它不是说“粒子有精确位置和动量，只是我们测不准”。

更准确地说：

```math
\boxed{
\text{在给定量子态中，位置和动量不能同时都是确定值}
}
```

---

### 3. 为什么会出现不确定关系

从波的角度理解最自然。

#### 单色平面波

如果一个粒子的动量完全确定：

```math
p=\hbar k
```

那么对应的是单一波数 $k$ 的无限平面波：

```math
\psi(x)=Ae^{ikx}
```

它在整个空间都有相同概率密度，因此位置完全不确定：

```math
\Delta p=0
\quad\Longrightarrow\quad
\Delta x\to\infty
```

#### 局域波包

若想把粒子限制在一个很小区域内，就必须把许多不同波数的平面波叠加起来。

波数范围越大：

```math
\Delta k\text{越大}
```

动量范围也越大：

```math
\Delta p=\hbar\Delta k
```

因此位置越精确，动量越不确定。

这本质上来自傅里叶分析：

```math
\Delta x\,\Delta k\gtrsim\frac12
```

再利用

```math
p=\hbar k
```

得到

```math
\Delta x\,\Delta p\geq\frac{\hbar}{2}
```

---

### 4. 单缝衍射与不确定关系

设粒子沿 $x$ 方向运动，通过宽度为 $a$ 的狭缝。

通过狭缝后，粒子在横向 $y$ 的位置约被限制为：

```math
\Delta y\sim a
```

单缝衍射第一极小满足：

```math
\sin\theta\sim\frac{\lambda}{a}
```

横向动量约为

```math
\Delta p_y\sim p\sin\theta
```

代入

```math
p=\frac{h}{\lambda}
```

得到

```math
\Delta p_y
\sim
\frac{h}{\lambda}\frac{\lambda}{a}
=
\frac{h}{a}
```

于是

```math
\Delta y\,\Delta p_y
\sim
a\frac{h}{a}
=
h
```

与不确定关系的数量级一致。

#### 物理意义

狭缝越窄：

```math
\Delta y\downarrow
```

但衍射越强：

```math
\Delta p_y\uparrow
```

因此不能靠无限缩小狭缝，同时精确测量位置和动量。

---

### 5. 例题：限制在原子核内的电子至少具有多大能量

假设把电子限制在

```math
\Delta x\sim10^{-15}\ \mathrm m
```

范围内。

根据不确定关系，

```math
\Delta p
\gtrsim
\frac{\hbar}{2\Delta x}
```

代入：

```math
\Delta p
\gtrsim
\frac{1.055\times10^{-34}}
{2\times10^{-15}}
\approx5.3\times10^{-20}\ \mathrm{kg\,m/s}
```

这个动量已经远大于 $m_ec$ 的普通非相对论尺度，因此不能简单使用

```math
E_k=\frac{p^2}{2m}
```

应使用相对论关系：

```math
E^2=p^2c^2+m_e^2c^4
```

数量级上，若 $pc\gg m_ec^2$ ，则

```math
E\sim pc
```

所以

```math
E\sim
5.3\times10^{-20}\times3.0\times10^8
```

```math
E\sim1.6\times10^{-11}\ \mathrm J
```

转化为电子伏特：

```math
E\sim10^8\ \mathrm{eV}
```

即约百 MeV 数量级。

这说明：

> 若电子被限制在原子核范围内，它必须具有极大的动能，因此普通原子核内不可能预先存在一个低能电子。

这是用不确定关系做数量级判断的典型题。

---

### 6. 能量—时间不确定关系

常见形式为

```math
\boxed{
\Delta E\,\Delta t\gtrsim\frac{\hbar}{2}
}
```

它和位置—动量不确定关系的含义不完全相同，因为时间在普通量子力学中不是与位置同类的算符。

在原子物理中常用于：

- 激发态寿命；
- 能级宽度；
- 谱线自然宽度。

若一个激发态寿命为 $\tau$ ，其能级宽度数量级为

```math
\boxed{
\Delta E\sim\frac{\hbar}{\tau}
}
```

寿命越短，能级越宽；寿命越长，能级越锐利。

---

## 五、波函数及其统计解释

---

### 1. 为什么需要波函数

经典力学中，一个粒子的状态由位置和动量给出：

```math
\boldsymbol r(t),\qquad \boldsymbol p(t)
```

但在量子力学中，由于不确定关系，不能再用一条确定轨迹描述电子。

因此量子力学用波函数

```math
\boxed{\Psi(\boldsymbol r,t)}
```

来描述粒子的量子态。

课件将“微观粒子的运动状态由波函数描述，描写粒子的波是概率波”列为量子力学的基本假设。

---

### 2. 自由粒子的平面波

具有确定动量 $\boldsymbol p$ 和确定能量 $E$ 的自由粒子，可以写成

```math
\Psi(\boldsymbol r,t)
=
A\exp\left[
\frac{i}{\hbar}
(\boldsymbol p\cdot\boldsymbol r-Et)
\right]
```

一维情况下：

```math
\Psi(x,t)
=
Ae^{i(px-Et)/\hbar}
```

这与经典波

```math
Ae^{i(kx-\omega t)}
```

形式相同，因为

```math
p=\hbar k,\qquad E=\hbar\omega
```

---

### 3. 波函数不是直接可观测量

波函数通常是复数：

```math
\Psi=\Psi_{\mathrm R}+i\Psi_{\mathrm I}
```

实验不能直接测量 $\Psi$ 。

真正具有概率意义的是

```math
\boxed{
|\Psi|^2=\Psi^*\Psi
}
```

---

### 4. 玻恩统计解释

玻恩提出：

```math
\boxed{
|\Psi(\boldsymbol r,t)|^2
}
```

表示粒子在时刻 $t$ 、位置 $\boldsymbol r$ 附近的概率密度。

在体积元 $d\tau$ 中找到粒子的概率为

```math
\boxed{
dP
=
|\Psi(\boldsymbol r,t)|^2d\tau
}
```

一维情况下，在区间 $[x,x+dx]$ 内找到粒子的概率：

```math
dP=|\Psi(x,t)|^2dx
```

在区间 $[a,b]$ 内找到粒子的概率：

```math
\boxed{
P(a\lt x\lt b)
=
\int_a^b|\Psi(x,t)|^2dx
}
```

课件明确给出：波函数模平方是概率密度，波函数也称为概率幅。

---

### 5. 归一化

粒子一定存在于整个空间某处，因此全空间概率应为1：

```math
\boxed{
\int_{\text{全空间}}|\Psi|^2d\tau=1
}
```

一维情况下：

```math
\boxed{
\int_{-\infty}^{+\infty}|\Psi(x,t)|^2dx=1
}
```

这叫归一化条件。

若给定波函数

```math
\psi(x)=A f(x)
```

求归一化常数 $A$ 的标准做法是：

```math
\int |\psi|^2dx=1
```

即

```math
|A|^2\int|f(x)|^2dx=1
```

所以

```math
|A|
=
\frac{1}
{\sqrt{\int|f(x)|^2dx}}
```

虽然复习要求中“复杂归一化计算”不是重点，但最基本的归一化思想必须理解。

---

### 6. 波函数的标准条件

物理上可接受的波函数通常要求：

1. 单值；
2. 有限；
3. 连续；
4. 平方可积；
5. 在有限势能处，一阶导数通常连续。

为什么要求单值？

因为同一位置的概率密度不能有两个不同数值。

为什么要求有限？

若波函数无限大，概率密度可能发散。

为什么要求平方可积？

因为总概率必须能够归一化为1。

---

### 7. 整体相位不影响物理状态

如果

```math
\Psi'(\boldsymbol r,t)
=
e^{i\alpha}\Psi(\boldsymbol r,t)
```

其中 $\alpha$ 是常数，那么

```math
|\Psi'|^2
=
|e^{i\alpha}|^2|\Psi|^2
=
|\Psi|^2
```

因此 $\Psi$ 和 $e^{i\alpha}\Psi$ 描述同一个物理态。

注意：

- 整体相位没有物理意义；
- 不同分量之间的相对相位有物理意义，因为它会影响干涉。

---

## 六、态叠加原理

若 $\psi_1$ 和 $\psi_2$ 都是可能的量子态，那么

```math
\boxed{
\psi=c_1\psi_1+c_2\psi_2
}
```

也可以是一个可能的量子态。

这叫态叠加原理。

---

### 1. 为什么叠加不是普通概率相加

若两条路径对应概率幅 $\psi_1,\psi_2$ ，总概率幅为

```math
\psi=\psi_1+\psi_2
```

则概率密度为

```math
|\psi|^2
=
|\psi_1+\psi_2|^2
```

展开：

```math
|\psi|^2
=
|\psi_1|^2+|\psi_2|^2
+\psi_1^*\psi_2+\psi_2^*\psi_1
```

后两项是干涉项。

因此

```math
\boxed{
P_{12}\neq P_1+P_2
}
```

这正是双缝干涉的根源。

---

### 2. 测量路径为何破坏干涉

只要实验能够区分电子经过哪条缝，两个路径态就与测量装置发生纠缠，使相干交叉项消失。

于是概率从

```math
|\psi_1+\psi_2|^2
```

转变为

```math
|\psi_1|^2+|\psi_2|^2
```

干涉条纹消失。

这里的关键不只是“观察者看了一眼”，而是：

```math
\boxed{\text{路径信息被物理装置记录}}
```

---

## 七、薛定谔方程

---

### 1. 薛定谔方程在量子力学中的地位

经典力学的核心方程是

```math
m\frac{d^2\boldsymbol r}{dt^2}=\boldsymbol F
```

量子力学的核心方程是薛定谔方程。

它告诉我们：

> 已知初始波函数和体系的势能，波函数今后如何演化。

课件指出，薛定谔方程在量子力学中的地位相当于牛顿方程在经典力学中的地位。

---

### 2. 一维含时薛定谔方程

```math
\boxed{
i\hbar\frac{\partial\Psi(x,t)}{\partial t}
=
\left[
-\frac{\hbar^2}{2m}
\frac{\partial^2}{\partial x^2}
+
V(x,t)
\right]\Psi(x,t)
}
```

三维形式为

```math
\boxed{
i\hbar\frac{\partial\Psi}{\partial t}
=
\left[
-\frac{\hbar^2}{2m}\nabla^2+V(\boldsymbol r,t)
\right]\Psi
}
```

其中

```math
\nabla^2
=
\frac{\partial^2}{\partial x^2}
+
\frac{\partial^2}{\partial y^2}
+
\frac{\partial^2}{\partial z^2}
```

---

### 3. 哈密顿算符

经典力学中总能量为

```math
E=\frac{p^2}{2m}+V
```

在量子力学中，动量用算符

```math
\hat p_x=-i\hbar\frac{\partial}{\partial x}
```

表示，因此

```math
\hat p_x^2
=
-\hbar^2\frac{\partial^2}{\partial x^2}
```

总能量算符为

```math
\boxed{
\hat H
=
-\frac{\hbar^2}{2m}\nabla^2+V
}
```

于是含时薛定谔方程可以写成

```math
\boxed{
i\hbar\frac{\partial\Psi}{\partial t}
=
\hat H\Psi
}
```

---

### 4. 为什么动量算符是微分算符

考虑自由粒子平面波：

```math
\psi(x)=Ae^{ipx/\hbar}
```

对它求导：

```math
\frac{d\psi}{dx}
=
\frac{ip}{\hbar}\psi
```

整理：

```math
-i\hbar\frac{d\psi}{dx}
=
p\psi
```

所以作用在该波函数上的算符

```math
-i\hbar\frac{d}{dx}
```

返回动量本身 $p$ 。

因此定义

```math
\boxed{
\hat p_x=-i\hbar\frac{d}{dx}
}
```

---

## 八、定态薛定谔方程与能量本征值

若势能与时间无关：

```math
V=V(\boldsymbol r)
```

可以设

```math
\Psi(\boldsymbol r,t)
=
\psi(\boldsymbol r)T(t)
```

代入含时薛定谔方程，可分离得到：

```math
T(t)=e^{-iEt/\hbar}
```

空间部分满足

```math
\boxed{
\hat H\psi=E\psi
}
```

也就是

```math
\boxed{
\left[
-\frac{\hbar^2}{2m}\nabla^2+V
\right]\psi
=
E\psi
}
```

这叫定态薛定谔方程，也叫能量本征方程。

课件将其写为

```math
\hat H\psi_n=E_n\psi_n
```

其中 $E_n$ 是可能的能量本征值， $\psi_n$ 是相应的本征函数；求解该方程是量子力学的核心任务。

---

### 1. 本征值和本征函数

如果一个算符作用在某个函数上，只得到该函数乘以一个常数：

```math
\hat A\psi=a\psi
```

则：

- $\psi$ 是算符 $\hat A$ 的本征函数；
- $a$ 是对应的本征值。

例如：

```math
\hat p_xe^{ikx}
=
-i\hbar\frac{d}{dx}e^{ikx}
=
\hbar k e^{ikx}
```

因此 $e^{ikx}$ 是动量算符的本征函数，本征值为

```math
p_x=\hbar k
```

---

### 2. 定态为什么叫“定态”

定态波函数为

```math
\Psi_n(\boldsymbol r,t)
=
\psi_n(\boldsymbol r)e^{-iE_nt/\hbar}
```

其概率密度：

```math
|\Psi_n|^2
=
|\psi_n|^2
\left|e^{-iE_nt/\hbar}\right|^2
```

因为

```math
\left|e^{-iE_nt/\hbar}\right|^2=1
```

所以

```math
|\Psi_n(\boldsymbol r,t)|^2
=
|\psi_n(\boldsymbol r)|^2
```

不随时间变化。

因此“定态”不是说波函数本身不随时间变化，而是：

```math
\boxed{\text{定态的概率密度和可观测分布不随时间变化}}
```

---

## 九、一维无限深势阱

这是本章最重要、最典型的计算模型。

---

### 1. 模型

设粒子只能在

```math
0\lt x\lt a
```

范围内运动。

势能为

```math
V(x)=
\begin{cases}
0,&0\lt x\lt a\\
\infty,&x\leq0\text{ 或 }x\geq a
\end{cases}
```

物理意义是：

- 势阱内部粒子自由运动；
- 势阱外势能无限大，粒子绝不可能出现。

---

### 2. 势阱内的薛定谔方程

在阱内 $V=0$ ，定态方程为

```math
-\frac{\hbar^2}{2m}
\frac{d^2\psi}{dx^2}
=
E\psi
```

整理：

```math
\frac{d^2\psi}{dx^2}
+
\frac{2mE}{\hbar^2}\psi
=
0
```

令

```math
k^2=\frac{2mE}{\hbar^2}
```

得到

```math
\frac{d^2\psi}{dx^2}+k^2\psi=0
```

一般解：

```math
\psi(x)=A\sin kx+B\cos kx
```

---

### 3. 边界条件

因为阱外波函数为零，并要求波函数连续，所以

```math
\psi(0)=0
```

```math
\psi(a)=0
```

由

```math
\psi(0)=B=0
```

得到

```math
\psi(x)=A\sin kx
```

再由

```math
\psi(a)=A\sin ka=0
```

非零解要求

```math
\sin ka=0
```

所以

```math
ka=n\pi
```

即

```math
\boxed{
k_n=\frac{n\pi}{a},
\qquad n=1,2,3,\ldots
}
```

注意不能取 $n=0$ ，因为此时 $\psi=0$ ，表示全空间找到粒子的概率为零，不是物理态。

---

### 4. 能级

由

```math
E=\frac{\hbar^2k^2}{2m}
```

得到

```math
\boxed{
E_n
=
\frac{n^2\pi^2\hbar^2}{2ma^2}
=
\frac{n^2h^2}{8ma^2}
}
```

其中

```math
n=1,2,3,\ldots
```

课件复习材料也把无限深势阱的能级写为上述形式，并强调基态能量非零、粒子概率分布不均匀。

---

### 5. 归一化波函数

波函数为

```math
\psi_n(x)=A\sin\frac{n\pi x}{a}
```

归一化条件：

```math
\int_0^a|\psi_n(x)|^2dx=1
```

即

```math
A^2\int_0^a
\sin^2\frac{n\pi x}{a}dx
=1
```

利用

```math
\int_0^a
\sin^2\frac{n\pi x}{a}dx
=
\frac a2
```

得到

```math
A^2\frac a2=1
```

所以

```math
A=\sqrt{\frac2a}
```

因此

```math
\boxed{
\psi_n(x)
=
\sqrt{\frac2a}
\sin\frac{n\pi x}{a}
}
```

完整写法：

```math
\psi_n(x)=
\begin{cases}
\sqrt{\frac2a}\sin\frac{n\pi x}{a},&0\lt x\lt a\\
0,&\text{其他}
\end{cases}
```

---

### 6. 概率密度

```math
\boxed{
|\psi_n(x)|^2
=
\frac2a
\sin^2\frac{n\pi x}{a}
}
```

这与经典粒子在阱中各处概率均匀完全不同。

#### 基态 $n=1$

```math
|\psi_1|^2
=
\frac2a
\sin^2\frac{\pi x}{a}
```

在

```math
x=\frac a2
```

概率密度最大。

在两侧阱壁：

```math
x=0,\quad x=a
```

概率密度为零。

#### 第一激发态 $n=2$

```math
|\psi_2|^2
=
\frac2a
\sin^2\frac{2\pi x}{a}
```

在

```math
x=\frac a2
```

存在内部节点。

---

### 7. 节点数

无限深势阱第 $n$ 个本征态有

```math
\boxed{n-1}
```

个内部节点。

节点是波函数为零、概率密度也为零的位置。

---

### 8. 为什么基态能量不为零

基态能量为

```math
E_1=\frac{\pi^2\hbar^2}{2ma^2}\gt 0
```

若基态能量为零，则

```math
p=0
```

也就是

```math
\Delta p=0
```

同时粒子被限制在有限宽度 $a$ 内：

```math
\Delta x\lt \infty
```

这将违反

```math
\Delta x\Delta p\geq\frac{\hbar}{2}
```

所以受限粒子不能完全静止。

这种最低的非零能量称为零点能。

---

### 9. 能级间隔

```math
E_n=n^2E_1
```

相邻能级间隔：

```math
E_{n+1}-E_n
=
[(n+1)^2-n^2]E_1
```

```math
\boxed{
\Delta E=(2n+1)E_1
}
```

因此无限深势阱的相邻能级并不是等间距，而是随着 $n$ 增大而增大。

---

### 10. 高频极限与经典对应

当 $n$ 很大时，波函数振荡非常快。

实验仪器通常无法分辨微小空间尺度内的快速振荡，只能测得平均概率密度：

```math
\overline{\sin^2}= \frac12
```

于是

```math
\overline{|\psi_n|^2}
=
\frac2a\cdot\frac12
=
\frac1a
```

这正是经典粒子在阱内均匀分布的结果。

这体现了对应原理：

```math
\boxed{
\text{大量子数极限下，量子规律趋近经典规律}
}
```

---

## 十、一维无限深势阱典型题

### 例题1：电子在宽度 $a=1.0\,\mathrm{nm}$ 的无限深势阱中的基态能量

```math
E_1=\frac{h^2}{8m_ea^2}
```

代入：

```math
h=6.626\times10^{-34}\ \mathrm{J\,s}
```

```math
m_e=9.109\times10^{-31}\ \mathrm{kg}
```

```math
a=1.0\times10^{-9}\ \mathrm m
```

得到

```math
E_1
\approx
6.02\times10^{-20}\ \mathrm J
```

转化为 eV：

```math
E_1
=
\frac{6.02\times10^{-20}}
{1.602\times10^{-19}}
```

```math
\boxed{E_1\approx0.376\ \mathrm{eV}}
```

于是

```math
E_2=4E_1\approx1.50\ \mathrm{eV}
```

```math
E_3=9E_1\approx3.38\ \mathrm{eV}
```

---

### 例题2：从 $n=3$ 跃迁到 $n=1$ 发射光子能量

```math
h\nu=E_3-E_1
```

```math
E_3-E_1=(9-1)E_1=8E_1
```

因此

```math
h\nu=8\times0.376\ \mathrm{eV}
```

```math
\boxed{h\nu\approx3.01\ \mathrm{eV}}
```

波长：

```math
\lambda=\frac{hc}{\Delta E}
```

使用

```math
hc\approx1240\ \mathrm{eV\,nm}
```

得到

```math
\lambda
=
\frac{1240}{3.01}
```

```math
\boxed{\lambda\approx412\ \mathrm{nm}}
```

---

### 例题3：基态粒子在左半边的概率

求

```math
0\lt x\lt \frac a2
```

内找到粒子的概率。

```math
P
=
\int_0^{a/2}
\frac2a\sin^2\frac{\pi x}{a}dx
```

由于基态概率密度关于 $x=a/2$ 对称，所以直接得到

```math
\boxed{P=\frac12}
```

这种题不一定要硬积分，先观察对称性。

---

### 例题4：基态粒子在中间三分之一区域的概率

范围：

```math
\frac a3\lt x\lt \frac{2a}3
```

```math
P=
\int_{a/3}^{2a/3}
\frac2a\sin^2\frac{\pi x}{a}dx
```

利用

```math
\int\sin^2 u\,du
=
\frac u2-\frac{\sin2u}{4}
```

得到

```math
P
=
\frac13+\frac{\sqrt3}{2\pi}
```

数值约为

```math
\boxed{P\approx0.609}
```

这说明基态粒子更容易出现在势阱中间。

---

## 十一、线性谐振子：需要理解的结论

线性谐振子势能：

```math
V(x)=\frac12m\omega^2x^2
```

定态薛定谔方程为

```math
-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2}
+
\frac12m\omega^2x^2\psi
=
E\psi
```

课程通常不要求完整求解，但要记住能级：

```math
\boxed{
E_n=
\left(n+\frac12\right)\hbar\omega,
\qquad n=0,1,2,\ldots
}
```

注意这里量子数从 $n=0$ 开始。

### 1. 能级等间距

```math
E_{n+1}-E_n=\hbar\omega
```

与无限深势阱不同，谐振子能级是等间距的。

### 2. 零点能

基态 $n=0$ ：

```math
\boxed{
E_0=\frac12\hbar\omega
}
```

即使在最低能态，粒子也不能完全静止。

### 3. 奇偶性

谐振子势能满足

```math
V(-x)=V(x)
```

因此波函数具有确定宇称：

```math
\psi_n(-x)=(-1)^n\psi_n(x)
```

- $n$ 为偶数：偶宇称；
- $n$ 为奇数：奇宇称。

---

## 十二、宇称

---

### 1. 定义

若

```math
\psi(-x)=\psi(x)
```

则为偶宇称。

若

```math
\psi(-x)=-\psi(x)
```

则为奇宇称。

---

### 2. 宇称的基本性质

偶函数乘偶函数为偶函数；

奇函数乘奇函数为偶函数；

偶函数乘奇函数为奇函数。

在对称区间上：

```math
\int_{-a}^{a}\text{奇函数}\,dx=0
```

这一点在计算平均值和跃迁矩阵元时非常有用。

---

### 3. 对称势场中的定态

若势能满足

```math
V(-x)=V(x)
```

则能量本征函数可选为奇函数或偶函数。

例如以原点为中心的无限深势阱和谐振子势都具有宇称对称性。

---

## 十三、力学量与算符

量子力学与经典力学最大的数学区别之一是：

> 经典力学中的物理量，在量子力学中由算符表示。

---

### 1. 常见算符

#### 位置算符

```math
\boxed{\hat x=x}
```

即直接乘以 $x$ 。

#### 一维动量算符

```math
\boxed{
\hat p_x=-i\hbar\frac{\partial}{\partial x}
}
```

#### 动能算符

```math
\boxed{
\hat T
=
-\frac{\hbar^2}{2m}\nabla^2
}
```

#### 总能量算符

```math
\boxed{
\hat H
=
-\frac{\hbar^2}{2m}\nabla^2+V
}
```

#### 角动量算符

```math
\boxed{
\hat{\boldsymbol L}
=
\boldsymbol r\times\hat{\boldsymbol p}
}
```

其中

```math
\hat L_x
=
-i\hbar
\left(
y\frac{\partial}{\partial z}
-z\frac{\partial}{\partial y}
\right)
```

```math
\hat L_y
=
-i\hbar
\left(
z\frac{\partial}{\partial x}
-x\frac{\partial}{\partial z}
\right)
```

```math
\hat L_z
=
-i\hbar
\left(
x\frac{\partial}{\partial y}
-y\frac{\partial}{\partial x}
\right)
```

球坐标中最常用的是

```math
\boxed{
\hat L_z
=
-i\hbar\frac{\partial}{\partial\varphi}
}
```

---

### 2. 力学量平均值

若粒子处于归一化波函数 $\psi$ ，力学量 $A$ 的平均值为

```math
\boxed{
\langle A\rangle
=
\int\psi^*\hat A\psi\,d\tau
}
```

一维坐标平均值：

```math
\boxed{
\langle x\rangle
=
\int_{-\infty}^{+\infty}
\psi^*x\psi\,dx
}
```

动量平均值：

```math
\boxed{
\langle p_x\rangle
=
\int
\psi^*
\left(
-i\hbar\frac{\partial}{\partial x}
\right)\psi\,dx
}
```

位置平方平均值：

```math
\langle x^2\rangle
=
\int\psi^*x^2\psi\,dx
```

动量平方平均值：

```math
\langle p_x^2\rangle
=
\int
\psi^*
\left(
-\hbar^2\frac{\partial^2}{\partial x^2}
\right)\psi\,dx
```

---

### 3. 测量值与本征值

若

```math
\hat A\psi=a\psi
```

则在状态 $\psi$ 中测量 $A$ ，一定得到

```math
a
```

且

```math
\Delta A=0
```

若波函数是多个本征态叠加：

```math
\psi=\sum_n c_n\psi_n
```

其中

```math
\hat A\psi_n=a_n\psi_n
```

则测量结果只能是某个本征值 $a_n$ ，其概率为

```math
\boxed{|c_n|^2}
```

前提是本征函数已经正交归一。

---

## 十四、对易关系与不确定关系

两个算符的对易子定义为

```math
[\hat A,\hat B]
=
\hat A\hat B-\hat B\hat A
```

对于位置和动量：

```math
\boxed{
[\hat x,\hat p_x]=i\hbar
}
```

简单验证：

```math
[\hat x,\hat p_x]\psi
=
x\left(-i\hbar\frac{d\psi}{dx}\right)
-
\left(-i\hbar\frac{d}{dx}\right)(x\psi)
```

第二项：

```math
-i\hbar\frac{d}{dx}(x\psi)
=
-i\hbar
\left(
\psi+x\frac{d\psi}{dx}
\right)
```

所以

```math
[\hat x,\hat p_x]\psi
=
i\hbar\psi
```

因此

```math
[\hat x,\hat p_x]=i\hbar
```

一般不确定关系：

```math
\boxed{
\Delta A\,\Delta B
\geq
\frac12
\left|
\langle[\hat A,\hat B]\rangle
\right|
}
```

代入位置和动量：

```math
\Delta x\,\Delta p_x
\geq
\frac{\hbar}{2}
```

因此不确定关系并不是额外加上的经验规定，而与算符不对易直接相关。

---

## 十五、角动量量子化

这是连接第三章和第四章的关键。

---

### 1. 角动量平方本征值

量子力学中：

```math
\boxed{
\hat L^2\psi
=
l(l+1)\hbar^2\psi
}
```

因此角动量大小为

```math
\boxed{
L=\sqrt{l(l+1)}\hbar
}
```

其中

```math
\boxed{
l=0,1,2,\ldots
}
```

---

### 2. 角动量 $z$ 分量

```math
\boxed{
\hat L_z\psi
=
m\hbar\psi
}
```

因此

```math
\boxed{
L_z=m\hbar
}
```

其中

```math
\boxed{
m=-l,-l+1,\ldots,0,\ldots,l-1,l
}
```

对给定 $l$ ，共有

```math
\boxed{2l+1}
```

种空间取向。

---

### 3. 为什么不能同时确定三个分量

角动量分量满足：

```math
[\hat L_x,\hat L_y]=i\hbar\hat L_z
```

循环地还有

```math
[\hat L_y,\hat L_z]=i\hbar\hat L_x
```

```math
[\hat L_z,\hat L_x]=i\hbar\hat L_y
```

因此 $L_x,L_y,L_z$ 不能同时精确确定。

但

```math
[\hat L^2,\hat L_z]=0
```

所以可以同时确定：

- 角动量大小 $L^2$ ；
- 某一指定方向的分量 $L_z$ 。

这就是为什么用 $l,m$ 两个量子数描述轨道角动量。

---

### 4. 与玻尔模型的区别

玻尔模型中：

```math
L=n\hbar
```

量子力学中：

```math
L=\sqrt{l(l+1)}\hbar
```

并且

```math
l=0,1,\ldots,n-1
```

例如氢原子基态：

```math
n=1,\quad l=0
```

所以

```math
L=0
```

这与玻尔模型中基态 $L=\hbar$ 不同。

因此玻尔所谓“电子沿圆轨道绕核转动”，不能看作现代量子力学中的真实图像。

---

## 十六、氢原子的薛定谔方程

---

### 1. 势能

电子与原子核之间是库仑吸引：

```math
V(r)
=
-\frac{1}{4\pi\varepsilon_0}
\frac{Ze^2}{r}
```

类氢离子中核电荷为 $+Ze$ 。

定态薛定谔方程：

```math
\left[
-\frac{\hbar^2}{2\mu}\nabla^2
-
\frac{Ze^2}{4\pi\varepsilon_0r}
\right]
\psi
=
E\psi
```

这里更准确地使用约化质量：

```math
\mu=\frac{m_eM}{m_e+M}
```

若核质量远大于电子质量，可近似取

```math
\mu\approx m_e
```

---

### 2. 为什么使用球坐标

氢原子势能只依赖 $r$ ，不依赖方向：

```math
V=V(r)
```

体系具有球对称性，因此采用球坐标：

```math
(r,\theta,\varphi)
```

设波函数可以分离：

```math
\boxed{
\psi(r,\theta,\varphi)
=
R(r)\Theta(\theta)\Phi(\varphi)
}
```

也常写成

```math
\boxed{
\psi_{nlm}(r,\theta,\varphi)
=
R_{nl}(r)Y_l^m(\theta,\varphi)
}
```

其中 $Y_l^m$ 是球谐函数。

氢原子方程经过分离变量后会得到径向、 $\theta$ 向和 $\varphi$ 向三个方程，并自然出现三个量子数 $n,l,m$ 。

---

## 十七、氢原子的三个量子数

---

### 1. 主量子数 $n$

```math
\boxed{
n=1,2,3,\ldots
}
```

主要决定能量和电子云尺度。

类氢体系能量：

```math
\boxed{
E_n
=
-\frac{\mu Z^2e^4}
{2(4\pi\varepsilon_0)^2\hbar^2}
\frac1{n^2}
}
```

若忽略核质量修正：

```math
\boxed{
E_n
=
-13.6\frac{Z^2}{n^2}\ \mathrm{eV}
}
```

与玻尔模型结果相同，但现在这个结果是薛定谔方程和边界条件自然给出的，而不是人为规定。

---

### 2. 轨道角动量量子数 $l$

```math
\boxed{
l=0,1,2,\ldots,n-1
}
```

决定轨道角动量大小：

```math
L=\sqrt{l(l+1)}\hbar
```

轨道名称：

| $l$ | 符号 |
|---:|:---|
| 0 | $s$ |
| 1 | $p$ |
| 2 | $d$ |
| 3 | $f$ |
| 4 | $g$ |

例如：

- $n=1$ ：只有 $1s$ ；
- $n=2$ ：有 $2s,2p$ ；
- $n=3$ ：有 $3s,3p,3d$ 。

---

### 3. 磁量子数 $m$

```math
\boxed{
m=-l,-l+1,\ldots,l
}
```

决定轨道角动量在指定方向上的投影：

```math
\boxed{
L_z=m\hbar
}
```

每个 $l$ 对应 $2l+1$ 个 $m$ 。

例如 $l=2$ ：

```math
m=-2,-1,0,1,2
```

共有5个状态。

---

## 十八、氢原子能级简并度

忽略自旋时，氢原子的能量只依赖 $n$ ，不依赖 $l,m$ 。

对固定 $n$ ：

```math
l=0,1,\ldots,n-1
```

每个 $l$ 有 $2l+1$ 个 $m$ 。

所以状态总数：

```math
g_n
=
\sum_{l=0}^{n-1}(2l+1)
```

利用前 $n$ 个奇数之和：

```math
1+3+5+\cdots+(2n-1)=n^2
```

得到

```math
\boxed{g_n=n^2}
```

若计入电子自旋的两个取向，则

```math
\boxed{g_n=2n^2}
```

例如 $n=3$ ：

- $l=0$ ：1个；
- $l=1$ ：3个；
- $l=2$ ：5个。

总计：

```math
1+3+5=9
```

即

```math
g_3=3^2=9
```

复习材料明确要求理解简并，并给出氢原子第 $n$ 层忽略自旋时简并度为 $n^2$ 。

---

## 十九、氢原子的电子云与“轨道”

现代量子力学中的“轨道”不是电子运动轨迹，而是：

```math
\boxed{\text{具有确定 }n,l,m\text{ 的单电子波函数}}
```

例如：

- $1s$ 轨道；
- $2s$ 轨道；
- $2p_x$ 轨道；
- $3d$ 轨道。

它描述的是电子概率分布，而不是一条路径。

---

### 1. 径向概率密度

波函数：

```math
\psi_{nlm}=R_{nl}(r)Y_l^m(\theta,\varphi)
```

在体积元

```math
d\tau=r^2\sin\theta\,dr\,d\theta\,d\varphi
```

中找到电子的概率为

```math
|\psi|^2d\tau
```

仅问半径在 $r$ 到 $r+dr$ 之间的概率，需要对所有方向积分：

```math
\boxed{
dP
=
r^2|R_{nl}(r)|^2dr
}
```

因此径向概率分布为

```math
\boxed{
P(r)=r^2|R_{nl}(r)|^2
}
```

有些教材会因径向函数定义不同而写成 $4\pi r^2|\psi|^2$ ，判断时要看其 $R(r)$ 如何定义。

---

### 2. 基态 $1s$ 波函数

氢原子基态：

```math
n=1,\quad l=0,\quad m=0
```

波函数为

```math
\boxed{
\psi_{100}(r)
=
\frac1{\sqrt{\pi a_0^3}}
e^{-r/a_0}
}
```

概率密度：

```math
|\psi_{100}|^2
=
\frac1{\pi a_0^3}e^{-2r/a_0}
```

这个概率密度在 $r=0$ 最大。

但径向概率分布是

```math
P(r)
=
4\pi r^2|\psi_{100}|^2
```

即

```math
P(r)
=
\frac{4r^2}{a_0^3}e^{-2r/a_0}
```

其最大值满足

```math
\frac{dP}{dr}=0
```

可得到

```math
\boxed{r_{\mathrm{mp}}=a_0}
```

所以：

- 单位体积概率密度在核处最大；
- 单位半径球壳内的概率在 $r=a_0$ 最大。

这两个说法并不矛盾，因为球壳体积随 $r^2$ 增大。

---

### 3. 最概然半径

最概然半径指径向概率分布

```math
r^2|R(r)|^2
```

达到最大值的位置。

对于氢原子基态：

```math
\boxed{r_{\mathrm{mp}}=a_0}
```

这与玻尔第一轨道半径相同。

但物理图像不同：

- 玻尔模型：电子固定在半径 $a_0$ 的圆轨道上；
- 量子力学：电子可出现在各种 $r$ ，只是 $r=a_0$ 附近的球壳概率最大。

课件也特别指出，电子可出现在 $0$ 到 $\infty$ 的任意半径，只是概率不同；基态的最概然半径等于玻尔半径。

---

### 4. 径向节点和角节点

氢原子轨道的节点总数为

```math
\boxed{n-1}
```

其中：

#### 径向节点数

```math
\boxed{n-l-1}
```

#### 角节点数

```math
\boxed{l}
```

二者相加：

```math
(n-l-1)+l=n-1
```

例如：

#### $2s$

```math
n=2,\quad l=0
```

径向节点：

```math
2-0-1=1
```

角节点：

```math
0
```

#### $2p$

```math
n=2,\quad l=1
```

径向节点：

```math
2-1-1=0
```

角节点：

```math
1
```

#### $3d$

```math
n=3,\quad l=2
```

径向节点：

```math
3-2-1=0
```

角节点：

```math
2
```

---

## 二十、量子力学如何重新解释玻尔模型

第三章学完后，应当重新理解第二章。

### 1. 能量量子化

玻尔模型：

```math
L=n\hbar
```

是直接规定。

量子力学：

- 解薛定谔方程；
- 要求波函数单值、有限、连续、可归一化；
- 只有某些 $E$ 能满足这些边界条件。

所以能量量子化来自：

```math
\boxed{\text{微分方程与边界条件}}
```

---

### 2. 稳定性

玻尔模型规定定态不辐射。

量子力学中，能量本征态的概率分布不随时间变化：

```math
|\Psi_n(\boldsymbol r,t)|^2
=
|\psi_n(\boldsymbol r)|^2
```

因此原子定态稳定。

---

### 3. 电子轨道

玻尔模型中有确定圆轨道。

量子力学中：

- 没有确定的经典轨迹；
- 只有概率分布；
- “轨道”是波函数，不是路径。

---

### 4. 角动量

玻尔模型：

```math
L=n\hbar
```

量子力学：

```math
L=\sqrt{l(l+1)}\hbar
```

```math
L_z=m\hbar
```

---

### 5. 量子数

玻尔模型主要只有一个量子数 $n$ 。

薛定谔方程解氢原子后自然出现：

```math
n,\quad l,\quad m
```

第四章再加入自旋：

```math
s,\quad m_s
```

---

## 二十一、考试常见题型

---

### 题型一：德布罗意波长

常见条件：

- 已知质量和速度；
- 已知动能；
- 已知电子加速电压。

对应公式：

```math
\lambda=\frac{h}{p}
```

```math
\lambda=\frac{h}{mv}
```

```math
\lambda=\frac{h}{\sqrt{2mE_k}}
```

电子经电压 $U$ 加速：

```math
\lambda=\frac{h}{\sqrt{2m_eeU}}
```

易错点：

- eV必须转换成J，除非使用快捷公式；
- 不能把动能 $E_k$ 错当成总能量 $E$ ；
- 高能电子要考虑相对论修正。

---

### 题型二：晶体衍射

两个公式联立：

```math
\lambda=\frac{h}{\sqrt{2mE_k}}
```

```math
2d\sin\theta=n\lambda
```

注意题目中的角度定义。有些实验给的是入射束与散射束夹角，而布拉格角是射线与晶面夹角，不能机械代入。

---

### 题型三：不确定关系估算

标准步骤：

1. 根据空间限制估计 $\Delta x$ ；
2. 用 $\Delta p\gtrsim\frac{\hbar}{2\Delta x}$ ；
3. 根据具体情况求速度或动能；
4. 判断是否需要相对论。

易错点：

- 原子核尺度下电子通常已不能使用非相对论动能；
- $\Delta p$ 是动量不确定度，不一定等于平均动量，但数量级估算中常取同阶。

---

### 题型四：波函数概率

若给定 $\psi(x)$ ，常问：

- 是否可归一化；
- 求归一化常数；
- 求某区间概率；
- 求最大概率密度位置；
- 判断节点。

核心公式：

```math
\int|\psi|^2dx=1
```

```math
P(a\lt x\lt b)=\int_a^b|\psi|^2dx
```

---

### 题型五：算符和平均值

常问：

```math
\langle x\rangle,\qquad
\langle x^2\rangle,\qquad
\langle p\rangle,\qquad
\langle p^2\rangle
```

记住：

```math
\langle A\rangle
=
\int\psi^*\hat A\psi\,dx
```

动量算符必须作用在右边的波函数上：

```math
\hat p\psi=-i\hbar\frac{d\psi}{dx}
```

不能把 $\hat p$ 当成普通数直接移来移去。

---

### 题型六：无限深势阱

必须会：

```math
E_n=\frac{n^2\pi^2\hbar^2}{2ma^2}
```

```math
\psi_n(x)
=
\sqrt{\frac2a}
\sin\frac{n\pi x}{a}
```

并会判断：

- 基态 $n=1$ ；
- 内部节点数 $n-1$ ；
- 跃迁能量 $E_{n_i}-E_{n_f}$ ；
- 发射光波长；
- 某区间概率。

---

### 题型七：量子数和简并度

必须会判断：

```math
n=1,2,3,\ldots
```

```math
l=0,1,\ldots,n-1
```

```math
m=-l,\ldots,l
```

固定 $n$ 时：

```math
g_n=n^2
```

计入自旋：

```math
g_n=2n^2
```

---

### 题型八：电子云、概率密度与最概然半径

重点区分：

```math
|\psi|^2
```

是单位体积概率密度；

```math
r^2|R(r)|^2
```

是径向概率分布。

不能因为 $1s$ 的 $|\psi|^2$ 在 $r=0$ 最大，就说电子最可能位于核内一个零体积点。求“某一半径附近球壳中”的概率时必须乘 $r^2$ 。

---

## 二十二、必须记住的公式

### A. 波粒二象性

```math
\boxed{E=h\nu=\hbar\omega}
```

```math
\boxed{p=\frac h\lambda=\hbar k}
```

```math
\boxed{\lambda=\frac hp}
```

非相对论：

```math
\boxed{\lambda=\frac{h}{mv}}
```

```math
\boxed{\lambda=\frac{h}{\sqrt{2mE_k}}}
```

电子加速：

```math
\boxed{
\lambda(\mathrm{Å})
\approx
\frac{12.27}{\sqrt{U(\mathrm V)}}
}
```

---

### B. 不确定关系

```math
\boxed{
\Delta x\Delta p_x\geq\frac{\hbar}{2}
}
```

```math
\boxed{
\Delta E\Delta t\gtrsim\frac{\hbar}{2}
}
```

```math
\boxed{
\Delta A\Delta B
\geq
\frac12|\langle[\hat A,\hat B]\rangle|
}
```

---

### C. 波函数

```math
\boxed{
dP=|\Psi|^2d\tau
}
```

```math
\boxed{
\int|\Psi|^2d\tau=1
}
```

```math
\boxed{
\langle A\rangle
=
\int\Psi^*\hat A\Psi\,d\tau
}
```

---

### D. 薛定谔方程

```math
\boxed{
i\hbar\frac{\partial\Psi}{\partial t}
=
\hat H\Psi
}
```

```math
\boxed{
\hat H
=
-\frac{\hbar^2}{2m}\nabla^2+V
}
```

定态方程：

```math
\boxed{
\hat H\psi=E\psi
}
```

---

### E. 算符

```math
\boxed{\hat x=x}
```

```math
\boxed{
\hat p_x=-i\hbar\frac{\partial}{\partial x}
}
```

```math
\boxed{
\hat L_z=-i\hbar\frac{\partial}{\partial\varphi}
}
```

---

### F. 无限深势阱

```math
\boxed{
E_n
=
\frac{n^2\pi^2\hbar^2}{2ma^2}
}
```

```math
\boxed{
\psi_n(x)
=
\sqrt{\frac2a}
\sin\frac{n\pi x}{a}
}
```

---

### G. 角动量

```math
\boxed{
L=\sqrt{l(l+1)}\hbar
}
```

```math
\boxed{
L_z=m\hbar
}
```

---

### H. 氢原子

```math
\boxed{
E_n=-13.6\frac{Z^2}{n^2}\ \mathrm{eV}
}
```

```math
\boxed{
n=1,2,3,\ldots
}
```

```math
\boxed{
l=0,1,\ldots,n-1
}
```

```math
\boxed{
m=-l,-l+1,\ldots,l
}
```

```math
\boxed{
g_n=n^2
}
```

---

## 二十三、建议记住的常数

| 常数 | 数值 |
|---|---:|
| 普朗克常数 $h$ | $6.626\times10^{-34}\ \mathrm{J\,s}$ |
| 约化普朗克常数 $\hbar$ | $1.055\times10^{-34}\ \mathrm{J\,s}$ |
| 电子质量 $m_e$ | $9.109\times10^{-31}\ \mathrm{kg}$ |
| 元电荷 $e$ | $1.602\times10^{-19}\ \mathrm C$ |
| 光速 $c$ | $2.998\times10^8\ \mathrm{m/s}$ |
| $1\ \mathrm{eV}$ | $1.602\times10^{-19}\ \mathrm J$ |
| $hc$ | $1240\ \mathrm{eV\,nm}$ |
| 玻尔半径 $a_0$ | $5.29\times10^{-11}\ \mathrm m$ |
| 氢基态能量 | $-13.6\ \mathrm{eV}$ |
| 电子静止能量 $m_ec^2$ | $0.511\ \mathrm{MeV}$ |

---

## 二十四、容易失分的概念辨析

### 1. 波函数不是概率

错误：

```math
\Psi=\text{概率}
```

正确：

```math
|\Psi|^2=\text{概率密度}
```

$\Psi$ 是概率幅。

---

### 2. 电子云不是电子物质摊开

电子云图表示大量重复测量的位置概率分布，不表示一个电子被分成许多小块。

---

### 3. “轨道”不是轨迹

原子轨道是波函数 $\psi_{nlm}$ ，不是电子实际走过的一条线。

---

### 4. 不确定关系不是仪器太差

即使使用理想仪器，量子态也不能同时具有任意确定的位置和动量。

---

### 5. 定态不是波函数完全不变

定态波函数含有时间相位：

```math
e^{-iEt/\hbar}
```

真正不变的是概率密度。

---

### 6. $l$ 不是角动量大小本身

```math
L\neq l\hbar
```

而是

```math
L=\sqrt{l(l+1)}\hbar
```

只有投影满足

```math
L_z=m\hbar
```

---

### 7. 基态量子数不一定都是0

无限深势阱常用：

```math
n=1,2,3,\ldots
```

谐振子常用：

```math
n=0,1,2,\ldots
```

必须看具体体系的定义。

---

## 二十五、本章应形成的最终物理图像

学完第三章后，对氢原子的正确认识应当是：

1. 电子不是沿一条确定圆轨道绕核运动；
2. 电子状态由波函数描述；
3. 波函数模平方给出电子出现的概率密度；
4. 能级由薛定谔方程和边界条件决定；
5. 能量量子化不是人为规定，而是本征值问题的结果；
6. $n,l,m$ 是方程分离变量后自然出现的量子数；
7. 角动量大小和空间取向都是量子化的；
8. 原子轨道是概率幅，不是经典轨迹；
9. 在大量子数极限，量子力学逐渐恢复经典力学。

可以把整章压缩为一句话：

```math
\boxed{
\text{量子力学不再追问电子“沿哪条轨道运动”，
而是计算各种测量结果出现的概率。}
}
```

第三章不是简单多学了几条公式，而是完成了从

```math
\text{经典轨迹观}
```

到

```math
\text{量子状态观}
```

的根本转变。
