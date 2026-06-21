# 第二章　原子的量子态：玻尔模型

> **用户原始要求**
>
> 同样的要求，讲解第二章

第一章解决了一个空间结构问题：

> 原子的正电荷和绝大部分质量集中在很小的原子核中。

但卢瑟福模型一建立，马上产生了更严重的新问题：

> **电子为什么不会掉进原子核？原子为什么只发出若干条确定波长的谱线？**

### 一、本章究竟研究什么

第一章解决了原子的空间结构问题：

> 原子的正电荷和绝大部分质量集中在很小的原子核中。

但卢瑟福模型一建立，立刻产生两个更严重的问题：

1. 电子为什么不会坠入原子核？
2. 原子为什么只发出若干条确定波长的谱线？

本章逻辑链：

```math
\boxed{
\text{卢瑟福模型的困难}
\rightarrow
\text{量子概念}
\rightarrow
\text{氢原子线光谱}
\rightarrow
\text{玻尔三个假设}
\rightarrow
r_n,v_n,E_n
\rightarrow
\text{里德伯公式}
\rightarrow
\text{实验验证与模型局限}
}
```

学习完本章，应当能够：

- 解释卢瑟福模型为什么导致原子坍塌；
- 解释线光谱为什么说明原子能量分立；
- 说清楚玻尔三个基本假设；
- 推导类氢原子的半径、速度和能量；
- 区分能级能量、结合能、激发能和电离能；
- 计算原子跃迁的频率和波长；
- 判断光谱线系及其线系限；
- 使用约化质量分析同位素位移；
- 解释弗兰克—赫兹实验；
- 理解碱金属光谱和量子缺陷；
- 判断玻尔模型的适用范围和局限。

---

## 二、卢瑟福模型为什么不完整

卢瑟福模型把电子看成像行星一样绕原子核运动。

库仑力提供向心力：

```math
\frac{mv^2}{r}
=
\frac{1}{4\pi\varepsilon_0}
\frac{Ze^2}{r^2}
```

但是电子作圆周运动具有向心加速度。按照经典电动力学：

> 加速运动的带电粒子会不断辐射电磁波。

电子一旦辐射，就会损失能量：

- 轨道半径逐渐缩小；
- 运动频率不断变化；
- 最终沿螺旋线坠入原子核。

这称为原子坍塌。

现实中却发现：

- 原子长期稳定；
- 同种原子的性质高度一致；
- 原子受到激发后还能恢复原状；
- 原子发出的是分立线光谱，而不是连续光谱。

因此存在两个根本矛盾。

### 1. 原子稳定性

经典理论预言原子会坍塌，实验中原子稳定。

### 2. 原子光谱

经典理论预言电子能量连续变化，辐射频率也连续变化；实验中却只观察到若干确定频率。

---

## 三、量子概念的出现

### 1. 普朗克能量子

经典理论不能解释黑体辐射。

普朗克提出，物质中的振子吸收和发射能量时，不是连续地交换，而是一份一份地交换。

每一份能量：

```math
\varepsilon=h\nu
```

振子能量取值：

```math
E_n=nh\nu,
\qquad
n=0,1,2,\ldots
```

其中：

```math
h=6.626\times10^{-34}\,\mathrm{J\cdot s}
```

量子化的真正含义是：

> 某些微观物理量不能连续取值，只能取一系列分立值。

### 2. 爱因斯坦光量子

爱因斯坦进一步提出，光本身由一个个光量子组成。

单个光子的能量：

```math
\boxed{
E_\gamma=h\nu=\frac{hc}{\lambda}
}
```

### 3. 玻尔的关键工作

玻尔把三方面结合起来：

- 卢瑟福的核式原子结构；
- 普朗克和爱因斯坦的量子概念；
- 氢原子线光谱的实验规律。

因此玻尔模型是：

```math
\boxed{
\text{卢瑟福经典轨道}
+
\text{量子化条件}
+
\text{光子跃迁}
}
```

它是一种半经典理论：

- 轨道上的运动使用经典力学；
- 允许哪些轨道由量子条件决定；
- 轨道间跃迁使用光子关系 $h\nu=\Delta E$ 。

---

## 四、原子光谱

光谱表示电磁辐射的频率或波长与强度之间的关系。

低压气体放电时，原子受到激发并发光。经过棱镜或光栅后，观察到一条条分立亮线。

原子光谱具有三条基本规律：

1. 光谱是线状的，谱线位置确定；
2. 谱线之间存在规律，可组成线系；
3. 谱线波数可以写成两个光谱项之差。

---

## 五、氢原子巴尔末线系

氢原子可见光谱中的常见谱线：

| 名称 | 跃迁 | 波长 |
|---|---|---:|
| $H_\alpha$ | $3\rightarrow2$ | $656.3\,\mathrm{nm}$ |
| $H_\beta$ | $4\rightarrow2$ | $486.1\,\mathrm{nm}$ |
| $H_\gamma$ | $5\rightarrow2$ | $434.0\,\mathrm{nm}$ |
| $H_\delta$ | $6\rightarrow2$ | $410.2\,\mathrm{nm}$ |

巴尔末经验公式：

```math
\lambda
=
B\frac{n^2}{n^2-4},
\qquad
n=3,4,5,\ldots
```

其中：

```math
B=364.56\,\mathrm{nm}
```

当时最难理解的是：为什么公式中会出现整数平方？

---

## 六、波数、光谱项和里德伯公式

