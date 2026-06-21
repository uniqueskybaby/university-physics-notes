# 第一章　原子的位形：卢瑟福模型

> **用户原始要求**
>
> 先给我详细讲解第一章要求,详细讲清楚其中的前因和后果来龙去脉,也要让我提升做题能力，能举一反三，要求有考试常考的例题,以及详细解析,以及写明白需要我记哪些公式,需要我理解哪个模型,需要我记住哪些常数的数值来方便计算。

第一章的核心问题是：

> **原子内部到底是什么结构？**

### 一、本章究竟研究什么

这一章表面上是在研究 $\alpha$ 粒子散射，实际上是在回答一个更一般的问题：

> 我们无法直接看见原子内部，怎样通过粒子碰撞后的运动，反推出原子内部的结构？

本章逻辑链：

```math
\boxed{
\text{电子被发现}
\rightarrow
\text{汤姆逊模型}
\rightarrow
\alpha\text{ 粒子散射异常}
\rightarrow
\text{汤姆逊模型失败}
\rightarrow
\text{卢瑟福核式模型}
\rightarrow
\text{库仑散射公式}
\rightarrow
\text{散射截面与实验计数}
}
```

学习完本章，应当能够：

- 解释汤姆逊模型为什么在当时具有合理性；
- 解释大角散射为什么能否定汤姆逊模型；
- 建立卢瑟福核式原子的物理图像；
- 理解瞄准距离、散射角和最近接距离；
- 使用卢瑟福散射公式；
- 计算散射概率、计数率和测量时间；
- 判断卢瑟福公式的适用条件。

---

## 二、前因：为什么需要建立原子结构模型

汤姆逊通过阴极射线实验发现：

- 阴极射线是带负电的粒子束；
- 这种粒子普遍存在于各种物质中；
- 其电荷量与氢离子的电荷量大小相同；
- 其质量远小于氢原子质量。

于是得到重要结论：

> 原子不是不可分割的基本粒子，原子内部至少包含电子。

原子整体电中性，而电子带负电，因此内部还必须有带正电的部分。电子质量只占原子质量的一小部分，因此原子的绝大部分质量也来自正电部分。

当时已知：

```math
\text{原子尺度}\sim10^{-10}\,\mathrm m
```

以及：

```math
\frac{m_p}{m_e}\approx1836
```

真正未知的问题是：

> 正电荷、大部分质量和负电子在约 $10^{-10}\,\mathrm m$ 的空间内怎样分布？

---

## 三、汤姆逊原子模型

汤姆逊提出“葡萄干布丁模型”：

- 正电荷和大部分质量均匀分布在整个原子球内；
- 电子像葡萄干一样嵌在均匀正电荷中；
- 整个原子保持电中性。

它能够初步解释：

- 原子为什么整体电中性；
- 电子为什么可以存在于原子内部；
- 原子为什么有确定空间范围；
- 电子受扰动后可能在平衡位置附近振动并发光。

所以，汤姆逊模型并不是毫无根据的猜测。科学模型是否可靠，最终要由实验检验。

---

## 四、为什么使用 $\alpha$ 粒子和金箔

### 1. $\alpha$ 粒子

$\alpha$ 粒子本质上是氦核：

```math
{}^4_2\mathrm{He}^{2+}
```

因此：

```math
Z_1=2,
\qquad
q_\alpha=+2e
```

```math
m_\alpha\approx4u
\approx6.64\times10^{-27}\,\mathrm{kg}
```

典型动能为几个 $\mathrm{MeV}$。

### 2. 为什么不用电子作探针

$\alpha$ 粒子质量约为电子质量的 $7300$ 倍：

```math
m_\alpha\approx7300m_e
```

原子中的电子很难使高速重粒子发生大角偏转。因此，若观察到 $\alpha$ 粒子大角散射，更可能来自原子内部的大质量正电部分。

### 3. 为什么用金箔

金的核电荷数：

```math
Z=79
```

卢瑟福散射截面满足：

```math
\frac{d\sigma}{d\Omega}\propto Z_2^2
```

重元素更容易产生可观测的大角散射。

金的延展性很好，可以制成极薄金箔，减少：

- 多重散射；
- 能量损失；
- 一个粒子连续与多个原子核强烈碰撞。

