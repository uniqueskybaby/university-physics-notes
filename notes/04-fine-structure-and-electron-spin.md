# 第四章 原子的精细结构：电子自旋

根据课程课件，本章可以概括为：**一个假设、三个实验、两套量子数。**

- 一个假设：电子具有内禀自旋；
- 三个实验：史特恩—盖拉赫实验、碱金属双线、塞曼效应；
- 两套常用量子数： $n,l,m_l,m_s$ 与 $n,l,j,m_j$ 。

这些实验从“原子束怎样分裂”“无外场时谱线怎样分裂”“加磁场后谱线怎样分裂”三个角度，共同证明电子除轨道运动外还具有自旋自由度。

---

## 一、本章到底解决什么问题

### 1. 一句话概括

> **原子光谱为什么在高分辨率下出现细小分裂，以及外磁场为什么会使谱线进一步分裂？**

第二章和第三章中，我们主要考虑电子与原子核之间的静电相互作用。它能够解释：

- 原子具有分立能级；
- 原子发生能级跃迁时发出线状光谱；
- 碱金属原子的主要光谱结构。

但实验仪器精度提高后，人们发现原来的一条谱线往往不是一条，而是两条、三条甚至更多条。

这说明原来认为“能量只由 $n,l$ 决定”的模型还不够精细。

### 2. 本章核心因果链

```math
\text{静电相互作用给出粗能级}
```

```math
\downarrow
```

```math
\text{高分辨率光谱发现谱线双线或多线结构}
```

```math
\downarrow
```

```math
\text{史特恩—盖拉赫实验发现原子束出现偶数分裂}
```

```math
\downarrow
```

```math
\text{单靠整数轨道角动量无法解释}
```

```math
\downarrow
```

```math
\text{引入电子自旋 }s=\frac12
```

```math
\downarrow
```

```math
\mathbf J=\mathbf L+\mathbf S
```

```math
\downarrow
```

```math
\text{自旋—轨道相互作用使能级按 }j\text{ 分裂}
```

```math
\downarrow
```

```math
\text{外磁场使能级继续按 }m_j\text{ 分裂}
```

因此，本章最重要的层级关系是：

| 结构层次 | 主要相互作用 | 能级由什么量子数区分 |
|---|---|---|
| 粗结构 | 核—电子静电作用 | $n,l$ |
| 精细结构 | 自旋—轨道耦合及相对论效应 | $j$ |
| 塞曼分裂 | 原子磁矩与外磁场相互作用 | $m_j$ |

一定要形成下面这个图像：

```math
(n,l)
\quad\xrightarrow{\text{自旋轨道耦合}}\quad
(n,l,j)
\quad\xrightarrow{\text{外磁场}}\quad
(n,l,j,m_j)
```

---

## 二、电子轨道运动为什么会产生磁矩

### 1. 研究对象和物理图像

先暂时采用半经典图像：

- 电子带负电；
- 电子绕原子核做轨道运动；
- 运动电荷相当于电流；
- 电流环会产生磁矩。

所以：

> 电子绕核运动不仅具有轨道角动量，也相当于一个微小的电流环，因此具有轨道磁矩。

### 2. 从电流环推导轨道磁矩

设电子以速率 $v$ 在半径 $r$ 的圆轨道上运动。

电子运动一周的周期为

```math
T=\frac{2\pi r}{v}.
```

等效电流大小为

```math
I=\frac{-e}{T}
=-\frac{ev}{2\pi r}.
```

负号表示传统电流方向与电子运动方向相反。

电流环面积为

```math
S=\pi r^2.
```

电流环磁矩为

```math
\boldsymbol{\mu}_L=IS\mathbf n.
```

代入得到

```math
\boldsymbol{\mu}_L
=-\frac{ev}{2\pi r}\pi r^2\mathbf n
=-\frac{evr}{2}\mathbf n.
```

电子轨道角动量为

```math
\mathbf L=m_evr\mathbf n.
```

因此

```math
\boxed{
\boldsymbol{\mu}_L
=-\frac{e}{2m_e}\mathbf L
}
```

定义轨道旋磁比

```math
\gamma_L=\frac{e}{2m_e},
```

于是

```math
\boxed{
\boldsymbol{\mu}_L=-\gamma_L\mathbf L
}
```

### 3. 为什么磁矩与角动量方向相反

这是高频易错点。

- 角动量方向由电子的实际运动方向用右手定则确定；
- 磁矩方向由传统正电流方向确定；
- 电子带负电，所以传统电流方向与电子运动方向相反。

因此

```math
\boxed{
\boldsymbol{\mu}_L\text{ 与 }\mathbf L\text{ 反向}
}
```

注意：这里的负号不是“磁矩大小为负”，而是表示两个矢量方向相反。

---

## 三、玻尔磁子与轨道磁矩的量子化

### 1. 轨道角动量的量子力学结果

量子力学给出

```math
L=\sqrt{l(l+1)}\hbar,
```

```math
L_z=m_l\hbar,
```

其中

```math
l=0,1,2,\cdots,n-1,
```

```math
m_l=-l,-l+1,\cdots,l-1,l.
```

把它代入磁矩公式：

```math
\boldsymbol{\mu}_L
=-\frac{e}{2m_e}\mathbf L.
```

定义玻尔磁子

```math
\boxed{
\mu_B=\frac{e\hbar}{2m_e}
}
```

于是轨道磁矩的大小为

```math
\boxed{
\mu_L=\sqrt{l(l+1)}\,\mu_B
}
```

而在 $z$ 方向的分量为

```math
\boxed{
\mu_{L,z}=-m_l\mu_B
}
```

### 2. 为什么通常重点计算磁矩的投影

角动量大小是

```math
\sqrt{l(l+1)}\hbar,
```

但实验装置通常会选定一个特殊方向，例如外磁场方向 $z$ 。

原子在外磁场中的能量和受力主要取决于

```math
\mu_z,
```

而不是磁矩的总大小。

所以考试中看到：

- 能级在磁场中分裂；
- 史特恩—盖拉赫实验；
- 塞曼效应；

首先要想到的是：

```math
\boxed{\mu_z}
```

而不是单纯的 $\mu$ 。
、‘
### 3. 空间量子化

对于给定 $l$ ，有

```math
m_l=-l,-l+1,\cdots,l.
```

因此共有

```math
\boxed{2l+1}
```

个可能的空间取向。

例如 $l=1$ ：

```math
m_l=-1,0,+1,
```

所以有三个允许的投影：

```math
L_z=-\hbar,0,+\hbar.
```

这不是说角动量矢量只能真正静止在三个方向，而是说：

> 沿测量轴方向测量角动量时，只能得到三个分立结果。

---

## 四、均匀磁场和非均匀磁场有什么区别

### 1. 磁矩在均匀磁场中

磁矩在磁场中的势能为

```math
\boxed{
U=-\boldsymbol{\mu}\cdot\mathbf B
}
```

在均匀磁场中，它受到力矩