### 1. 波数

定义：

```math
\boxed{
\widetilde\nu=\frac{1}{\lambda}
}
```

频率和波数满足：

```math
\nu=c\widetilde\nu
```

### 2. 里德伯公式

氢原子各线系统一写为：

```math
\boxed{
\frac{1}{\lambda}
=
R_H
\left(
\frac{1}{n_f^2}
-
\frac{1}{n_i^2}
\right)
}
```

其中：

```math
n_i>n_f
```

普通氢的里德伯常数：

```math
\boxed{
R_H
=
1.09678\times10^7\,\mathrm{m^{-1}}
}
```

### 3. 光谱项

写成：

```math
\widetilde\nu
=
T(n_f)-T(n_i)
```

其中：

```math
T(n)=\frac{R_H}{n^2}
```

这暗示每条谱线对应两个原子状态之间的能量差。

---

## 七、玻尔模型的三个基本假设

### 假设一：定态假设

电子只能处于一系列允许的圆形轨道上。

这些允许状态称为定态。电子处于定态时：

- 能量不变；
- 不辐射电磁波；
- 不会逐渐坠入原子核。

### 假设二：频率条件

电子从一个定态跃迁到另一个定态时，才发射或吸收光子。

发射：

```math
\boxed{
h\nu=E_i-E_f
}
```

吸收：

```math
\boxed{
h\nu=E_f-E_i
}
```

统一写为：

```math
\boxed{
h\nu=|\Delta E|
}
```

光子频率由两个能级之差决定，一般不等于电子绕核运动的频率：

```math
\nu_{\text{光子}}
\neq
f_{\text{轨道}}
```

### 假设三：角动量量子化

```math
\boxed{
L=\mu vr=n\hbar
}
```

其中：

```math
n=1,2,3,\ldots
```

```math
\hbar=\frac{h}{2\pi}
```

这条条件从连续的经典轨道中筛选出一系列允许轨道。

---

## 八、类氢体系

玻尔模型最直接适用于单电子体系。

常见类氢体系：

```math
\mathrm H,
\quad
\mathrm{He}^{+},
\quad
\mathrm{Li}^{2+},
\quad
\mathrm{Be}^{3+}
```

共同特点：

- 原子核电荷为 $+Ze$ ；
- 核外只有一个电子。

中性 He、Li、Na 有多个电子，不能直接使用类氢公式。

---

## 九、约化质量

电子和原子核都绕共同质心运动。二体问题可化成约化质量：

```math
\boxed{
\mu=
\frac{m_eM}{m_e+M}
}
```

其中 $M$ 为原子核质量。

若：

```math
M\gg m_e
```

则：

```math
\mu\approx m_e
```

普通计算可用 $m_e$ ；同位素位移和精密计算要使用 $\mu$ 。

---

## 十、玻尔轨道半径的推导

### 第一步：库仑力提供向心力

```math
\frac{\mu v^2}{r}
=
\frac{1}{4\pi\varepsilon_0}
\frac{Ze^2}{r^2}
```

整理：

```math
\mu v^2
=
\frac{Ze^2}
{4\pi\varepsilon_0r}
```

### 第二步：角动量量子化

```math
\mu vr=n\hbar
```

所以：

```math
v=\frac{n\hbar}{\mu r}
```

### 第三步：求半径

代入得到：

```math
\boxed{
r_n
=
\frac{4\pi\varepsilon_0\hbar^2}
{\mu e^2}
\frac{n^2}{Z}
}
```

定义玻尔半径：

```math
\boxed{
a_0
=
\frac{4\pi\varepsilon_0\hbar^2}
{m_e e^2}
=
5.29\times10^{-11}\,\mathrm m
}
```

所以：

```math
\boxed{
r_n
=
a_0
\frac{m_e}{\mu}
\frac{n^2}{Z}
}
```

重核近似：

```math
\boxed{
r_n=\frac{n^2}{Z}a_0
}
```

比例关系：

```math
\boxed{
r_n\propto\frac{n^2}{Z}
}
```

---

## 十一、轨道速度

由角动量条件和半径公式：

```math
v_n
=
\frac{Ze^2}
{4\pi\varepsilon_0\hbar}
\frac{1}{n}
```

定义精细结构常数：

```math
\boxed{
\alpha
=
\frac{e^2}
{4\pi\varepsilon_0\hbar c}
\approx
\frac{1}{137}
}
```

所以：

```math
\boxed{
v_n=\frac{Z\alpha c}{n}
}
```

氢基态速度：

```math
\boxed{
v_1
=
\alpha c
\approx
2.19\times10^6\,\mathrm{m/s}
}
```

---

## 十二、轨道能量

总能量：

```math
E=K+U
```

动能：

```math
K=\frac{1}{2}\mu v^2
```

由向心力条件：

```math
K
=
\frac{1}{2}
\frac{Ze^2}
{4\pi\varepsilon_0r}
```

势能：

```math
U
=
-\frac{Ze^2}
{4\pi\varepsilon_0r}
```

因此：

```math
\boxed{
U=-2K
}
```

```math
\boxed{
E=-K=\frac{U}{2}
}
```

代入允许半径：

```math
\boxed{
E_n
=
-\frac{\mu Z^2e^4}
{2(4\pi\varepsilon_0)^2\hbar^2}
\frac{1}{n^2}
}
```

定义里德伯能量：

```math
\boxed{
\mathrm{Ry}
=
13.606\,\mathrm{eV}
}
```