金核很重，也便于近似看成静止。

---

## 五、盖革—马斯登散射实验

装置基本结构：

```math
\alpha\text{ 源}
\rightarrow
\text{准直装置}
\rightarrow
\text{薄金箔}
\rightarrow
\text{荧光屏或探测器}
```

实验发现：

- 绝大多数粒子几乎直线穿过；
- 大多数散射角小于约 $2^\circ$；
- 少量粒子发生大角散射；
- 约每数千个粒子中有一个散射角大于 $90^\circ$；
- 极少数粒子几乎沿原方向反弹。

真正需要解释的是：

> 为什么高速且很重的 $\alpha$ 粒子，会被一张极薄的金箔弹回来？

---

## 六、汤姆逊模型为什么不能解释大角散射

若正电荷 $+Ze$ 均匀分布在半径为 $R$ 的球内，根据高斯定理，球内距离中心 $r$ 处的电场为：

```math
E(r)
=
\frac{1}{4\pi\varepsilon_0}
\frac{Zer}{R^3}
```

其特点是：

- 中心处电场为零；
- 电场随 $r$ 线性增大；
- 表面处才达到最大。

因此，即使 $\alpha$ 粒子穿过原子中心，也不会遇到特别强的斥力。

点电荷库仑力则满足：

```math
F\propto\frac{1}{r^2}
```

越靠近中心，作用力越强。

### 最大偏转角的估算

设最大横向力约为：

```math
F_{\max}
\approx
\frac{1}{4\pi\varepsilon_0}
\frac{(2e)(Ze)}{R^2}
```

作用时间：

```math
\Delta t\approx\frac{2R}{v}
```

横向动量改变量：

```math
\Delta p_\perp\approx F_{\max}\Delta t
```

小角近似：

```math
\theta\approx\frac{\Delta p_\perp}{mv}
```

利用：

```math
E=\frac{1}{2}mv^2
```

得到：

```math
\boxed{
\theta_{\max}
\approx
\frac{1}{E}
\frac{1}{R}
\frac{2Ze^2}{4\pi\varepsilon_0}
}
```

---

## 七、例题 1：汤姆逊模型的最大偏转角

动能为 $5\,\mathrm{MeV}$ 的 $\alpha$ 粒子射向金原子，取：

```math
Z=79,
\qquad
R=0.1\,\mathrm{nm}
```

使用：

```math
\frac{e^2}{4\pi\varepsilon_0}
=
1.44\,\mathrm{MeV\cdot fm}
```

换算：

```math
0.1\,\mathrm{nm}
=
10^5\,\mathrm{fm}
```

代入：

```math
\theta_{\max}
\approx
\frac{2\times79\times1.44}
{5\times10^5}
=
4.55\times10^{-4}\,\mathrm{rad}
```

即：

```math
\boxed{
\theta_{\max}\approx0.026^\circ
}
```

这远小于实验中的 $90^\circ$ 甚至 $180^\circ$。

多次随机小角散射的典型累积满足：

```math
\theta_{\mathrm{rms}}
\sim
\sqrt{N}\,\delta\theta
```

而不是 $N\delta\theta$，因此也不能稳定累积成反向散射。

---

## 八、卢瑟福核式模型

卢瑟福提出：

1. 原子的正电荷集中在很小的原子核中；
2. 原子的绝大部分质量也集中在原子核中；
3. 电子分布在原子核外；
4. 原子绝大部分空间是空的。

### 怎样解释实验

#### 大多数粒子直穿

原子核非常小，大多数粒子未靠近原子核，只受弱作用。

#### 少数粒子发生大角散射

少数粒子非常接近原子核。由于：

```math
F=
\frac{1}{4\pi\varepsilon_0}
\frac{Z_1Z_2e^2}{r^2}
```

$r$ 很小时，斥力很大。

#### 极少数粒子反弹

若几乎正对原子核入射，即 $b\approx0$，粒子会受到强烈反向斥力。

大角散射说明的不是“原子核很大”，而是：

> 原子核很小，但正电荷和质量高度集中。

---

## 九、卢瑟福散射的理想模型

计算时作近似：