```math
\boldsymbol{\tau}
=\boldsymbol{\mu}\times\mathbf B.
```

这个力矩改变磁矩方向，使磁矩围绕磁场方向进动，但不会产生持续的平移合力。

所以：

> 均匀磁场可以使磁矩转向或进动，却不能把不同磁矩取向的原子束在空间上分开。

### 2. 磁矩在非均匀磁场中

力等于势能的负梯度：

```math
\mathbf F=-\nabla U.
```

若磁场主要沿 $z$ 方向变化，则

```math
U=-\mu_z B_z,
```

因此

```math
\boxed{
F_z=\mu_z\frac{\partial B_z}{\partial z}
}
```

于是：

- $\mu_z\gt 0$ 的原子向一个方向偏转；
- $\mu_z\lt 0$ 的原子向另一个方向偏转；
- 不同的分立 $\mu_z$ 对应不同的分立轨迹。

所以史特恩—盖拉赫实验必须使用非均匀磁场。

### 3. 拉莫尔进动

在均匀磁场中，

```math
\frac{d\mathbf L}{dt}
=\boldsymbol{\tau}
=\boldsymbol{\mu}\times\mathbf B.
```

由于

```math
\boldsymbol{\mu}=-\gamma\mathbf L,
```

可得到

```math
\frac{d\boldsymbol{\mu}}{dt}
=\boldsymbol{\omega}_L\times\boldsymbol{\mu},
```

其中

```math
\boxed{
\omega_L=\gamma B=\frac{eB}{2m_e}
}
```

称为拉莫尔角频率。

物理图像不是磁矩立即贴到磁场方向上，而是像陀螺一样绕磁场方向进动。

---

## 五、史特恩—盖拉赫实验

### 1. 实验解决什么问题

> 原子的角动量或磁矩在空间中的取向，是连续的还是分立的？

实验装置包括：

1. 高温炉产生原子束；
2. 狭缝将原子束准直；
3. 原子束通过强非均匀磁场；
4. 原子在屏幕或底片上形成沉积条纹。

### 2. 经典理论预言什么

如果原子磁矩相对于磁场方向可以取任意夹角 $\theta$ ，则

```math
\mu_z=\mu\cos\theta
```

可以连续变化。

于是

```math
F_z=\mu_z\frac{\partial B}{\partial z}
```

也连续变化。

屏幕上应该出现一条连续展宽的带，而不是几条清晰分开的线。

### 3. 量子理论预言什么

若磁矩投影量子化，则

```math
\mu_z
```

只能取若干分立值。

于是原子束应当分裂成若干条离散原子束。

实验确实观察到了离散分裂，证明了空间量子化。

### 4. 为什么“两束”是一个巨大的矛盾

若只考虑轨道角动量：

```math
m_l=-l,-l+1,\cdots,l,
```

取向数为

```math
2l+1.
```

因为 $l$ 是整数，所以 $2l+1$ 一定是奇数：

```math
1,3,5,7,\cdots
```

但实验对氢、银、钠等原子观察到两束。

两是偶数，无法写成整数 $l$ 对应的 $2l+1$ 。

因此必须引入一种半整数角动量。

这正是电子自旋假设的重要实验背景。

---

## 六、史特恩—盖拉赫实验的计算公式

设：

- 磁场区长度为 $d_1$ ；
- 磁场出口到屏幕距离为 $d_2$ ；
- 原子水平速率为 $v$ ；
- 原子质量为 $M$ ；
- 磁场梯度为 $\partial B/\partial z$ 。

原子在磁场中的加速度为

```math
a_z=\frac{F_z}{M}
=\frac{\mu_z}{M}\frac{\partial B}{\partial z}.
```

在磁场内运动时间

```math
t_1=\frac{d_1}{v}.
```

磁场内偏转

```math
z_1=\frac12a_zt_1^2.
```

离开磁场时的竖直速度

```math
v_z=a_zt_1.
```

离开磁场后飞行时间

```math
t_2=\frac{d_2}{v}.
```

自由飞行偏转

```math
z_2'=v_zt_2.
```

总偏转量

```math
z=z_1+z_2'.
```

整理得

```math
\boxed{
z=
\frac{\mu_z}{Mv^2}
\frac{\partial B}{\partial z}
d_1
\left(\frac{d_1}{2}+d_2\right)
}
```

这是史特恩—盖拉赫数值题最实用的公式。

### 例题1：银原子的史特恩—盖拉赫实验

题目给出：

```math
\frac{\partial B}{\partial z}=10^3\ \mathrm{T/m},
```

```math
d_1=0.04\ \mathrm m,
\qquad
d_2=0.10\ \mathrm m,
```

```math
v=500\ \mathrm{m/s},
```

屏幕上两束间距为

```math
\Delta z=0.002\ \mathrm m,
```

银原子质量为

```math
107.90u.
```

#### 第一步：注意“间距”和“单束偏转”的区别

两束关于中心对称，因此每束偏离中线的距离为

```math
z=\frac{\Delta z}{2}
=0.001\ \mathrm m.
```

#### 第二步：银原子的质量

```math
M=107.90\times1.66054\times10^{-27}
\approx1.792\times10^{-25}\ \mathrm{kg}.
```

#### 第三步：代入偏转公式

```math
\mu_z=
\frac{zMv^2}
{
\dfrac{\partial B}{\partial z}
d_1
\left(\dfrac{d_1}{2}+d_2\right)
}.
```

代入：

```math
\mu_z
=
\frac{
0.001
\times1.792\times10^{-25}
\times500^2
}{
10^3\times0.04\times(0.02+0.10)
}.
```

得到

```math
\boxed{
|\mu_z|
\approx9.33\times10^{-24}\ \mathrm{J/T}
}
```

而

```math
\mu_B=9.274\times10^{-24}\ \mathrm{J/T},
```

所以

```math
\boxed{
|\mu_z|\approx1.01\mu_B\approx\mu_B
}
```

#### 物理解释

银原子最外层未配对电子处于 $s$ 态：

```math
l=0,\qquad j=\frac12,\qquad g_j\approx2.
```

因此

```math
\mu_{J,z}=-m_jg_j\mu_B,
```

当

```math
m_j=\pm\frac12
```

时，

```math
\mu_{J,z}=\mp\mu_B.
```

所以原子束正好分成两束。

#### 本题易错点

1. 把两束间距 $0.002\,\mathrm m$ 直接当成单束偏转；
2. 忘记把原子质量单位 $u$ 换成千克；
3. 用均匀磁场 $B$ ，而不是磁场梯度 $\partial B/\partial z$ ；
4. 忽略磁场后的自由飞行偏转。

---

## 七、电子自旋假设

### 1. 为什么必须引入自旋

轨道角动量量子数只能是整数：

```math
l=0,1,2,\cdots
```

所以空间取向数 $2l+1$ 永远是奇数。

为了得到两个取向，需要一个满足

```math
2s+1=2
```

的量子数，因此