所以：

```math
\boxed{
E_n
=
-\frac{\mu}{m_e}
13.606
\frac{Z^2}{n^2}\,\mathrm{eV}
}
```

重核近似：

```math
\boxed{
E_n
=
-13.6
\frac{Z^2}{n^2}\,\mathrm{eV}
}
```

---

## 十三、能级图的物理含义

以氢原子为例：

| $n$ | $E_n$ |
|---:|---:|
| 1 | $-13.6\,\mathrm{eV}$ |
| 2 | $-3.40\,\mathrm{eV}$ |
| 3 | $-1.51\,\mathrm{eV}$ |
| 4 | $-0.850\,\mathrm{eV}$ |
| $\infty$ | $0$ |

- $n=1$ 为基态；
- $n=2,3,\ldots$ 为激发态；
- $n\rightarrow\infty$ 对应电离极限；
- 越接近 $E=0$ ，能级越密集。

---

## 十四、四种能量概念

### 1. 能级能量

```math
E_n<0
```

负号表示束缚态。

### 2. 结合能

```math
\boxed{
E_{\mathrm b}=|E_n|
}
```

### 3. 激发能

```math
\boxed{
E_{\mathrm{exc}}
=
E_{n_f}-E_{n_i}
}
```

其中 $n_f>n_i$ 。

### 4. 电离能

```math
\boxed{
E_{\mathrm{ion}}
=
0-E_n
=
|E_n|
}
```

基态电离能等于基态结合能，激发态电离能更小。

---

## 十五、从能级推导光谱

若：

```math
n_i>n_f
```

则：

```math
\frac{hc}{\lambda}
=
E_{n_i}-E_{n_f}
```

代入能级公式：

```math
\boxed{
\frac{1}{\lambda}
=
R_MZ^2
\left(
\frac{1}{n_f^2}
-
\frac{1}{n_i^2}
\right)
}
```

其中：

```math
\boxed{
R_M
=
R_\infty\frac{\mu}{m_e}
}
```

```math
\boxed{
R_\infty
=
1.09737\times10^7\,\mathrm{m^{-1}}
}
```
---

## 十六、氢原子的光谱线系

固定末态 $n_f$ ，改变初态 $n_i$ ，得到一个线系。

| 线系 | 末态 $n_f$ | 主要波段 |
|---|---:|---|
| 赖曼系 | 1 | 紫外 |
| 巴尔末系 | 2 | 可见光和近紫外 |
| 帕邢系 | 3 | 红外 |
| 布拉开系 | 4 | 红外 |
| 普丰德系 | 5 | 远红外 |
| 汉弗莱系 | 6 | 远红外 |

### 1. 最长波长

同一线系中，能量差最小对应相邻跃迁：

```math
n_i=n_f+1
```

因此：

```math
\boxed{
\frac{1}{\lambda_{\max}}
=
RZ^2
\left[
\frac{1}{n_f^2}
-
\frac{1}{(n_f+1)^2}
\right]
}
```

### 2. 最短波长和线系限

能量差最大对应：

```math
n_i\rightarrow\infty
```

所以：

```math
\boxed{
\frac{1}{\lambda_{\min}}
=
\frac{RZ^2}{n_f^2}
}
```

```math
\boxed{
\lambda_{\min}
=
\frac{n_f^2}{RZ^2}
}
```

---

## 十七、例题 1：氢原子的 $H_\alpha$ 线

氢原子从：

```math
n_i=3
```

跃迁到：

```math
n_f=2
```

能级：

```math
E_3
=
-\frac{13.6}{9}
=
-1.511\,\mathrm{eV}
```

```math
E_2
=
-\frac{13.6}{4}
=
-3.400\,\mathrm{eV}
```

光子能量：

```math
E_\gamma
=
E_3-E_2
=
1.889\,\mathrm{eV}
```

使用：

```math
hc\approx1240\,\mathrm{eV\cdot nm}
```

得到：

```math
\lambda
=
\frac{1240}{1.889}\,\mathrm{nm}
\approx656.4\,\mathrm{nm}
```

答案：

```math
\boxed{
\lambda\approx656.3\,\mathrm{nm}
}
```

---

## 十八、例题 2：巴尔末线系的线系限

巴尔末系末态：

```math
n_f=2
```

线系限对应：

```math
n_i\rightarrow\infty
```

所以：

```math
\frac{1}{\lambda_{\min}}
=
\frac{R_H}{4}
```

```math
\boxed{
\lambda_{\min}
=
\frac{4}{R_H}
\approx364.6\,\mathrm{nm}
}
```

也可以从能量看出，电离极限到 $n=2$ 的能量差为 $3.4\,\mathrm{eV}$ ：

```math
\lambda
=
\frac{1240}{3.4}
\approx364.7\,\mathrm{nm}
```

---

## 十九、类氢体系的比例关系

对于同一 $n$ ：

```math
\boxed{
r_n\propto\frac{1}{Z}
}
```

```math
\boxed{
v_n\propto Z
}
```

```math
\boxed{
|E_n|\propto Z^2
}
```

```math
\boxed{
\nu_{\text{跃迁}}\propto Z^2
}
```

```math
\boxed{
\lambda_{\text{跃迁}}\propto\frac{1}{Z^2}
}
```

这些比例关系是比值题和判断题的核心。

---

## 二十、例题 3：H、 $\mathrm{He}^+$ 、 $\mathrm{Li}^{2+}$ 综合比较