1. 只发生单次碰撞；
2. 只有库仑相互作用；
3. 原子核和入射粒子可视为点粒子；
4. 忽略核外电子作用；
5. 靶核近似静止；
6. 入射前和散射后粒子远离原子核；
7. 忽略粒子在靶中的明显能量损失。

问题化为：

> 一个电荷为 $Z_1e$、动能为 $E$ 的粒子，在静止的 $Z_2e$ 点电荷库仑场中运动。

---

## 十、三个重要几何量

### 1. 瞄准距离 $b$

若粒子不受力，沿原方向作直线运动，这条直线与原子核中心的垂直距离叫瞄准距离，也称冲量参数。

$b$ 不是实际最近距离。

### 2. 散射角 $\theta$

入射速度和出射速度方向之间的夹角：

```math
0\leq\theta\leq\pi
```

### 3. 最近接距离 $r_{\min}$

真实双曲线轨道上，粒子离原子核最近的距离。

一般：

```math
r_{\min}\neq b
```

---

## 十一、瞄准距离与散射角

定义：

```math
k=
\frac{Z_1Z_2e^2}{4\pi\varepsilon_0}
```

以及特征长度：

```math
\boxed{
a=
\frac{k}{E}
=
\frac{Z_1Z_2e^2}
{4\pi\varepsilon_0E}
}
```

卢瑟福散射关系：

```math
\boxed{
b=\frac{a}{2}\cot\frac{\theta}{2}
}
```

等价地：

```math
\boxed{
\tan\frac{\theta}{2}
=
\frac{a}{2b}
}
```

---

## 十二、$b-\theta$ 关系的推导思路

弹性散射前后速率相同：

```math
|\mathbf v_i|=|\mathbf v_f|=v
```

动量改变量大小：

```math
|\Delta\mathbf p|
=
2mv\sin\frac{\theta}{2}
```

中心力使角动量守恒：

```math
L=mvb
```

又有：

```math
L=mr^2\dot\varphi
```

因此：

```math
dt=\frac{mr^2}{L}\,d\varphi
```

对库仑力冲量积分，利用轨道对称性，可得：

```math
\Delta p
=
\frac{2k}{vb}
\cos\frac{\theta}{2}
```

令两种动量改变量相等：

```math
2mv\sin\frac{\theta}{2}
=
\frac{2k}{vb}
\cos\frac{\theta}{2}
```

结合：

```math
E=\frac{1}{2}mv^2
```

得到：

```math
\boxed{
b=\frac{k}{2E}\cot\frac{\theta}{2}
}
```

---

## 十三、公式的物理意义

当：

```math
b\rightarrow0
```

有：

```math
\theta\rightarrow180^\circ
```

小角度下：

```math
\cot\frac{\theta}{2}\approx\frac{2}{\theta}
```

所以：

```math
\boxed{
\theta\approx\frac{a}{b}
}
```

又因为：

```math
a\propto\frac{Z_1Z_2}{E}
```

所以：

- $b$ 越小，$\theta$ 越大；
- 能量越高，越难偏转；
- 核电荷越大，偏转越强。

---

## 十四、例题 2：由瞄准距离求散射角

动能为 $7.68\,\mathrm{MeV}$ 的 $\alpha$ 粒子在金核上散射，已知：

```math
b=10\,\mathrm{fm},
\qquad
Z_1=2,
\qquad
Z_2=79
```

先求：

```math
a=
\frac{2\times79\times1.44}{7.68}
\approx29.6\,\mathrm{fm}
```

再用：

```math
\tan\frac{\theta}{2}
=
\frac{a}{2b}
=
1.48
```

得到：

```math
\boxed{
\theta\approx112^\circ
}
```

若 $b=100\,\mathrm{fm}$，则 $\theta\approx16.9^\circ$；若 $b=1000\,\mathrm{fm}$，则 $\theta\approx1.7^\circ$。

---

## 十五、参数 $a$ 的物理意义

```math
a=
\frac{Z_1Z_2e^2}
{4\pi\varepsilon_0E}
```

它是库仑作用的特征长度，不是原子半径或原子核半径。

特殊情况：

当 $\theta=90^\circ$ 时：

```math
b=\frac{a}{2}
```

正碰时：

```math
r_{\min}=a
```

---

## 十六、最近接距离

能量守恒：

```math
E
=
\frac{L^2}{2mr_{\min}^2}
+
\frac{k}{r_{\min}}
```