```math
\boxed{
s=\frac12
}
```

1925年，乌仑贝克和古兹米特提出电子具有一种固有角动量，即电子自旋。

### 2. 自旋不是电子真的在“自转”

这是必须纠正的错误理解。

错误理解：

> 电子是一个小球，在绕自身轴线高速旋转。

正确理解：

> 自旋是电子的内禀量子属性，是电子本身固有的角动量自由度，在经典力学中没有完全对应物。

若把电子当成有半径的小球并用经典自转解释自旋，为产生实验所需角动量，其表面速度会遇到严重的相对论问题。

所以“自旋”只是历史名称，不应按宏观小球自转理解。

### 3. 自旋角动量

任意电子都有

```math
\boxed{
s=\frac12
}
```

自旋角动量大小为

```math
S=\sqrt{s(s+1)}\hbar
=\sqrt{\frac12\left(\frac12+1\right)}\hbar
```

所以

```math
\boxed{
S=\frac{\sqrt3}{2}\hbar
}
```

自旋角动量沿 $z$ 方向的投影为

```math
S_z=m_s\hbar,
```

其中

```math
\boxed{
m_s=\pm\frac12
}
```

于是

```math
\boxed{
S_z=\pm\frac{\hbar}{2}
}
```

注意：

```math
S\neq\frac{\hbar}{2}.
```

$\hbar/2$ 是投影的绝对值，而不是自旋角动量大小。

---

## 八、自旋磁矩和 $g$ 因子

### 1. 为什么简单类比会失败

轨道磁矩满足

```math
\boldsymbol{\mu}_L
=-\mu_B\frac{\mathbf L}{\hbar}.
```

若机械地类比，自旋磁矩似乎应为

```math
\boldsymbol{\mu}_S
=-\mu_B\frac{\mathbf S}{\hbar}.
```

但实验发现，自旋磁矩大约是这一结果的两倍。

因此必须写成

```math
\boxed{
\boldsymbol{\mu}_S
=-g_s\mu_B\frac{\mathbf S}{\hbar}
}
```

其中

```math
\boxed{
g_s\approx2
}
```

更精确地说，电子自由自旋的 $g_s$ 略大于2，但本课程通常取2。

### 2. 自旋磁矩大小与投影

自旋磁矩大小为

```math
\mu_S
=g_s\sqrt{s(s+1)}\mu_B.
```

取 $s=1/2$ 、 $g_s=2$ ：

```math
\mu_S
=2\sqrt{\frac34}\mu_B
=\sqrt3\,\mu_B.
```

所以

```math
\boxed{
\mu_S=\sqrt3\,\mu_B
}
```

其 $z$ 分量为

```math
\mu_{S,z}
=-g_sm_s\mu_B.
```

因为

```math
m_s=\pm\frac12,
```

所以

```math
\boxed{
\mu_{S,z}=\mp\mu_B
}
```

再次注意：自旋方向与磁矩方向相反，因为电子带负电。

---

## 九、轨道角动量和自旋角动量怎样合成

电子同时具有：

- 轨道角动量 $\mathbf L$ ；
- 自旋角动量 $\mathbf S$ 。

它们合成为总角动量

```math
\boxed{
\mathbf J=\mathbf L+\mathbf S
}
```

### 1. 总角动量量子数 $j$

角动量合成规则为

```math
j=l+s,l+s-1,\cdots,|l-s|.
```

对单电子

```math
s=\frac12,
```

因此通常有

```math
\boxed{
j=l+\frac12,\quad l-\frac12
}
```

但当 $l=0$ 时，只有

```math
j=\frac12.
```

例如：

| 电子状态 | $l$ | 允许的 $j$ |
|---|---:|---|
| $s$ 电子 | 0 | $1/2$ |
| $p$ 电子 | 1 | $1/2,3/2$ |
| $d$ 电子 | 2 | $3/2,5/2$ |
| $f$ 电子 | 3 | $5/2,7/2$ |

### 2. 总角动量大小和投影

```math
\boxed{
J=\sqrt{j(j+1)}\hbar
}
```

```math
\boxed{
J_z=m_j\hbar
}
```

其中

```math
m_j=-j,-j+1,\cdots,j-1,j.
```

因此一个 $j$ 能级共有

```math
\boxed{
2j+1
}
```

个磁子能级。

例如 $j=3/2$ ：

```math
m_j=-\frac32,-\frac12,+\frac12,+\frac32,
```

共有4个取向。

---

## 十、朗德 $g$ 因子

### 1. 为什么总磁矩不简单等于某个固定倍数的 $\mathbf J$

轨道磁矩与轨道角动量的比例因子是

```math
g_L=1.
```

自旋磁矩与自旋角动量的比例因子约为

```math
g_S=2.
```

因为二者比例不同，所以：

```math
\boldsymbol{\mu}_L+\boldsymbol{\mu}_S
```

一般不严格平行于

```math
\mathbf L+\mathbf S=\mathbf J.
```

但 $\mathbf L$ 和 $\mathbf S$ 会围绕 $\mathbf J$ 进动。垂直于 $\mathbf J$ 的磁矩分量在时间平均后相互抵消，对外有效的是沿 $\mathbf J$ 方向的平均分量。

于是定义有效总磁矩：

```math
\boxed{
\boldsymbol{\mu}_J
=-g_J\mu_B\frac{\mathbf J}{\hbar}
}
```

### 2. 朗德因子公式

```math
\boxed{
g_J
=
1+
\frac{
J(J+1)+S(S+1)-L(L+1)
}{
2J(J+1)
}
}
```

等价地写成

```math
\boxed{
g_J
=
\frac32+
\frac{
S(S+1)-L(L+1)
}{
2J(J+1)
}
}
```

单电子时可将大写 $L,S,J$ 换成小写 $l,s,j$ 。

总磁矩大小为

```math
\boxed{
\mu_J=g_J\sqrt{J(J+1)}\mu_B
}
```

其磁场方向投影为

```math
\boxed{
\mu_{J,z}=-g_Jm_J\mu_B
}
```

### 3. 三个必须熟记的特殊情况

#### 纯轨道角动量： $S=0$

此时

```math
J=L,
```

所以

```math
\boxed{g_J=1}
```

对应正常塞曼效应。

#### 纯自旋角动量： $L=0$

此时

```math
J=S,
```

所以

```math
\boxed{g_J=2}
```

#### 单电子 $P$ 态

```math
L=1,\qquad S=\frac12.
```

对于

```math
{}^2P_{1/2},
```

```math
\boxed{g_J=\frac23}
```

对于

```math
{}^2P_{3/2},
```

```math
\boxed{g_J=\frac43}
```

这两个数在钠双线塞曼效应中会反复出现。

---

## 十一、原子态符号怎样写

原子态通常写成

```math
\boxed{
n^{2S+1}L_J
}
```

其中：

- $n$ ：主量子数；
- $2S+1$ ：多重度；
- $L$ ：总轨道角动量量子数对应的字母；
- $J$ ：总角动量量子数。