忽略约化质量修正。

已知：

```math
a_0=5.29\times10^{-11}\,\mathrm m
```

```math
v_0=2.19\times10^6\,\mathrm{m/s}
```

### 1. 第一、第二玻尔轨道半径

```math
r_n=\frac{n^2}{Z}a_0
```

| 体系 | $r_1$ | $r_2$ |
|---|---:|---:|
| H | $5.29\times10^{-11}\,\mathrm m$ | $2.12\times10^{-10}\,\mathrm m$ |
| $\mathrm{He}^+$ | $2.65\times10^{-11}\,\mathrm m$ | $1.06\times10^{-10}\,\mathrm m$ |
| $\mathrm{Li}^{2+}$ | $1.76\times10^{-11}\,\mathrm m$ | $7.05\times10^{-11}\,\mathrm m$ |

### 2. 第一、第二轨道速度

```math
v_n=\frac{Z}{n}v_0
```

| 体系 | $v_1$ | $v_2$ |
|---|---:|---:|
| H | $2.19\times10^6$ | $1.09\times10^6$ |
| $\mathrm{He}^+$ | $4.38\times10^6$ | $2.19\times10^6$ |
| $\mathrm{Li}^{2+}$ | $6.56\times10^6$ | $3.28\times10^6$ |

单位均为 $\mathrm{m/s}$ 。

### 3. 基态结合能

```math
E_{\mathrm b,1}
=
13.6Z^2\,\mathrm{eV}
```

| 体系 | 基态结合能 |
|---|---:|
| H | $13.6\,\mathrm{eV}$ |
| $\mathrm{He}^+$ | $54.4\,\mathrm{eV}$ |
| $\mathrm{Li}^{2+}$ | $122.4\,\mathrm{eV}$ |

### 4. 基态到第一激发态的激发能

```math
\Delta E_{1\rightarrow2}
=
13.6Z^2
\left(
1-\frac14
\right)
```

即：

```math
\boxed{
\Delta E_{1\rightarrow2}
=
10.2Z^2\,\mathrm{eV}
}
```

| 体系 | 激发能 |
|---|---:|
| H | $10.2\,\mathrm{eV}$ |
| $\mathrm{He}^+$ | $40.8\,\mathrm{eV}$ |
| $\mathrm{Li}^{2+}$ | $91.8\,\mathrm{eV}$ |

### 5. 第一激发态回到基态的波长

```math
\lambda
=
\frac{1240}
{10.2Z^2}\,\mathrm{nm}
```

所以：

```math
\boxed{
\lambda_{2\rightarrow1}
\approx
\frac{121.6}{Z^2}\,\mathrm{nm}
}
```

| 体系 | 波长 |
|---|---:|
| H | $121.6\,\mathrm{nm}$ |
| $\mathrm{He}^+$ | $30.4\,\mathrm{nm}$ |
| $\mathrm{Li}^{2+}$ | $13.5\,\mathrm{nm}$ |

核心趋势：

```math
Z\uparrow
\Rightarrow
r\downarrow,
\quad
v\uparrow,
\quad
|E|\uparrow,
\quad
\lambda\downarrow
```

---

## 二十一、例题 4：由电离能判断离子

某单电子离子的基态电离能为：

```math
54.4\,\mathrm{eV}
```

类氢基态电离能：

```math
E_{\mathrm{ion}}
=
13.6Z^2\,\mathrm{eV}
```

所以：

```math
13.6Z^2=54.4
```

```math
Z=2
```

核电荷数为 $2$ ，核外只有一个电子，因此：

```math
\boxed{
\mathrm{He}^{+}
}
```

---

## 二十二、最多可能出现多少条谱线

若原子被激发到第 $n$ 能级，并允许通过各种中间能级退激，任意两个不同能级之间都可能形成一条谱线。

能级对数：

```math
\boxed{
N=\frac{n(n-1)}{2}
}
```

例如从 $n=4$ 开始：

```math
N=\frac{4\times3}{2}=6
```

可能跃迁：

```math
4\rightarrow3,
\quad
4\rightarrow2,
\quad
4\rightarrow1
```

```math
3\rightarrow2,
\quad
3\rightarrow1,
\quad
2\rightarrow1
```

注意：一个原子的一次退激过程不会同时发出六个光子，但大量原子的不同退激路径可以形成六条谱线。

若题目问最长和最短波长：

- 最大能量差对应最短波长；
- 最小能量差对应最长波长。

对于 $n=4$ ：

```math
\lambda_{\min}\text{ 对应 }4\rightarrow1
```

```math
\lambda_{\max}\text{ 对应 }4\rightarrow3
```

---

## 二十三、吸收光谱的重要限制

处于基态的氢原子只会吸收满足：

```math
h\nu=E_n-E_1
```

的光子，或者吸收能量不小于 $13.6\,\mathrm{eV}$ 的光子发生电离。

例如：

- $10.2\,\mathrm{eV}$ 可引起 $1\rightarrow2$ ；
- $12.09\,\mathrm{eV}$ 可引起 $1\rightarrow3$ ；
- $13.6\,\mathrm{eV}$ 刚好电离；
- $11.0\,\mathrm{eV}$ 不对应允许跃迁，理想孤立氢原子不会吸收。

原子不能吸收一个不匹配的光子，再任意保留多余能量。

---

## 二十四、约化质量与同位素位移

氢和氘的核电荷相同，但核质量不同。