利用：

```math
L=mvb,
\qquad
E=\frac{1}{2}mv^2
```

得到：

```math
1
=
\frac{b^2}{r_{\min}^2}
+
\frac{a}{r_{\min}}
```

解得：

```math
\boxed{
r_{\min}
=
\frac{a+\sqrt{a^2+4b^2}}{2}
}
```

也可写为：

```math
\boxed{
r_{\min}
=
\frac{a}{2}
\left(
1+\csc\frac{\theta}{2}
\right)
}
```

---

## 十七、例题 3：求最近接距离

仍取 $7.68\,\mathrm{MeV}$ 的 $\alpha$ 粒子和金核，若：

```math
\theta=90^\circ
```

已有：

```math
a=29.6\,\mathrm{fm}
```

所以：

```math
r_{\min}
=
\frac{29.6}{2}
\left(
1+\csc45^\circ
\right)
\approx35.7\,\mathrm{fm}
```

答案：

```math
\boxed{
r_{\min}\approx35.7\,\mathrm{fm}
}
```

此时 $b=14.8\,\mathrm{fm}$，说明 $b$ 与 $r_{\min}$ 不相等。

若实验在最近距离 $r_{\min}$ 处仍符合点电荷散射，只能推出：

```math
R_{\mathrm{核}}<r_{\min}
```

因此最近接距离给出的是核半径上限。

---

## 十八、为什么需要散射截面

$b-\theta$ 关系描述单个粒子轨迹，但实验不能测量每个粒子的 $b$。

实验直接测量的是：

- 入射粒子数；
- 靶的厚度；
- 探测器的角度；
- 探测器记录的粒子数。

因此要把不可测的 $b$ 转换成可测的角分布。

---

## 十九、从瞄准圆环到散射圆锥

瞄准距离位于：

```math
b\sim b+db
```

之间的粒子，在入射平面对应圆环面积：

```math
d\sigma=2\pi b\,|db|
```

散射后进入：

```math
\theta\sim\theta+d\theta
```

的空心圆锥，立体角为：

```math
d\Omega
=
2\pi\sin\theta\,d\theta
```

微分散射截面定义为：

```math
\frac{d\sigma}{d\Omega}
```
---

## 二十、立体角

立体角定义为球面面积与半径平方之比：

```math
\Omega=\frac{S}{R^2}
```

整个球面的立体角为：

```math
\Omega_{\mathrm{全}}=4\pi
```

一般微分立体角：

```math
d\Omega
=
\sin\theta\,d\theta\,d\varphi
```

轴对称情况下：

```math
d\Omega
=
2\pi\sin\theta\,d\theta
```

若小探测器面积为 $S$，距散射点为 $R$，且正对散射点：

```math
\boxed{
\Delta\Omega\approx\frac{S}{R^2}
}
```

若探测器法线与粒子方向夹角为 $\beta$：

```math
\Delta\Omega
\approx
\frac{S\cos\beta}{R^2}
```

---

## 二十一、微分散射截面的推导

已知：

```math
b=\frac{a}{2}\cot\frac{\theta}{2}
```

微分：

```math
\left|
\frac{db}{d\theta}
\right|
=
\frac{a}{4}
\csc^2\frac{\theta}{2}
```

入射圆环面积：

```math
d\sigma
=
2\pi b
\left|
\frac{db}{d\theta}
\right|
d\theta
```

散射圆锥立体角：

```math
d\Omega
=
2\pi\sin\theta\,d\theta
```

所以：

```math
\frac{d\sigma}{d\Omega}
=
\frac{b}{\sin\theta}
\left|
\frac{db}{d\theta}
\right|
```

代入并化简：

```math
\boxed{
\frac{d\sigma}{d\Omega}
=
\frac{a^2}
{16\sin^4(\theta/2)}
}
```

即：

```math
\boxed{
\frac{d\sigma}{d\Omega}
=
\left(
\frac{Z_1Z_2e^2}
{16\pi\varepsilon_0E}
\right)^2
\frac{1}
{\sin^4(\theta/2)}
}
```

微分截面不是概率本身，而是单位立体角内的有效散射面积，常用单位为：

```math
\mathrm{m^2/sr}
```

或：