字母对应关系：

| $L$ | 0 | 1 | 2 | 3 | 4 |
|---:|---|---|---|---|---|
| 符号 | S | P | D | F | G |

不要把态符号中的大写 S 与自旋量子数 $S$ 混淆。态符号中的字母 S 表示 $L=0$ 。

### 例题2：写出氢原子若干状态的原子态符号

#### $1s$

```math
n=1,\quad l=0,\quad s=\frac12,\quad j=\frac12.
```

所以

```math
\boxed{
1^2S_{1/2}
}
```

#### $2p$

```math
n=2,\quad l=1,\quad s=\frac12.
```

因此

```math
j=\frac12,\frac32.
```

所以

```math
\boxed{
2^2P_{1/2},\quad2^2P_{3/2}
}
```

#### $3d$

```math
l=2,
\qquad
j=\frac32,\frac52.
```

所以

```math
\boxed{
3^2D_{3/2},\quad3^2D_{5/2}
}
```

#### $4f$

```math
l=3,
\qquad
j=\frac52,\frac72.
```

所以

```math
\boxed{
4^2F_{5/2},\quad4^2F_{7/2}
}
```

### 例题3：一个 $d$ 电子的量子数和 $g$ 因子

对于 $d$ 电子：

```math
l=2,\qquad s=\frac12.
```

允许的总角动量为

```math
j=\frac52,\frac32.
```

所以原子态为

```math
{}^2D_{5/2},\qquad{}^2D_{3/2}.
```

#### 对 ${}^2D_{5/2}$

```math
g_J
=
1+
\frac{
\frac52\frac72+\frac12\frac32-2\times3
}{
2\times\frac52\times\frac72
}
```

得到

```math
\boxed{
g_{5/2}=\frac65
}
```

#### 对 ${}^2D_{3/2}$

同理得到

```math
\boxed{
g_{3/2}=\frac45
}
```

如果置于弱磁场中：

- ${}^2D_{5/2}$ 分裂成 $2J+1=6$ 层；
- ${}^2D_{3/2}$ 分裂成 $2J+1=4$ 层。

---

## 十二、自旋—轨道相互作用

### 1. 它解决什么问题

> 为什么同一个 $n,l$ 能级会因为 $j$ 不同而分裂？

例如一个 $p$ 电子：

```math
l=1,\qquad s=\frac12,
```

可能形成

```math
j=\frac12,\frac32.
```

实验发现这两个状态的能量略有不同。

这意味着电子的自旋状态和轨道运动不是完全独立的。

### 2. 物理图像

在电子的参考系中，可以把原子核看成绕电子运动的正电荷。

运动电荷产生磁场，这个磁场会与电子自旋磁矩相互作用。

因此产生附加能量：

```math
U=-\boldsymbol{\mu}_S\cdot\mathbf B_{\text{轨道}}.
```

经过相对论修正和托马斯进动修正后，自旋—轨道相互作用可写成

```math
\boxed{
H_{SO}=\xi(r)\mathbf L\cdot\mathbf S
}
```

对于中心势

```math
\boxed{
\xi(r)=
\frac{1}{2m_e^2c^2r}
\frac{dV}{dr}
}
```

对于库仑势

```math
V(r)=-\frac{Ze^2}{4\pi\varepsilon_0r},
```

有

```math
\xi(r)\gt 0.
```

### 3. 怎样计算 $\mathbf L\cdot\mathbf S$

由

```math
\mathbf J=\mathbf L+\mathbf S
```

可得

```math
\mathbf J^2
=
\mathbf L^2+\mathbf S^2
+2\mathbf L\cdot\mathbf S.
```

所以

```math
\boxed{
\mathbf L\cdot\mathbf S
=
\frac12
\left(
\mathbf J^2-\mathbf L^2-\mathbf S^2
\right)
}
```

在量子态中取本征值：

```math
\boxed{
\langle\mathbf L\cdot\mathbf S\rangle
=
\frac{\hbar^2}{2}
\left[
j(j+1)-l(l+1)-s(s+1)
\right]
}
```

因此自旋—轨道附加能量为

```math
\boxed{
\Delta E_{SO}
=
\frac{\xi}{2}\hbar^2
\left[
j(j+1)-l(l+1)-s(s+1)
\right]
}
```

### 4. 对单电子 $s=1/2$ 的两个状态

#### 当

```math
j=l+\frac12
```

时，

```math
\boxed{
\langle\mathbf L\cdot\mathbf S\rangle
=\frac{l}{2}\hbar^2
}
```

轨道和自旋较趋于同向，附加能量较高。

#### 当

```math
j=l-\frac12
```

时，

```math
\boxed{
\langle\mathbf L\cdot\mathbf S\rangle
=-\frac{l+1}{2}\hbar^2
}
```

轨道和自旋较趋于反向，附加能量较低。

所以在通常的库仑中心势近似下：

```math
\boxed{
j=l-\frac12\text{ 的能级较低，}
\quad
j=l+\frac12\text{ 的能级较高}
}
```

### 5. 类氢近似下的分裂公式

课程中使用的双线分裂近似可写为

```math
\boxed{
\Delta E_{nl}
=
\frac{
(\alpha Z^*)^4m_ec^2
}{
2n^3l(l+1)
}
}
\qquad(l\neq0)
```

其中：

- $\alpha$ 为精细结构常数；
- $Z^*$ 为有效核电荷；
- $m_ec^2$ 为电子静止能量。

### 6. 必须掌握的比例关系

```math
\boxed{
\Delta E_{SO}\propto
\frac{(Z^*)^4}{n^3l(l+1)}
}
```

因此：

#### 固定 $l,Z^*$

```math
n\uparrow
\quad\Rightarrow\quad
\Delta E\downarrow
```

即

```math
\Delta E_{2p}\gt{}
\Delta E_{3p}\gt{}
\Delta E_{4p}.
```

#### 固定 $n,Z^*$

```math
l\uparrow
\quad\Rightarrow\quad
\Delta E\downarrow
```

即

```math
\Delta E_{4p}\gt{}
\Delta E_{4d}\gt{}
\Delta E_{4f}.
```

#### 固定 $n,l$

```math
Z^*\uparrow
\quad\Rightarrow\quad
\Delta E\text{ 急剧增大}
```

因为是四次方关系。

### 7. 为什么 $S$ 能级不形成这种双线

对 $s$ 电子：

```math
l=0.
```

只有

```math
j=\frac12.
```

不存在

```math
l+\frac12
\quad\text{和}\quad
l-\frac12
```

两个不同状态，所以在本章采用的自旋—轨道双线模型中：

```math
\boxed{
S\text{ 能级不分裂成双层}
}
```

更严格的氢原子精细结构还包括相对论动能修正和达尔文项，但本章考试通常以自旋—轨道耦合模型为主。

---

## 十三、碱金属双线

### 1. 为什么碱金属可以近似为单电子体系