约化质量：

```math
\mu=
\frac{m_eM}{m_e+M}
```

由于：

```math
M_D>M_H
```

所以：

```math
\mu_D>\mu_H
```

有限质量里德伯常数：

```math
R_M
=
R_\infty\frac{\mu}{m_e}
```

因此：

```math
R_D>R_H
```

同一跃迁满足：

```math
\frac{1}{\lambda}\propto R_M
```

所以：

```math
\boxed{
\lambda_D<\lambda_H
}
```

氘谱线位于氢谱线的短波一侧。

物理本质：

> 氘核更重，反冲更小，约化质量更大，束缚能略大，跃迁频率略高，波长略短。

---

## 二十五、例题 5：利用光谱估计氘的质量

同一条巴尔末线测得：

```math
\lambda_H
=
6562.790\,\text{Å}
```

```math
\lambda_D
=
6561.000\,\text{Å}
```

对于同一跃迁：

```math
\frac{\lambda_H}{\lambda_D}
=
\frac{R_D}{R_H}
```

而：

```math
R_M
=
R_\infty
\frac{M}{M+m_e}
```

令：

```math
x_H=\frac{M_H}{m_e},
\qquad
x_D=\frac{M_D}{m_e}
```

```math
q=\frac{\lambda_H}{\lambda_D}
```

则：

```math
q
=
\frac{x_D/(x_D+1)}
{x_H/(x_H+1)}
```

解得：

```math
\boxed{
x_D
=
\frac{qx_H}
{x_H+1-qx_H}
}
```

取：

```math
x_H\approx1836.15
```

可得：

```math
x_D\approx3.68\times10^3
```

又因：

```math
1u\approx1822.89m_e
```

所以：

```math
M_D\approx2.02u
```

用多组谱线平均后约为：

```math
\boxed{
M_D\approx2.01u
}
```

---

## 二十六、弗兰克—赫兹实验

弗兰克—赫兹实验的重要性在于：

> 光谱通过光子间接反映能级；弗兰克—赫兹实验通过电子碰撞直接证明原子只能吸收某些确定能量。

### 1. 装置思想

装置包括：

- 加热阴极；
- 加速电场；
- 低压原子蒸气；
- 栅极；
- 收集极；
- 小的反向遏止电压。

电子经过加速电压 $U$ 后获得动能：

```math
K=eU
```

### 2. 加速电压较低

电子能量不足以激发原子，只能发生弹性碰撞。由于原子远重于电子，电子损失能量很少，收集电流随电压增大而增加。

### 3. 达到第一激发能

当电子动能达到某一特定值时，发生非弹性碰撞：

```math
e^-+\mathrm A
\rightarrow
e^-+\mathrm A^*
```

电子把固定能量交给原子，碰撞后动能下降，不能克服遏止电压，收集电流下降。

### 4. 为什么电流周期性升降

继续增大加速电压后，电子碰撞后还能重新加速，电流再次上升。

当电子总能量足以发生两次、三次激发碰撞时，电流再次下降。

相邻峰或谷的电压间隔：

```math
\boxed{
\Delta U
=
\frac{E_{\mathrm{exc}}}{e}
}
```

若用 $\mathrm{eV}$ 和 $\mathrm V$ ：

```math
\boxed{
E_{\mathrm{exc}}(\mathrm{eV})
=
\Delta U(\mathrm V)
}
```

### 5. 实验证明了什么

它证明：

- 原子不能任意吸收能量；
- 原子存在分立能级；
- 激发具有明确阈值。

它没有证明：

- 电子真实地沿玻尔圆轨道运动；
- 角动量条件一定是 $n\hbar$ 。

---

## 二十七、例题 6：由弗兰克—赫兹曲线求激发能

相邻电流极小值出现在：

```math
U_1=5.2\,\mathrm V
```

```math
U_2=10.1\,\mathrm V
```

```math
U_3=15.0\,\mathrm V
```

相邻间距：

```math
\Delta U_1=4.9\,\mathrm V
```

```math
\Delta U_2=4.9\,\mathrm V
```

所以第一激发能：

```math
\boxed{
E_{\mathrm{exc}}=4.9\,\mathrm{eV}
}
```

若直接退激回基态：

```math
\lambda
=
\frac{1240}{4.9}\,\mathrm{nm}
\approx253\,\mathrm{nm}
```

答案：

```math
\boxed{
\lambda\approx253\,\mathrm{nm}
}
```

实际装置存在接触电势、初始电子能量分布和遏止电压，因此通常使用相邻峰或谷的间隔，而不是第一个极小值的绝对位置。

---

## 二十八、玻尔对应原理

量子数很大时，量子理论应逐渐接近经典理论。

氢原子：

```math
E_n=-\frac{\mathrm{Ry}}{n^2}
```

当 $n\gg1$ 时：

```math
\Delta E
=
E_{n+1}-E_n
\approx
\frac{2\mathrm{Ry}}{n^3}
```

跃迁频率：

```math
\nu_{\mathrm{光}}
=
\frac{\Delta E}{h}
```

在高 $n$ 极限下趋近经典轨道频率。

对应原理的含义是：

```math
\boxed{
n\gg1
\text{ 时，量子理论逐渐过渡到经典理论}
}
```

不是说所有能级上的光子频率都等于轨道频率。

---

## 二十九、玻尔—索末菲修正

玻尔只考虑圆轨道。

索末菲进一步引入：