```math
\mathrm{barn/sr}
```

---

## 二十二、卢瑟福公式的比例关系

```math
\frac{d\sigma}{d\Omega}
\propto
Z_1^2Z_2^2
```

```math
\frac{d\sigma}{d\Omega}
\propto
\frac{1}{E^2}
```

```math
\frac{d\sigma}{d\Omega}
\propto
\frac{1}{\sin^4(\theta/2)}
```

因此：

- 入射粒子或靶核电荷数增大，散射显著增强；
- 入射能量增大，散射减弱；
- 小角散射多，大角散射少，背散射极少。

---

## 二十三、例题 4：比较不同角度的散射强度

比较 $60^\circ$ 和 $120^\circ$ 处的微分截面：

```math
\frac{\sigma(60^\circ)}
{\sigma(120^\circ)}
=
\frac{
\sin^4(60^\circ)
}{
\sin^4(30^\circ)
}
```

因为：

```math
\sin60^\circ=\frac{\sqrt3}{2},
\qquad
\sin30^\circ=\frac12
```

所以：

```math
\boxed{
\sigma(60^\circ)
=
9\sigma(120^\circ)
}
```

高频错误是把公式误写成 $\sin^4\theta$。正确分母是：

```math
\sin^4\frac{\theta}{2}
```

---

## 二十四、从截面计算实验计数

设：

- 入射粒子总数为 $N_0$；
- 靶的面原子数密度为 $n_t$；
- 探测器立体角为 $\Delta\Omega$。

探测器计数：

```math
\boxed{
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
}
```

若探测效率为 $\eta$：

```math
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega\,\eta
```

若靶的质量密度为 $\rho$、厚度为 $t$、摩尔质量为 $M$：

```math
\boxed{
n_t
=
\frac{\rho tN_A}{M}
}
```

若每秒入射粒子数为 $I$，测量时间为 $T$：

```math
N_0=IT
```

计数率：

```math
\boxed{
R
=
In_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
}
```

测量时间：

```math
\boxed{
T=\frac{N_{\mathrm{目标}}}{R}
}
```

---

## 二十五、例题 5：求测量时间

已知：

```math
\frac{d\sigma}{d\Omega}
=
1\,\mathrm{b/sr}
```

```math
t=1\,\mu\mathrm m
```

```math
\rho
=
1.93\times10^4\,\mathrm{kg/m^3}
```

```math
M=0.197\,\mathrm{kg/mol}
```

```math
I=10^5\,\mathrm{s^{-1}}
```

```math
\Delta\Omega=0.01\,\mathrm{sr}
```

要求记录 $100$ 个粒子。

先求面原子数密度：

```math
n_t
=
\frac{\rho tN_A}{M}
\approx
5.90\times10^{22}\,\mathrm{m^{-2}}
```

截面换算：

```math
1\,\mathrm b
=
10^{-28}\,\mathrm{m^2}
```

计数率：

```math
R
=
10^5
\times
5.90\times10^{22}
\times
10^{-28}
\times
0.01
```

```math
R
=
5.90\times10^{-3}\,\mathrm{s^{-1}}
```

所以：

```math
T
=
\frac{100}{5.90\times10^{-3}}
\approx
1.69\times10^4\,\mathrm s
```

```math
\boxed{
T\approx4.7\,\mathrm h
}
```

---

## 二十六、大于某个角度的总散射截面

若要求散射角大于 $\theta_0$ 的总截面：

```math
\sigma(\theta>\theta_0)
=
\int_{\theta_0}^{\pi}
\frac{d\sigma}{d\Omega}
d\Omega
```

结果：

```math
\boxed{
\sigma(\theta>\theta_0)
=
\frac{\pi a^2}{4}
\cot^2\frac{\theta_0}{2}
}
```

也可直接用几何方法：

```math
b_0
=
\frac{a}{2}
\cot\frac{\theta_0}{2}
```

所有 $b<b_0$ 的粒子都会有 $\theta>\theta_0$，因此：

```math
\sigma=\pi b_0^2
```

特别地：

```math
\boxed{
\sigma(\theta>90^\circ)
=
\frac{\pi a^2}{4}
}
```

---

## 二十七、例题 6：大于 $90^\circ$ 的散射比例

一束动能为：