碱金属原子具有：

- 一个封闭的原子实；
- 一个最外层价电子。

封闭原子实的总轨道角动量和总自旋通常相互抵消，因此主要由最外层价电子决定原子的光谱和磁矩。

所以可以近似用单电子量子数

```math
n,l,j,m_j
```

描述整个原子。

### 2. 碱金属四个主要线系

设最低 $S$ 、 $P$ 、 $D$ 态分别作为终态，则：

| 线系 | 跃迁形式 |
|---|---|
| 主线系 | $nP\rightarrow n_0S$ |
| 锐线系 | $nS\rightarrow n_0P$ |
| 漫线系 | $nD\rightarrow n_0P$ |
| 基线系 | $nF\rightarrow n_0D$ |

基本电偶极跃迁选择定则为

```math
\boxed{
\Delta l=\pm1
}
```

考虑自旋—轨道耦合后，还必须满足

```math
\boxed{
\Delta j=0,\pm1
}
```

但

```math
\boxed{
j=0\not\leftrightarrow j'=0
}
```

### 3. 主线系为什么是双线

主线系：

```math
nP\rightarrow n_0S.
```

$P$ 能级有

```math
{}^2P_{1/2},\qquad{}^2P_{3/2}
```

两个精细结构能级。

而 $S$ 能级只有

```math
{}^2S_{1/2}.
```

因此有两个允许跃迁：

```math
{}^2P_{1/2}\rightarrow{}^2S_{1/2},
```

```math
{}^2P_{3/2}\rightarrow{}^2S_{1/2}.
```

所以每条主线分裂成两条。

随着初态主量子数 $n$ 增大，

```math
\Delta E_{nP}\propto\frac1{n^3}
```

逐渐减小，所以主线系双线间距逐渐减小，最后在线系限合并。

### 4. 锐线系为什么也是双线，而且间距近似不变

锐线系：

```math
nS\rightarrow n_0P.
```

初态 $nS$ 不形成双层，而固定的终态 $n_0P$ 分裂为

```math
{}^2P_{1/2},\qquad{}^2P_{3/2}.
```

因此形成两条谱线。

由于终态始终是同一个最低 $P$ 能级，其裂距固定，所以锐线系双线间隔基本不随 $n$ 改变。

### 5. 漫线系为什么通常有三条

漫线系：

```math
nD\rightarrow n_0P.
```

初态有

```math
{}^2D_{3/2},\qquad{}^2D_{5/2}.
```

末态有

```math
{}^2P_{1/2},\qquad{}^2P_{3/2}.
```

表面上有四种组合，但选择定则要求

```math
\Delta j=0,\pm1.
```

其中

```math
{}^2D_{5/2}\rightarrow{}^2P_{1/2}
```

有

```math
\Delta j=-2,
```

所以禁戒。

剩下三条允许跃迁：

```math
{}^2D_{3/2}\rightarrow{}^2P_{1/2},
```

```math
{}^2D_{3/2}\rightarrow{}^2P_{3/2},
```

```math
{}^2D_{5/2}\rightarrow{}^2P_{3/2}.
```

因此漫线系常表现为三条精细结构分线。

这类“先列全部组合，再用选择定则删除禁戒跃迁”的方法非常重要。

---

## 十四、塞曼效应

### 1. 塞曼效应研究什么

> 把发光原子置于外磁场中，原来的光谱线为什么会进一步分裂？

史特恩—盖拉赫实验研究的是：

```math
\text{原子束在非均匀磁场中的空间分裂}
```

塞曼效应研究的是：

```math
\text{光源在磁场中的光谱分裂}
```

两者不能混淆。

### 2. 外磁场中的能量

原子磁矩与磁场相互作用能为

```math
U=-\boldsymbol{\mu}\cdot\mathbf B.
```

取磁场方向为 $z$ 轴：

```math
U=-\mu_zB.
```

又因为

```math
\mu_z=-g_Jm_J\mu_B,
```

所以

```math
\boxed{
\Delta E_B=g_Jm_J\mu_BB
}
```

于是原能级 $E_0$ 变为

```math
\boxed{
E'=E_0+g_Jm_J\mu_BB
}
```

一个总角动量为 $J$ 的能级分裂成

```math
\boxed{
2J+1
}
```

个磁子能级。

### 3. 跃迁谱线的频率移动

设上能级和下能级的磁量子数、朗德因子分别为

```math
m_u,g_u
```

和

```math
m_l,g_l.
```

无磁场时：

```math
h\nu_0=E_u-E_l.
```

有磁场时：

```math
h\nu'
=
(E_u+g_um_u\mu_BB)
-
(E_l+g_lm_l\mu_BB).
```

因此

```math
\boxed{
\nu'
=
\nu_0+
\frac{\mu_BB}{h}
(g_um_u-g_lm_l)
}
```

波数差为

```math
\boxed{
\Delta\widetilde{\nu}
=
\frac{\mu_BB}{hc}
(g_um_u-g_lm_l)
}
```

这是塞曼效应所有计算的总公式。

### 4. 塞曼跃迁的选择定则

弱磁场中：

```math
\boxed{
\Delta n=\text{任意}
}
```

```math
\boxed{
\Delta l=\pm1
}
```

```math
\boxed{
\Delta j=0,\pm1
}
```

```math
\boxed{
\Delta m_j=0,\pm1
}
```

其中

```math
j=0\not\leftrightarrow j'=0.
```

---

## 十五、正常塞曼效应

### 1. 发生条件

当原子态总自旋为零：

```math
S=0,
```

则

```math
J=L
```

并且

```math
g_J=1.
```

上下能级都有同样的 $g=1$ ，所以频率移动变为

```math
\Delta\nu
=
\frac{\mu_BB}{h}
(m_u-m_l).
```

根据

```math
\Delta m=0,\pm1,
```

只有三种不同频率：

```math
\boxed{
\nu_0-\nu_L,\quad
\nu_0,\quad
\nu_0+\nu_L
}
```

其中

```math
\boxed{
\nu_L=\frac{\mu_BB}{h}
=\frac{eB}{4\pi m_e}
}
```

称为洛伦兹频率或一个洛伦兹单位。

因此：

```math
\boxed{
正常塞曼效应：一条谱线等间隔分裂成三条
}
```

### 例题4： ${}^1D_2\rightarrow{}^1P_1$ 的正常塞曼效应

题目给出氢原子某条

```math
{}^1D_2\rightarrow{}^1P_1
```

跃迁，波长为 $6678\,\text{\AA}$ ，要求画出塞曼分裂并标出 $\pi$ 、 $\sigma$ 线。

#### 第一步：判断是否正常塞曼效应

两个原子态的多重度均为1：

```math
2S+1=1
```

所以

```math
S=0.
```

因此

```math
g_u=g_l=1.
```

这是正常塞曼效应。

#### 第二步：上、下能级分裂

上能级：

```math
{}^1D_2,\qquad J_u=2,
```

所以