- 椭圆轨道；
- 相对论修正；
- 更多量子数。

旧量子论中使用：

```math
n,\quad l,\quad m
```

大致描述：

- 轨道大小；
- 轨道形状；
- 轨道平面取向。

不同运动状态可能具有相同能量，这称为简并。

这些确定轨道图像后来被量子力学的波函数取代。
---

## 三十、碱金属为什么近似像氢

碱金属如 Li、Na、K 的最外层只有一个价电子。

原子核和内层闭合电子壳层合称原子实。

在很远处：

- 原子核电荷为 $+Ze$ ；
- 内层电子总电荷约为 $-(Z-1)e$ ；
- 价电子感受到的净电荷约为 $+e$ 。

因此高激发态价电子近似像氢原子电子。

---

## 三十一、碱金属为什么不完全像氢

价电子还受到：

- 内层电子屏蔽；
- 原子实极化；
- 轨道贯穿。

因此能量不再只依赖 $n$ ，还依赖轨道角量子数 $l$ 。

### 1. 轨道贯穿

某些价电子轨道会进入内层电子云区域。

贯穿越深，屏蔽越弱，价电子感受到的有效核电荷越大，束缚越强。

一般：

```math
\boxed{
s>p>d>f
}
```

相同主量子数下通常：

```math
E_{ns}<E_{np}<E_{nd}<E_{nf}
```

这里能量更小表示更负、束缚更强。

### 2. 原子实极化

价电子的电场会使原子实内部正负电荷分布发生微小相对位移，形成诱导偶极矩，并对价电子产生额外吸引。

---

## 三十二、量子缺陷

碱金属价电子能量常写为：

```math
\boxed{
E_{nl}
=
-\frac{hcR}
{(n-\delta_l)^2}
}
```

其中 $\delta_l$ 称为量子缺陷。

定义有效主量子数：

```math
\boxed{
n^*=n-\delta_l
}
```

一般：

```math
\delta_s>\delta_p>\delta_d>\delta_f\approx0
```

原因是 $s$ 轨道贯穿最强，受原子实影响最大； $f$ 轨道贯穿很弱，最接近氢原子。

---

## 三十三、碱金属光谱四个线系

以钠的基态 $3s$ 为例，电偶极跃迁的基本选择规则：

```math
\boxed{
\Delta l=\pm1
}
```

### 1. 主线系

```math
np\rightarrow3s
```

### 2. 锐线系

```math
ns\rightarrow3p
```

### 3. 漫线系

```math
nd\rightarrow3p
```

### 4. 基线系

```math
nf\rightarrow3d
```

考试中应当能够根据能级图判断线系的初态、末态和线系限。

---

## 三十四、例题 7：由锂光谱求激发能和电离能

已知锂原子：

- 主线系最长波长：

```math
\lambda_1=6707\,\text{Å}
```

- 漫线系线系限：

```math
\lambda_2=3519\,\text{Å}
```

换算：

```math
6707\,\text{Å}=670.7\,\mathrm{nm}
```

```math
3519\,\text{Å}=351.9\,\mathrm{nm}
```

### 第一步：第一激发能

锂基态为 $2s$ ，主线系最长波长来自：

```math
2p\rightarrow2s
```

所以：

```math
E_{2p}-E_{2s}
=
\frac{hc}{\lambda_1}
=
\frac{1240}{670.7}
\approx1.85\,\mathrm{eV}
```

因此：

```math
\boxed{
E_{\mathrm{第一激发}}
\approx1.85\,\mathrm{eV}
}
```

### 第二步： $2p$ 态结合能

漫线系：

```math
nd\rightarrow2p
```

线系限对应上能级趋于电离极限：

```math
E_\infty=0
```

所以：

```math
|E_{2p}|
=
\frac{hc}{\lambda_2}
=
\frac{1240}{351.9}
\approx3.52\,\mathrm{eV}
```

### 第三步：基态电离能

```math
E_{\mathrm{ion}}
=
1.85+3.52
=
5.37\,\mathrm{eV}
```

答案：

```math
\boxed{
E_{\mathrm{第一激发}}
\approx1.85\,\mathrm{eV}
}
```

```math
\boxed{
E_{\mathrm{ion}}
\approx5.37\,\mathrm{eV}
}
```

---

## 三十五、重粒子原子和介子原子

玻尔公式也能处理其他带负电粒子绕核运动，只需把电子质量换成约化质量。

若：

```math
\mu\gg m_e
```

则：

```math
r_n\propto\frac{1}{\mu}
```

轨道显著缩小；

```math
|E_n|\propto\mu
```

束缚能显著增大。

介子原子因此可以用来探测原子核内部结构。

---

## 三十六、例题 8：铅的介子原子

已知：

```math
Z=82
```

负介子质量：

```math
m_\pi=273m_e
```

铅核半径：

```math
R_N=7.1\,\mathrm{fm}
```

铅核很重，可近似：

```math
\mu\approx273m_e
```

### 1. 基态半径

```math
r_1
=
a_0
\frac{m_e}{\mu}
\frac{1}{Z}
```

使用：

```math
a_0=5.29\times10^4\,\mathrm{fm}
```

得到：

```math
r_1
=
\frac{5.29\times10^4}
{273\times82}
\,\mathrm{fm}
```

```math
\boxed{
r_1\approx2.36\,\mathrm{fm}
}
```

### 2. 第一激发态半径

```math
r_2=4r_1
```