```math
E=4.78\,\mathrm{MeV}
```

的 $\alpha$ 粒子入射到厚度：

```math
t=1\,\mu\mathrm m
```

的金箔上。已知：

```math
\rho=1.93\times10^4\,\mathrm{kg/m^3}
```

```math
Z_2=79,
\qquad
M=0.197\,\mathrm{kg/mol}
```

先求：

```math
a
=
\frac{2\times79\times1.44}{4.78}
\approx47.6\,\mathrm{fm}
```

所以：

```math
\sigma_{>90^\circ}
=
\frac{\pi a^2}{4}
\approx
1.78\times10^{-27}\,\mathrm{m^2}
```

即约：

```math
17.8\,\mathrm b
```

面原子数密度：

```math
n_t
\approx
5.90\times10^{22}\,\mathrm{m^{-2}}
```

散射概率：

```math
P=n_t\sigma
\approx
1.05\times10^{-4}
```

换成百分数：

```math
\boxed{
P_{\%}\approx0.0105\%
}
```

约每 $9.5\times10^3$ 个入射粒子中有一个散射到 $90^\circ$ 以上。

---

## 二十八、参数变化题

综合关系：

```math
N_{\mathrm{det}}
\propto
N_0
\frac{\rho t}{M}
\frac{Z_1^2Z_2^2}{E^2}
\frac{\Delta\Omega}
{\sin^4(\theta/2)}
```

| 参数变化 | 计数变化 |
|---|---:|
| 入射粒子数变为 2 倍 | 2 倍 |
| 测量时间变为 3 倍 | 3 倍 |
| 薄靶厚度变为 2 倍 | 2 倍 |
| 探测器面积变为 2 倍 | 2 倍 |
| 探测距离变为 2 倍 | $1/4$ |
| 入射能量变为 2 倍 | $1/4$ |
| 靶核电荷数变为 2 倍 | 4 倍 |
| 入射粒子电荷数变为 2 倍 | 4 倍 |

例：把金靶 $Z=79$ 换成铝靶 $Z=13$，同时把能量降为原来一半：

```math
\frac{R_{\mathrm{Al}}}{R_{\mathrm{Au}}}
=
\left(
\frac{13}{79}
\right)^2
\times4
\approx0.108
```

所以：

```math
\boxed{
R_{\mathrm{Al}}
\approx0.11R_{\mathrm{Au}}
}
```

---

## 二十九、通用做题流程

### 类型一：给 $b$ 求 $\theta$

```math
\tan\frac{\theta}{2}
=
\frac{a}{2b}
```

### 类型二：给 $\theta$ 求 $b$

```math
b=\frac{a}{2}\cot\frac{\theta}{2}
```

### 类型三：求最近接距离

```math
r_{\min}
=
\frac{a}{2}
\left(
1+\csc\frac{\theta}{2}
\right)
```

或：

```math
r_{\min}
=
\frac{a+\sqrt{a^2+4b^2}}{2}
```

### 类型四：求某方向计数

```math
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
```

### 类型五：求大于某角度的比例

```math
P=n_t\sigma(\theta>\theta_0)
```

### 类型六：求测量时间

```math
R
=
In_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
```

```math
T=\frac{N_{\mathrm{目标}}}{R}
```

---

## 三十、必须记住的公式

### 必须默写

```math
\boxed{
a=
\frac{Z_1Z_2e^2}
{4\pi\varepsilon_0E}
}
```

```math
\boxed{
b=\frac{a}{2}\cot\frac{\theta}{2}
}
```

```math
\boxed{
\frac{d\sigma}{d\Omega}
=
\frac{a^2}
{16\sin^4(\theta/2)}
}
```

```math
\boxed{
n_t=\frac{\rho tN_A}{M}
}
```

```math
\boxed{
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
}
```

### 建议记住

```math
\boxed{
r_{\min}
=
\frac{a}{2}
\left(
1+\csc\frac{\theta}{2}
\right)
}
```

```math
\boxed{
\sigma(\theta>\theta_0)
=
\frac{\pi a^2}{4}
\cot^2\frac{\theta_0}{2}
}
```

```math
\boxed{
\Delta\Omega\approx\frac{S}{R^2}
}
```

---

## 三十一、必须记住的常数