```math
m_u=-2,-1,0,1,2.
```

下能级：

```math
{}^1P_1,\qquad J_l=1,
```

所以

```math
m_l=-1,0,1.
```

#### 第三步：选择定则

```math
\Delta m=m_u-m_l=0,\pm1.
```

虽然可以画出9条允许跃迁箭头，但具有相同 $\Delta m$ 的跃迁频率相同。

因此所有跃迁合并成三条谱线：

```math
\boxed{
\Delta m=-1,\ 0,\ +1
}
```

即以洛伦兹单位表示：

```math
\boxed{
-1,\quad0,\quad+1
}
```

最终只有三种频率：

```math
\nu_0-\nu_L,\quad\nu_0,\quad\nu_0+\nu_L.
```

核心不是数箭头，而是数不同的

```math
g_um_u-g_lm_l.
```

---

## 十六、反常塞曼效应

### 1. 为什么叫“反常”

如果电子总自旋不为零：

```math
S\neq0,
```

则通常

```math
g_J\neq1.
```

上下能级的 $g$ 因子也可能不同。

频率移动为

```math
\Delta\nu
=
\frac{\mu_BB}{h}
(g_um_u-g_lm_l).
```

这时：

- 分裂不一定只有三条；
- 相邻谱线间距不一定相同；
- 分裂结构可能非常复杂。

历史上在电子自旋被认识之前无法解释，所以被称为“反常”塞曼效应。

实际上，它才是更普遍的情况。

---

## 十七、钠黄双线在 $1\,\mathrm T$ 磁场中的分裂

作业给出的钠原子 $3P\rightarrow3S$ 双线波长为

```math
589.593\ \mathrm{nm}
```

和

```math
588.996\ \mathrm{nm}.
```

要求分析在 $1\,\mathrm T$ 外磁场中的能级与谱线分裂。

### 1. 无磁场时的两个跃迁

较长波长对应较小光子能量：

```math
589.593\ \mathrm{nm}:
\quad
3^2P_{1/2}\rightarrow3^2S_{1/2}.
```

较短波长对应较大光子能量：

```math
588.996\ \mathrm{nm}:
\quad
3^2P_{3/2}\rightarrow3^2S_{1/2}.
```

对应 $g$ 因子：

```math
\boxed{
g(3^2S_{1/2})=2
}
```

```math
\boxed{
g(3^2P_{1/2})=\frac23
}
```

```math
\boxed{
g(3^2P_{3/2})=\frac43
}
```

### 2. 一个玻尔磁子在 $1\,\mathrm T$ 中对应的能量

```math
\mu_BB
=
5.788\times10^{-5}\ \mathrm{eV}.
```

对应波数单位为

```math
\frac{\mu_BB}{hc}
=
0.46686\ \mathrm{cm^{-1}}.
```

这个数非常适合考试快速计算：

```math
\boxed{
1\,\mathrm T
\quad\Rightarrow\quad
1\mu_BB=0.46686\ \mathrm{cm^{-1}}
}
```

### 3. 各能级的磁场分裂

#### $3^2S_{1/2}$

```math
m_j=\pm\frac12,
\qquad
g=2.
```

因此

```math
gm_j=\pm1.
```

能量移动为

```math
\boxed{
\Delta E=\pm\mu_BB
}
```

即

```math
\boxed{
\pm5.788\times10^{-5}\ \mathrm{eV}
}
```

#### $3^2P_{1/2}$

```math
m_j=\pm\frac12,
\qquad
g=\frac23.
```

所以

```math
gm_j=\pm\frac13.
```

能量移动为

```math
\boxed{
\Delta E=\pm\frac13\mu_BB
}
```

即

```math
\boxed{
\pm1.929\times10^{-5}\ \mathrm{eV}
}
```

#### $3^2P_{3/2}$

```math
m_j=\pm\frac32,\pm\frac12,
\qquad
g=\frac43.
```

所以

```math
gm_j=
\pm2,\quad\pm\frac23.
```

能量移动为

```math
\boxed{
\Delta E=
\pm2\mu_BB,\quad
\pm\frac23\mu_BB
}
```

### 4. $3^2P_{1/2}\rightarrow3^2S_{1/2}$ 的四条谱线

用

```math
q=g_um_u-g_lm_l
```

表示以 $\mu_BB$ 为单位的频率移动。

| 上态 $m_u$ | 下态 $m_l$ | $\Delta m$ | $q$ |
|---:|---:|---:|---:|
| $+1/2$ | $+1/2$ | 0 | $-2/3$ |
| $-1/2$ | $-1/2$ | 0 | $+2/3$ |
| $+1/2$ | $-1/2$ | $+1$ | $+4/3$ |
| $-1/2$ | $+1/2$ | $-1$ | $-4/3$ |

所以波数差为

```math
\boxed{
\Delta\widetilde{\nu}
=
\pm\frac23(0.46686),
\quad
\pm\frac43(0.46686)
}
```

即

```math
\boxed{
\Delta\widetilde{\nu}
=
\pm0.31124\ \mathrm{cm^{-1}},
\quad
\pm0.62249\ \mathrm{cm^{-1}}
}
```

因此这条钠线分裂成四条。

### 5. $3^2P_{3/2}\rightarrow3^2S_{1/2}$ 的六条谱线

允许跃迁对应的 $q$ 值为

```math
q=
\pm\frac13,\quad
\pm1,\quad
\pm\frac53.
```

所以波数差为

```math
\boxed{
\Delta\widetilde{\nu}
=
\pm0.15562,
\quad
\pm0.46686,
\quad
\pm0.77811
\ \mathrm{cm^{-1}}
}
```

因此这条钠线分裂成六条。

### 6. 如何判断仍然属于弱场塞曼效应

钠双线本身的波数间隔为

```math
\frac1{588.996\,\mathrm{nm}}
-
\frac1{589.593\,\mathrm{nm}}
\approx17.19\ \mathrm{cm^{-1}}.
```

而 $1\,\mathrm T$ 下的磁场分裂不到 $1\,\mathrm{cm^{-1}}$ 。

所以

```math
\mu_BB\ll\Delta E_{SO}.
```

自旋—轨道耦合仍然比外磁场作用强， $j,m_j$ 仍是好量子数，属于弱场反常塞曼效应。

---

## 十八、塞曼谱线的偏振

### 1. 三类跃迁

#### $\pi$ 线

```math
\boxed{
\Delta m=0
}
```

#### $\sigma^+$ 线

```math
\boxed{
\Delta m=+1
}
```

#### $\sigma^-$ 线

```math
\boxed{
\Delta m=-1
}
```

### 2. 垂直于磁场方向观察

若观察方向垂直于 $\mathbf B$ ：

- $\pi$ 线为线偏振光，电矢量平行于 $\mathbf B$ ；
- $\sigma^\pm$ 线也表现为线偏振光，电矢量垂直于 $\mathbf B$ 。

所以：

```math
\boxed{
\pi:\ \mathbf E\parallel\mathbf B
}
```