```math
\boxed{
r_2\approx9.46\,\mathrm{fm}
}
```

### 3. $2\rightarrow1$ 光子能量

基态能量绝对值：

```math
|E_1|
=
13.6\times273\times82^2\,\mathrm{eV}
\approx25.0\,\mathrm{MeV}
```

因此：

```math
\Delta E
=
|E_1|
\left(
1-\frac14
\right)
```

```math
\boxed{
\Delta E\approx18.7\,\mathrm{MeV}
}
```

### 4. 有限核尺寸修正

由于：

```math
r_1=2.36\,\mathrm{fm}<R_N=7.1\,\mathrm{fm}
```

基态轨道已经深入原子核内部。

点电荷势：

```math
V(r)
=
-\frac{Ze^2}
{4\pi\varepsilon_0r}
```

在 $r\rightarrow0$ 时无限变深；但真实原子核电荷分布在有限体积内，核内势能不会无限下降。

因此：

- 基态能量向上移动，绝对值减小；
- 基态受影响比第一激发态更大；
- 两能级间隔减小；
- 共振线光子能量减小；
- 波长增大。

---

## 三十七、玻尔模型的成功

### 1. 解释原子稳定性

通过定态假设，规定允许状态不辐射。

### 2. 解释氢原子线光谱

成功推导：

```math
\frac{1}{\lambda}
=
R_H
\left(
\frac{1}{n_f^2}
-
\frac{1}{n_i^2}
\right)
```

### 3. 给出正确原子尺度

```math
a_0=0.529\,\text{Å}
```

### 4. 给出氢基态能量

```math
E_1=-13.6\,\mathrm{eV}
```

### 5. 解释类氢离子

统一处理 H、 $\mathrm{He}^+$ 、 $\mathrm{Li}^{2+}$ 等单电子体系。

### 6. 解释同位素位移

通过约化质量解释氢和氘的谱线差别。

### 7. 建立能级和跃迁图像

基态、激发态、能级、跃迁和光子能量等概念至今仍在使用。

---

## 三十八、玻尔模型的局限

### 1. 定态不辐射是硬性规定

没有解释为什么某些加速运动的电子不辐射。

### 2. 没有跃迁动力学

不能说明：

- 电子何时跃迁；
- 跃迁概率多大；
- 哪些跃迁允许或禁戒。

### 3. 不能正确处理多电子原子

多电子体系存在电子—电子相互作用，简单的 $Z^2/n^2$ 公式失效。

### 4. 不能解释谱线强度

能给出谱线位置，却不能可靠计算强弱。

### 5. 不能完整解释精细结构

需要相对论、自旋和自旋—轨道耦合。

### 6. 不能完整解释外场分裂

塞曼效应和斯塔克效应需要更完整的量子理论。

### 7. 确定轨道图像不正确

现代量子力学用波函数描述电子，不认为电子沿确定圆轨道运动。

### 8. 角动量量子化形式不准确

玻尔模型：

```math
L=n\hbar
```

现代量子力学：

```math
L=\sqrt{l(l+1)}\hbar
```

氢基态 $l=0$ ，轨道角动量为零，与玻尔圆轨道图像不同。

---

## 三十九、必须记住的公式

### 必须默写

```math
\boxed{
L=\mu vr=n\hbar
}
```

```math
\boxed{
r_n
=
a_0
\frac{m_e}{\mu}
\frac{n^2}{Z}
}
```

重核近似：

```math
\boxed{
r_n=\frac{n^2}{Z}a_0
}
```

```math
\boxed{
v_n=\frac{Z\alpha c}{n}
}
```

```math
\boxed{
E_n
=
-\frac{\mu}{m_e}
13.6\frac{Z^2}{n^2}\,\mathrm{eV}
}
```

```math
\boxed{
h\nu=|E_i-E_f|
}
```

```math
\boxed{
\frac{1}{\lambda}
=
R_MZ^2
\left(
\frac{1}{n_f^2}
-
\frac{1}{n_i^2}
\right)
}
```

### 必须理解并会用

```math
\boxed{
\mu=
\frac{m_eM}
{m_e+M}
}
```

```math
\boxed{
R_M
=
R_\infty
\frac{\mu}{m_e}
}
```

```math
\boxed{
E_{\mathrm b}=|E_n|
}
```

```math
\boxed{
E_{\mathrm{exc}}=E_f-E_i
}
```

```math
\boxed{
E_{\mathrm{ion}}=-E_n
}
```

```math
\boxed{
N=\frac{n(n-1)}{2}
}
```

```math
\boxed{
E_{nl}
=
-\frac{hcR}
{(n-\delta_l)^2}
}
```

---

## 四十、必须记住的常数

```math
\boxed{
h
=
6.626\times10^{-34}\,\mathrm{J\cdot s}
}
```

```math
\boxed{
\hbar
=
1.055\times10^{-34}\,\mathrm{J\cdot s}
}
```

```math
\boxed{
c
=
2.998\times10^8\,\mathrm{m/s}
}
```

```math
\boxed{
e
=
1.602\times10^{-19}\,\mathrm C
}
```

```math
\boxed{
m_e
=
9.109\times10^{-31}\,\mathrm{kg}
}
```

```math
\boxed{
1\,\mathrm{eV}
=
1.602\times10^{-19}\,\mathrm J
}
```

```math
\boxed{
a_0
=
5.29\times10^{-11}\,\mathrm m
=
0.529\,\text{Å}
}
```