```math
\boxed{
\frac{e^2}{4\pi\varepsilon_0}
=
1.44\,\mathrm{MeV\cdot fm}
}
```

```math
\boxed{
N_A
=
6.022\times10^{23}\,\mathrm{mol^{-1}}
}
```

```math
1\,\mathrm{fm}=10^{-15}\,\mathrm m
```

```math
1\,\text{Å}=10^{-10}\,\mathrm m
```

```math
1\,\mathrm{nm}=10^{-9}\,\mathrm m
```

```math
\boxed{
1\,\mathrm b
=
10^{-28}\,\mathrm{m^2}
=
100\,\mathrm{fm^2}
}
```

```math
1\,\mathrm{eV}
=
1.602\times10^{-19}\,\mathrm J
```

```math
1u
=
1.6605\times10^{-27}\,\mathrm{kg}
```

```math
m_\alpha
\approx
6.64\times10^{-27}\,\mathrm{kg}
```

---

## 三十二、常见失分点

1. 把 $\sin^4(\theta/2)$ 错写成 $\sin^4\theta$；
2. 把截面直接当概率，忘记乘靶面密度；
3. 把微分截面当总截面，忘记乘立体角；
4. 把 $b$ 当成最近接距离；
5. 把 $197\,\mathrm{g/mol}$ 直接当成 $197\,\mathrm{kg/mol}$；
6. 忘记 $1\,\mu\mathrm m=10^{-6}\,\mathrm m$；
7. 概率换成百分数时少乘或多乘 $100$；
8. 忘记探测器只覆盖有限立体角。

---

## 三十三、卢瑟福公式何时失效

### 1. 靶太厚

多重散射不可忽略。

### 2. 极小角度

大瞄准距离下，核外电子屏蔽核电荷，纯库仑公式需要修正。

### 3. 能量过高或距离过近

最近接距离接近核半径时，有限核尺寸不可忽略。

### 4. 靶核较轻

轻靶核反冲明显，需要使用质心系：

```math
E_{\mathrm{cm}}
=
E_{\mathrm{lab}}
\frac{M}{M+m}
```

### 5. 粒子明显失能

若穿过靶时能量变化显著，不能把 $E$ 当常数。

---

## 三十四、卢瑟福模型的意义和后果

卢瑟福模型建立了核式原子结构，也开创了利用散射研究微观结构的方法：

```math
\text{已知入射粒子}
+
\text{未知靶结构}
\rightarrow
\text{测量散射角和能量}
\rightarrow
\text{反推内部结构}
```

但它不能解释：

- 原子为什么稳定；
- 电子为什么不坠入原子核；
- 原子为什么发射分立光谱。

因此第二章需要引入玻尔模型。

---

## 三十五、本章最终模型图像

一束高速 $\alpha$ 粒子射向薄金箔：

- 大多数粒子的 $b$ 很大，只发生小角散射；
- 少数粒子的 $b$ 较小，发生大角散射；
- 极少数粒子近似正碰，几乎反向弹回；
- 入射圆环对应散射圆锥；
- 圆环面积除以圆锥立体角得到微分截面；
- 截面乘面密度得到概率；
- 再乘入射数和探测器立体角得到计数。

完整逻辑：

```math
\boxed{
b
\longleftrightarrow
\theta
\longrightarrow
\frac{d\sigma}{d\Omega}
\longrightarrow
P
\longrightarrow
N_{\mathrm{det}}
}
```

---

## 三十六、闭卷自测

1. 汤姆逊模型为什么在当时具有合理性？
2. 为什么均匀正电荷不能产生大角散射？
3. 为什么大角散射说明正电荷集中？
4. 为什么大多数粒子直穿说明原子核很小？
5. $b$、$\theta$、$r_{\min}$ 分别是什么？
6. 为什么 $b$ 越小，$\theta$ 越大？
7. 参数 $a$ 的物理意义是什么？
8. 为什么要从 $b$ 转换到散射截面？
9. 微分截面和概率有什么区别？
10. 为什么计数公式要乘靶面密度？
11. 为什么散射率与 $Z^2/E^2$ 有关？
12. 为什么小角区域受到电子屏蔽修正？
13. 最近接距离为什么只能给出核半径上限？
14. 卢瑟福模型为什么不是完整原子理论？