```math
\boxed{
\sigma:\ \mathbf E\perp\mathbf B
}
```

### 3. 沿磁场方向观察

若观察方向平行于 $\mathbf B$ ：

- $\pi$ 线观察不到；
- $\sigma^+$ 、 $\sigma^-$ 为旋向相反的圆偏振光。

圆偏振究竟称为左旋还是右旋，与观察方向及教材采用的符号约定有关。考试时应先写清楚“沿 $+\mathbf B$ 方向观察”还是“迎着磁场方向观察”，不要只凭记忆写左右旋。

---

## 十九、帕邢—巴克效应

### 1. 什么时候弱场模型失效

弱磁场中：

```math
H_{SO}\gg H_B,
```

先有

```math
\mathbf J=\mathbf L+\mathbf S,
```

然后 $\mathbf J$ 与磁场作用。

但磁场非常强时：

```math
H_B\gg H_{SO}.
```

外磁场分别强迫 $\mathbf L$ 和 $\mathbf S$ 绕磁场进动，自旋和轨道不再紧密耦合成稳定的 $\mathbf J$ 。

这就是帕邢—巴克效应。

### 2. 强场中的能量

强场中使用

```math
m_l,\quad m_s
```

描述状态，而不再优先使用 $j,m_j$ 。

磁场附加能量近似为

```math
\boxed{
\Delta E
=
\mu_BB(m_l+g_sm_s)
}
```

取

```math
g_s\approx2,
```

得到

```math
\boxed{
\Delta E
=
\mu_BB(m_l+2m_s)
}
```

### 3. 强场选择定则

```math
\boxed{
\Delta m_s=0
}
```

```math
\boxed{
\Delta m_l=0,\pm1
}
```

因为跃迁中自旋取向不改变，所以频率差只取决于 $\Delta m_l$ 。

最终复杂的反常塞曼结构又趋向三组分裂，这就是：

```math
\boxed{
反常塞曼效应在强场下重新趋向正常三重分裂
}
```

但物理机制与真正的 $S=0$ 正常塞曼效应并不完全相同。

---

## 二十、三个重要实验怎样区分

| 实验 | 研究对象 | 是否需要外磁场 | 磁场要求 | 观测结果 | 主要证明 |
|---|---|---|---|---|---|
| 史特恩—盖拉赫 | 原子束 | 是 | 非均匀磁场 | 原子束空间分裂 | 空间量子化、自旋 |
| 碱金属双线 | 原子光谱 | 不需要 | 无外场 | 一条谱线出现双线等精细结构 | 自旋—轨道耦合 |
| 塞曼效应 | 原子光谱 | 是 | 通常均匀磁场 | 谱线进一步多重分裂 | 原子磁矩、 $g$ 因子、自旋 |

记忆方法：

> **原子束分开看史盖；无场双线看精细；加场谱线看塞曼。**

---

## 二十一、本章公式卡

### A级：必须直接默写

#### 1. 玻尔磁子

```math
\boxed{
\mu_B=\frac{e\hbar}{2m_e}
}
```

#### 2. 轨道磁矩

```math
\boxed{
\boldsymbol{\mu}_L
=-\mu_B\frac{\mathbf L}{\hbar}
}
```

```math
\boxed{
\mu_{L,z}=-m_l\mu_B
}
```

#### 3. 自旋角动量

```math
\boxed{
s=\frac12,\qquad
m_s=\pm\frac12
}
```

#### 4. 自旋磁矩

```math
\boxed{
\boldsymbol{\mu}_S
=-g_s\mu_B\frac{\mathbf S}{\hbar},
\qquad g_s\approx2
}
```

#### 5. 总角动量

```math
\boxed{
\mathbf J=\mathbf L+\mathbf S
}
```

```math
\boxed{
j=l\pm\frac12
}
```

```math
\boxed{
m_j=-j,-j+1,\cdots,j
}
```

#### 6. 朗德因子

```math
\boxed{
g_J
=
1+
\frac{
J(J+1)+S(S+1)-L(L+1)
}{
2J(J+1)
}
}
```

#### 7. 总磁矩投影

```math
\boxed{
\mu_{J,z}=-g_Jm_J\mu_B
}
```

#### 8. 外磁场能级移动

```math
\boxed{
\Delta E_B=g_Jm_J\mu_BB
}
```

#### 9. 谱线频率移动

```math
\boxed{
\Delta\nu
=
\frac{\mu_BB}{h}
(g_um_u-g_lm_l)
}
```

#### 10. 选择定则

```math
\boxed{
\Delta l=\pm1
}
```

```math
\boxed{
\Delta j=0,\pm1
}
```

```math
\boxed{
\Delta m_j=0,\pm1
}
```

### B级：必须理解并会使用

#### 史特恩—盖拉赫受力

```math
\boxed{
F_z=\mu_z\frac{\partial B}{\partial z}
}
```

#### 自旋—轨道耦合

```math
\boxed{
H_{SO}=\xi(r)\mathbf L\cdot\mathbf S
}
```

#### 角动量点积

```math
\boxed{
\mathbf L\cdot\mathbf S
=
\frac12
\left(
\mathbf J^2-\mathbf L^2-\mathbf S^2
\right)
}
```

#### 精细结构比例

```math
\boxed{
\Delta E_{SO}
\propto
\frac{(Z^*)^4}{n^3l(l+1)}
}
```

#### 强场帕邢—巴克效应

```math
\boxed{
\Delta E
=
\mu_BB(m_l+2m_s)
}
```

### C级：理解来源即可

- 轨道磁矩从等效电流环推导；
- 拉莫尔进动公式；
- 朗德因子从磁矩在 $\mathbf J$ 方向的投影推导；
- 史特恩—盖拉赫屏幕偏转公式；
- 自旋—轨道相互作用常数的完整相对论推导。

---

## 二十二、本章常数卡

| 常数 | 数值 | 用途 |
|---|---:|---|
| 玻尔磁子 | $\mu_B=9.274\times10^{-24}\,\mathrm{J/T}$ | 磁矩、塞曼能级移动 |
| 玻尔磁子 | $\mu_B=5.788\times10^{-5}\,\mathrm{eV/T}$ | 用 eV 快速算磁场分裂 |
| $\mu_B/h$ | $13.996\,\mathrm{GHz/T}$ | 塞曼频率移动 |
| $\mu_B/(hc)$ | $0.46686\,\mathrm{cm^{-1}/T}$ | 光谱波数计算 |
| 精细结构常数 | $\alpha\approx1/137$ | 精细结构量级 |
| $hc$ | $1240\,\mathrm{eV\cdot nm}$ | 波长与光子能量换算 |
| 原子质量单位 | $u=1.66054\times10^{-27}\,\mathrm{kg}$ | 原子束计算 |

考试最值得记的快捷结论：

```math
\boxed{
1\,\mathrm T
\Rightarrow
\mu_BB\approx5.79\times10^{-5}\,\mathrm{eV}
}
```