```math
\boxed{
v_0
=
2.19\times10^6\,\mathrm{m/s}
}
```

```math
\boxed{
\mathrm{Ry}
=
13.606\,\mathrm{eV}
}
```

```math
\boxed{
R_\infty
=
1.09737\times10^7\,\mathrm{m^{-1}}
}
```

```math
\boxed{
\alpha
\approx
\frac{1}{137}
}
```

最实用的光子换算：

```math
\boxed{
hc
\approx
1240\,\mathrm{eV\cdot nm}
}
```

因此：

```math
\boxed{
E(\mathrm{eV})
=
\frac{1240}
{\lambda(\mathrm{nm})}
}
```

质量换算：

```math
1u
=
1.6605\times10^{-27}\,\mathrm{kg}
```

```math
\frac{m_p}{m_e}\approx1836
```

---

## 四十一、公式体系的记忆方法

从两个出发式开始：

```math
\frac{\mu v^2}{r}
=
\frac{Ze^2}
{4\pi\varepsilon_0r^2}
```

```math
\mu vr=n\hbar
```

可推出：

```math
r_n,\quad v_n
```

再由：

```math
E=K+U
```

以及：

```math
U=-2K
```

得到：

```math
E_n
```

最后使用：

```math
h\nu=\Delta E
```

得到里德伯公式。

完整推导链：

```math
\boxed{
\text{库仑向心力}
+
\text{角动量量子化}
\rightarrow
r_n,v_n,E_n
\rightarrow
h\nu=\Delta E
\rightarrow
\text{原子光谱}
}
```

---

## 四十二、常见失分点

1. 忘记能量公式中的 $Z^2$ ；
2. 把结合能写成负数；
3. 发射时把初、末能级顺序写反；
4. 把绝对值最大误认为能量最高；
5. 把线系限误认为末态趋于无穷；
6. 把最长、最短波长判断反；
7. 把类氢公式用于普通多电子原子；
8. 讨论同位素位移却忽略约化质量；
9. 把光子频率等同于轨道频率；
10. 认为弗兰克—赫兹实验证明了圆轨道。

---

## 四十三、通用做题流程

### 类型一：类氢轨道题

先确定：

```math
Z,\quad n,\quad \mu
```

再依次求：

```math
r_n
\rightarrow
v_n
\rightarrow
E_n
```

### 类型二：激发和电离

先写：

```math
E_n
=
-13.6\frac{Z^2}{n^2}\,\mathrm{eV}
```

再区分：

- 激发：两个束缚能级之差；
- 电离：从负能级到零；
- 结合能：能级绝对值。

### 类型三：光谱波长

确定：

```math
n_i,\quad n_f
```

再使用：

```math
\Delta E
\rightarrow
\lambda=\frac{hc}{\Delta E}
```

或里德伯公式。

### 类型四：线系范围

最长波长：

```math
n_i=n_f+1
```

最短波长：

```math
n_i\rightarrow\infty
```

### 类型五：同位素题

使用：

```math
R_M=R_\infty\frac{\mu}{m_e}
```

核越重：

```math
R\uparrow,
\quad
\nu\uparrow,
\quad
\lambda\downarrow
```

### 类型六：弗兰克—赫兹题

优先求相邻峰或谷的间隔：

```math
E_{\mathrm{exc}}(\mathrm{eV})
=
\Delta U(\mathrm V)
```

### 类型七：模型适用性

计算后比较相关尺度。例如：

```math
r_n\sim R_N
```

时，点核近似可能失效。

---

## 四十四、闭卷自测

1. 卢瑟福模型为什么导致原子坍塌？
2. 原子线光谱为什么暗示能级分立？
3. 普朗克能量子和爱因斯坦光量子有什么区别？
4. 玻尔三个基本假设是什么？
5. 为什么玻尔模型称为半经典理论？
6. 为什么能级能量是负值？
7. 为什么 $U=-2K$ 、 $E=-K$ ？
8. 为什么轨道半径正比于 $n^2/Z$ ？
9. 为什么能量正比于 $-Z^2/n^2$ ？
10. 结合能、激发能和电离能有什么区别？
11. 线系最长和最短波长对应什么跃迁？
12. 为什么氘的谱线比氢略短？
13. 弗兰克—赫兹实验为什么出现周期性电流极小？
14. 弗兰克—赫兹实验证明了什么，没有证明什么？
15. 碱金属为什么近似像氢，又为什么不完全像氢？
16. 什么是轨道贯穿和量子缺陷？
17. 为什么介子原子的轨道特别小？
18. 玻尔模型成功在哪里，根本缺陷又在哪里？

---

## 四十五、本章最终知识图像

本章最核心的思想是：

> 原子的能量不是连续的。原子只能处于一系列分立定态，光谱线来自定态之间的跃迁。

第一章得到原子的空间结构：

```math
\text{原子核}+\text{核外电子}
```

第二章进一步得到原子的能量结构：

```math
E_1,E_2,E_3,\ldots
```

实验中观测到的一条谱线，本质上是在测量：

```math
\boxed{
\text{两个原子能级之间的能量差}
}
```

完整因果链：

```math
\boxed{
\text{经典原子不稳定}
\rightarrow
\text{引入定态}
\rightarrow
\text{角动量量子化}
\rightarrow
\text{轨道和能量分立}
\rightarrow
\text{跃迁发射光子}
\rightarrow
\text{线状光谱}
}
```