```math
\boxed{
1\,\mathrm T
\Rightarrow
\frac{\mu_BB}{hc}
\approx0.4669\,\mathrm{cm^{-1}}
}
```

---

## 二十三、高频失分点

### 1. 把自旋理解成经典自转

错误：电子是一个真正自转的小球。

正确：自旋是内禀量子属性。

### 2. 把 $S=\hbar/2$

正确的是

```math
S=\frac{\sqrt3}{2}\hbar,
```

而

```math
S_z=\pm\frac{\hbar}{2}.
```

### 3. 忘记磁矩和角动量反向

对电子：

```math
\boldsymbol{\mu}\propto-\mathbf L
```

或

```math
\boldsymbol{\mu}\propto-\mathbf S.
```

### 4. 用均匀磁场解释史特恩—盖拉赫分束

均匀磁场主要产生力矩，不产生稳定的平移分束。

必须有

```math
\frac{\partial B}{\partial z}\neq0.
```

### 5. 认为 $j$ 只有 $l+s$

正确是

```math
j=l+s,l+s-1,\cdots,|l-s|.
```

单电子才简化为

```math
j=l\pm\frac12.
```

### 6. 把 $g_J$ 一律写成2

只有纯自旋、 $L=0$ 时通常有 $g_J=2$ 。

例如：

```math
{}^2P_{1/2}:g=\frac23,
```

```math
{}^2P_{3/2}:g=\frac43.
```

### 7. 无外场时也把 $m_j$ 当成不同能量

没有外场时，同一 $n,l,j$ 下不同 $m_j$ 通常简并。

只有外磁场破坏空间各向同性后，能量才显式依赖 $m_j$ 。

### 8. 数跃迁箭头等于数谱线

错误。

不同箭头可能具有相同的

```math
g_um_u-g_lm_l,
```

因而频率相同，会合并成同一条谱线。

正常塞曼效应中可能有很多允许箭头，但只出现三种不同频率。

### 9. 认为所有三重分裂都是正常塞曼效应

正常塞曼效应要求

```math
S=0,\qquad g=1.
```

强场帕邢—巴克效应也可能趋向三重分裂，但机制不同。

### 10. 弱场和强场量子数混用

弱场：

```math
j,m_j
```

是好量子数。

强场：

```math
m_l,m_s
```

更适合描述状态。

---

## 二十四、常见题型与标准解题流程

### 题型一：写原子态符号

1. 由电子字母确定 $l$ ；
2. 写出 $s=1/2$ ；
3. 求 $j=l\pm1/2$ ；
4. 多重度为 $2s+1=2$ ；
5. 写成 $n^{2}L_J$ 。

### 题型二：计算朗德因子

1. 从态符号读出 $S,L,J$ ；
2. 代入

```math
g_J
=
1+
\frac{
J(J+1)+S(S+1)-L(L+1)
}{
2J(J+1)
};
```

3. 检查特殊情况：
   - $S=0\Rightarrow g=1$ ；
   - $L=0\Rightarrow g=2$ 。

### 题型三：判断精细结构能级数

1. 确定 $l$ ；
2. 若 $l=0$ ，只有 $j=1/2$ ；
3. 若 $l\neq0$ ，有 $j=l\pm1/2$ ；
4. 根据自旋—轨道能量判断高低；
5. 用 $\Delta l,\Delta j$ 判断允许跃迁。

### 题型四：塞曼分裂

1. 写出上下能级的 $J$ ；
2. 求各自 $g_J$ ；
3. 列出所有 $m_J$ ；
4. 写出磁场能量

```math
\Delta E=g_Jm_J\mu_BB;
```

5. 按

```math
\Delta m=0,\pm1
```

画允许箭头；

6. 对每条箭头计算

```math
q=g_um_u-g_lm_l;
```

7. 相同 $q$ 合并；
8. 根据 $\Delta m$ 判断 $\pi$ 、 $\sigma^\pm$ 偏振。

### 题型五：史特恩—盖拉赫实验

1. 确认磁场不均匀；
2. 写

```math
F_z=\mu_z\frac{\partial B}{\partial z};
```

3. 将运动分成磁场内匀加速和磁场外匀速；
4. 区分单束偏转和两束间距；
5. 求出 $\mu_z$ ；
6. 与 $\mu_B$ 比较，判断 $g,m_j$ 。

---

## 二十五、本章核心因果链回顾

```math
\text{电子轨道运动}
\Rightarrow
\text{轨道角动量和轨道磁矩}
```

```math
\text{史特恩—盖拉赫出现两束}
\Rightarrow
\text{引入 }s=\frac12
```

```math
\mathbf L+\mathbf S=\mathbf J
\Rightarrow
j=l\pm\frac12
```

```math
\mathbf L\cdot\mathbf S
\Rightarrow
\text{同一 }n,l\text{ 能级按 }j\text{ 分裂}
```

```math
\text{碱金属双线}
\Rightarrow
\text{证明自旋—轨道耦合}
```

```math
\boldsymbol{\mu}_J\cdot\mathbf B
\Rightarrow
\text{能级按 }m_j\text{ 分裂}
```

```math
\text{正常或反常塞曼效应}
```

```math
B\text{ 极强}
\Rightarrow
\mathbf L,\mathbf S\text{ 解耦}
\Rightarrow
\text{帕邢—巴克效应}
```

---

## 二十六、闭卷自测

1. 为什么电子轨道磁矩与轨道角动量方向相反？
2. 玻尔磁子的定义和数值是什么？
3. 为什么均匀磁场不能完成史特恩—盖拉赫分束？
4. 为什么只考虑轨道角动量不可能产生两束？
5. 电子的 $s,m_s,S,S_z$ 分别是多少？
6. 为什么不能把电子自旋理解为经典小球自转？
7. 一个 $p$ 电子可以形成哪些 $j$ 状态？
8. 写出 $2p$ 电子的原子态符号。
9. 写出朗德因子公式。
10. ${}^2P_{1/2}$ 、 ${}^2P_{3/2}$ 、 ${}^2S_{1/2}$ 的 $g_J$ 各是多少？
11. 为什么主线系双线间距随 $n$ 增大而减小？
12. 为什么锐线系双线间距近似不变？
13. 为什么漫线系通常只有三条，而不是四条？
14. 正常塞曼效应必须满足什么条件？
15. 为什么正常塞曼效应虽然允许多条跃迁箭头，却只有三条谱线？
16. $\pi$ 线和 $\sigma$ 线在垂直磁场方向观察时各是什么偏振？
17. 弱场和强场下分别用哪组量子数描述能级？
18. 帕邢—巴克效应为什么重新趋向三重分裂？

复习本章时，最优先掌握的不是复杂推导，而是下面这条主线：

> **轨道运动产生轨道磁矩；两束分裂迫使我们引入自旋；轨道与自旋耦合产生精细结构；总磁矩与外磁场作用产生塞曼分裂。**
