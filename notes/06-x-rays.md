---
title: 第六章 X射线
aliases:
  - X射线
  - 原子物理第六章
tags:
  - 原子物理
  - 期末复习
  - X射线
  - 康普顿散射
  - 布拉格衍射
date: 2026-06-16
---

# 第六章 X射线

> [!NOTE] 本章核心问题
> 高速电子打到物质上为什么会产生 X 射线？X 射线为什么既能发生衍射，又能像粒子一样与电子碰撞？它又如何揭示原子的内层电子结构？

本章包括四部分：

1. X 射线的发现及其波动性
2. X 射线产生的机制
3. 康普顿散射
4. X 射线的吸收

---

## 一、本章在整门原子物理中的位置

前五章主要研究：

- 原子核外电子如何排布；
- 外层电子的能级与跃迁；
- 自旋、精细结构和多电子原子。

第六章把研究对象进一步推进到两个方向：

1. **用 X 射线研究原子和晶体结构；**
2. **研究原子内层电子的能级和跃迁。**

可以把本章理解成前面知识的综合应用：

```math
\text{电子加速}
\rightarrow
\text{撞击靶材}
\rightarrow
\begin{cases}
\text{减速辐射} \rightarrow \text{连续谱},\\
\text{打出内层电子} \rightarrow \text{特征谱}.
\end{cases}
```

产生的 X 射线又会发生：

```math
\begin{aligned}
\text{通过晶体}
&\rightarrow
\text{衍射，表现波动性},\\
\text{撞击近似自由电子}
&\rightarrow
\text{康普顿散射，表现粒子性},\\
\text{穿过物质}
&\rightarrow
\text{吸收和衰减}.
\end{aligned}
```

这就是整章的主线。

---

## 二、先建立本章的统一物理图像

想象一个真空管。

左边有一个被加热的阴极，持续放出电子；右边放着一块金属靶。阴极和金属靶之间加很高的电压 $U$ 。

电子经过电场加速后获得动能：

```math
E_k=eU.
```

高速电子撞上金属靶后，主要发生两类过程。

### 2.1 第一类过程：电子被靶核减速

高速电子经过原子核附近时，受到强库仑力，运动方向和速度发生改变。

带电粒子只要有加速度，就会辐射电磁波。

由于每个电子损失的能量可以不同，因此产生各种不同能量的光子，形成：

```math
\boxed{\text{连续 X 射线谱}}
```

这种辐射称为**轫致辐射**或**刹车辐射**。

### 2.2 第二类过程：高速电子击出靶原子的内层电子

如果入射电子能量足够高，它可以把靶原子的 $K$ 、 $L$ 、 $M$ 层电子击出。

这会在内层留下一个“空穴”。

外层电子随后向内层跃迁，释放出确定能量的光子：

```math
h\nu=E_{\text{初}}-E_{\text{末}}.
```

因为内层能级是分立的，所以得到若干条分立谱线：

```math
\boxed{\text{特征 X 射线谱}}
```

它像元素的“指纹”，主要由靶元素的原子序数 $Z$ 决定。

---

## 三、X 射线是什么

### 3.1 X 射线的本质

X 射线本质上是一种波长很短、光子能量很高的电磁波。

典型波长约为：

```math
10^{-2}\,\mathrm{nm}
\sim
10\,\mathrm{nm}.
```

课程中通常以约 $0.1\,\mathrm{nm}$ 为粗略界线：

- 波长较长、能量较低：软 X 射线；
- 波长较短、能量较高：硬 X 射线。

根据

```math
E=h\nu=\frac{hc}{\lambda},
```

波长越短，单个光子的能量越高，通常穿透能力也越强。

X 射线能使照相底片感光、使某些物质发出荧光，也能使物质发生电离。同时，它具有偏振、干涉和衍射等电磁波性质。

### 3.2 为什么普通光栅不能很好地研究 X 射线

要明显观察衍射，需要障碍物或周期结构的尺寸与波长接近：

```math
d\sim\lambda.
```

可见光波长约为几百纳米，因此可以用刻线光栅。

但 X 射线波长约为：

```math
\lambda\sim0.1\,\mathrm{nm}
=
10^{-10}\,\mathrm{m}.
```

普通机械方法无法制造间距只有 $10^{-10}\,\mathrm{m}$ 的光栅。

而晶体中原子或离子的间距恰好也是：

```math
d\sim10^{-10}\,\mathrm{m}.
```

所以晶体就是天然的 X 射线光栅。

这就是劳厄想到用晶体检验 X 射线波动性的根本原因。

---

## 四、X 射线衍射与布拉格公式

### 4.1 物理模型

把晶体内部想象成许多互相平行、等间距的晶面。

设：

- 相邻晶面距离为 $d$ ；
- X 射线波长为 $\lambda$ ；
- 入射线与晶面的夹角为 $\theta$ 。

两束 X 射线分别被相邻晶面散射。

下层晶面的那束光比上层那束多走了一段路程。

几何上，这个额外路程为：

```math
\Delta=2d\sin\theta.
```

当光程差等于波长的整数倍时，两束波相长干涉：

```math
2d\sin\theta=n\lambda,
\qquad
n=1,2,3,\cdots
```

这就是**布拉格公式**。

### 4.2 布拉格公式的物理意义

```math
\boxed{2d\sin\theta=n\lambda}
```

它连接了三个尺度：

- 晶体内部结构尺度 $d$ ；
- X 射线波长 $\lambda$ ；
- 实验中可测的衍射角 $\theta$ 。

因此它有两类相反的用途。

#### 已知晶面间距，测 X 射线波长

```math
\lambda=\frac{2d\sin\theta}{n}.
```

#### 已知 X 射线波长，测晶面间距

```math
d=\frac{n\lambda}{2\sin\theta}.
```

这就是为什么 X 射线可以研究晶体结构。

### 4.3 必须澄清的角度定义

布拉格公式中的 $\theta$ 是：

> **入射线与晶面的夹角，也叫掠射角。**

实验仪器有时给出的是入射线与衍射线之间的夹角，这个角通常是：

```math
2\theta.
```

因此考试时必须先判断题目给的是 $\theta$ 还是 $2\theta$ 。

这是最常见的失分点之一。

### 4.4 “晶面反射”不是真正的镜面反射

布拉格模型常画成射线被晶面“反射”。

但晶体内部并不存在一面真实的小镜子。

更准确的图像是：

1. 每个原子中的电子受到入射 X 射线电场驱动；
2. 电子发生受迫振动并重新辐射；
3. 大量原子的散射波相互叠加；
4. 只有满足相长干涉条件的方向出现强峰。

所以所谓“晶面反射”，本质是许多散射波的相干叠加。

### 4.5 比例关系与快速判断

由

```math
2d\sin\theta=n\lambda
```

可知，在 $n,d$ 不变时：

```math
\lambda\uparrow
\quad\Longrightarrow\quad
\theta\uparrow.
```

在 $\lambda,d$ 不变时：

```math
n\uparrow
\quad\Longrightarrow\quad
\theta\uparrow.
```

又因为

```math
\sin\theta\leq1,
```

所以衍射级次不能无限大：

```math
n\leq\frac{2d}{\lambda}.
```

### 4.6 典型例题一：由衍射角求波长

某晶体晶面间距为

```math
d=0.200\,\mathrm{nm},
```

一级衍射峰出现在

```math
\theta=20.0^\circ.
```

求 X 射线波长和光子能量。

#### 题意翻译

已知晶体周期和衍射角，要求 X 射线波长，属于布拉格衍射题。

#### 选择公式

一级衍射：

```math
n=1.
```

使用：

```math
2d\sin\theta=n\lambda.
```

#### 计算波长

```math
\lambda
=
2d\sin\theta
=
2\times0.200\times\sin20.0^\circ\,\mathrm{nm}.
```

得到：

```math
\lambda\approx0.1368\,\mathrm{nm}.
```

#### 计算光子能量

利用：

```math
E=\frac{hc}{\lambda},
\qquad
hc\approx1240\,\mathrm{eV\cdot nm}.
```

所以：

```math
E
=
\frac{1240}{0.1368}\,\mathrm{eV}
\approx
9.06\times10^3\,\mathrm{eV}.
```

即：

```math
\boxed{E\approx9.06\,\mathrm{keV}}.
```

> [!TIP] 方法总结
> 这类题的固定流程是：
>
> ```math
> \theta
> \overset{\text{布拉格公式}}{\longrightarrow}
> \lambda
> \overset{E=hc/\lambda}{\longrightarrow}
> E
> ```
>
> 最容易错的是把实验给出的 $2\theta$ 直接代入。

---

## 五、X 射线管与发射谱

### 5.1 X 射线管的基本组成

一个典型 X 射线管包括：

- 阴极；
- 阳极靶；
- 高电压电源；
- 真空环境；
- X 射线出口窗口。

其信号过程是：

```math
\text{阴极放出电子}
\rightarrow
\text{高压加速}
\rightarrow
\text{电子撞击阳极靶}
\rightarrow
\text{产生 X 射线}.
```

电子获得的最大动能是：

```math
E_k=eU.
```

这里的 $U$ 是管电压。

### 5.2 三个实验旋钮分别控制什么

| 实验量 | 主要作用 |
|---|---|
| 管电压 $U$ | 决定电子最大动能、连续谱短波限，并影响总强度 |
| 管电流 $I$ | 决定单位时间撞击靶材的电子数，主要改变 X 射线强度 |
| 靶材原子序数 $Z$ | 决定特征谱位置，并影响轫致辐射强度 |

> [!IMPORTANT] 必须理解
> 管电压决定“每个电子最多有多少能量”，管电流决定“每秒有多少电子”。

---

## 六、连续 X 射线谱：轫致辐射

### 6.1 为什么会形成连续谱

所有入射电子在进入靶材前都有大致相同的最大动能：

```math
eU.
```

但它们在靶中经历的过程不同。

有的电子：

- 一次碰撞只损失很少能量；
- 多次碰撞后逐渐停下；
- 某一次碰撞损失较大能量；
- 极少数电子一次就损失几乎全部动能。

如果某次过程损失能量为 $\Delta E$ ，就可能产生能量为

```math
h\nu=\Delta E
```

的光子。

因为 $\Delta E$ 可以在一个连续范围内变化，所以光子能量也连续：

```math
0\lt h\nu\leq eU.
```

因此产生连续谱。

### 6.2 为什么连续谱存在最短波长

单个 X 光子的能量不可能超过入射电子的全部动能。

最大光子能量发生在一个极端情况：

> 一个电子在一次相互作用中，把全部动能转移给一个光子。

于是：

```math
h\nu_{\max}=eU.
```

又因为：

```math
\nu_{\max}=\frac{c}{\lambda_{\min}},
```

所以：

```math
\boxed{
eU=\frac{hc}{\lambda_{\min}}
}
```

即：

```math
\boxed{
\lambda_{\min}=\frac{hc}{eU}
}
```

这称为连续谱的**短波限**，也叫量子极限或杜安—亨特定律。

### 6.3 考试快捷公式

当 $U$ 用千伏、 $\lambda$ 用纳米时：

```math
\boxed{
\lambda_{\min}(\mathrm{nm})
=
\frac{1.24}{U(\mathrm{kV})}
}
```

因为一个电子经过 $1\,\mathrm{kV}$ 电压加速后，获得

```math
1\,\mathrm{keV}
```

的能量，所以还有一个极实用的关系：

```math
\boxed{
E_{\gamma,\max}(\mathrm{keV})
=
U(\mathrm{kV})
}
```

例如：

- 管电压为 $50\,\mathrm{kV}$ ；
- 最大光子能量就是 $50\,\mathrm{keV}$ 。

### 6.4 短波限公式的适用条件

公式

```math
eU=\frac{hc}{\lambda_{\min}}
```

假设：

1. 电子初始动能相对 $eU$ 可以忽略；
2. 电子在真空中被完整电势差 $U$ 加速；
3. 极限情况下，电子全部动能转化为一个光子；
4. 忽略靶材反冲和其他微小能量损失。

### 6.5 连续谱随实验条件如何变化

#### 增大管电压

- 电子最大动能增加；
- 最大光子能量增加；
- 最短波长减小；
- 连续谱向短波方向延伸；
- 总强度通常也增大。

即：

```math
U\uparrow
\quad\Longrightarrow\quad
\lambda_{\min}\downarrow.
```

#### 增大管电流

- 单位时间电子数增加；
- 光子数增加；
- 谱线整体变强；
- 最短波长不变。

#### 改变靶材

在课程近似下：

- 连续谱的基本形状不由靶材决定；
- 总强度会随靶核电荷增大而增强；
- 短波限不变；
- 特征谱位置会明显改变。

### 6.6 典型例题二：连续谱短波限

某 X 射线管连续谱的最短波长为：

```math
\lambda_{\min}=0.0124\,\mathrm{nm}.
```

求管电压。

使用：

```math
U(\mathrm{kV})
=
\frac{1.24}{\lambda_{\min}(\mathrm{nm})}.
```

代入：

```math
U
=
\frac{1.24}{0.0124}\,\mathrm{kV}
=
100\,\mathrm{kV}.
```

所以：

```math
\boxed{U=100\,\mathrm{kV}}.
```

### 6.7 举一反三

如果管电压从 $40\,\mathrm{kV}$ 增加到 $80\,\mathrm{kV}$ ，则：

```math
\lambda_{\min}\propto\frac1U.
```

因此：

```math
\lambda_{\min}'=\frac12\lambda_{\min}.
```

注意：不是所有光子的波长都减半，而只是短波限减半，整个连续谱分布也会随之改变。

---

## 七、特征 X 射线谱：内层电子跃迁

### 7.1 为什么特征谱是分立的

高速电子若击出原子的内层电子，便产生一个空穴。

例如， $K$ 层电子被击出：

```math
K\text{ 层产生空穴}.
```

外层电子随后跃迁到 $K$ 层。

由于初末能级都是分立的，释放的光子能量也是分立的：

```math
h\nu
=
E_{\text{高能级}}
-
E_{\text{低能级}}.
```

因此出现尖锐谱线。

### 7.2 K、L、M 线系是什么意思

X 射线谱线按照电子跃迁的**末态壳层**分类。

#### K 线系

所有以 $K$ 层为末态的跃迁：

```math
L,M,N,\cdots\rightarrow K.
```

其中：

- $L\rightarrow K$ ： $K_\alpha$ ；
- $M\rightarrow K$ ： $K_\beta$ ；
- $N\rightarrow K$ ： $K_\gamma$ 。

#### L 线系

所有以 $L$ 层为末态的跃迁：

```math
M,N,O,\cdots\rightarrow L.
```

例如：

- $M\rightarrow L$ ： $L_\alpha$ ；
- $N\rightarrow L$ ： $L_\beta$ 。

> [!TIP] 记忆口诀
> 大写字母说明“落到哪一层”，希腊字母说明“从多远的上一层落下来”。

### 7.3 用结合能表示谱线能量

内层电子通常用正的结合能表示：

- $B_K$ ：移走一个 $K$ 层电子需要的能量；
- $B_L$ ：移走一个 $L$ 层电子需要的能量。

由于 $K$ 层束缚更深：

```math
B_K\gt B_L\gt B_M.
```

当 $L$ 层电子填补 $K$ 空穴时：

```math
\boxed{
E_{K_\alpha}
=
h\nu_{K_\alpha}
=
B_K-B_L
}
```

当 $M$ 层电子填补 $K$ 空穴时：

```math
\boxed{
E_{K_\beta}
=
B_K-B_M
}
```

因为：

```math
B_M\lt B_L,
```

所以：

```math
E_{K_\beta}\gt E_{K_\alpha},
```

从而：

```math
\lambda_{K_\beta}\lt \lambda_{K_\alpha}.
```

这是常见判断题。

### 7.4 为什么必须有临界电压

要产生 $K$ 系特征谱，首先必须击出一个 $K$ 层电子。

入射电子能量至少要满足：

```math
eU\geq B_K.
```

因此存在临界电压：

```math
\boxed{
U_K=\frac{B_K}{e}
}
```

如果管电压低于这个临界值，即使电子持续撞击靶材，也不会产生 $K$ 系特征谱。

### 7.5 特征谱由什么决定

特征谱峰的位置主要由

```math
\boxed{\text{靶材的原子序数 }Z}
```

决定。

一旦空穴形成，后续跃迁能量几乎只由靶原子的内层能级决定。

因此：

- 改变管电压，只要仍高于临界值，谱线位置基本不变；
- 改变管电流，谱线强度改变，位置不变；
- 改变靶材，谱线位置改变。

课程近似通常说特征谱与元素化学状态无关。更严格地说，内层能级受化学环境影响较小，高分辨率实验中仍可能观察到微小的化学位移。

---

## 八、莫塞莱定律

### 8.1 实验规律

莫塞莱研究不同元素的特征 X 射线，发现对于同一线系：

```math
\sqrt{\nu}
```

与原子序数 $Z$ 近似成线性关系：

```math
\boxed{
\sqrt{\nu}=A(Z-\sigma)
}
```

或写成：

```math
\boxed{
\nu=A^2(Z-\sigma)^2
}
```

其中：

- $A$ 是与线系有关的常量；
- $\sigma$ 是屏蔽常数。

对 $K_\alpha$ 线，课程中常用经验形式：

```math
\boxed{
\nu_{K_\alpha}
\approx
0.248\times10^{16}(Z-1)^2\ \mathrm{Hz}
}
```

### 8.2 莫塞莱定律为什么成立

先用类氢原子的近似能级：

```math
E_n
\approx
-13.6\,\mathrm{eV}
\frac{Z_{\mathrm{eff}}^2}{n^2}.
```

对于 $K_\alpha$ 线，是：

```math
n=2\rightarrow n=1.
```

由于另一个 $K$ 层电子对核电荷有一定屏蔽，可以近似取：

```math
Z_{\mathrm{eff}}\approx Z-1.
```

所以：

```math
h\nu_{K_\alpha}
=
13.6(Z-1)^2
\left(
1-\frac14
\right)\mathrm{eV}.
```

于是：

```math
h\nu_{K_\alpha}
=
10.2(Z-1)^2\,\mathrm{eV}.
```

因此：

```math
\nu_{K_\alpha}\propto(Z-1)^2,
```

即：

```math
\sqrt{\nu_{K_\alpha}}\propto Z-1.
```

这就解释了莫塞莱经验定律。

### 8.3 莫塞莱定律的深层意义

元素在周期表中的根本编号不是原子质量，而是：

```math
\boxed{\text{原子核电荷数 }Z}
```

原子序数 $Z$ 决定：

- 核中质子数；
- 中性原子的电子数；
- 内层电子束缚能；
- 特征 X 射线频率；
- 元素在周期表中的根本身份。

### 8.4 典型例题三：估算铁的 $K_\alpha$ 线

铁的原子序数为：

```math
Z=26.
```

由近似公式：

```math
E_{K_\alpha}
\approx
10.2(Z-1)^2\,\mathrm{eV}.
```

得到：

```math
E_{K_\alpha}
\approx
10.2\times25^2\,\mathrm{eV}.
```

所以：

```math
E_{K_\alpha}
\approx
6375\,\mathrm{eV}
=
6.38\,\mathrm{keV}.
```

其波长为：

```math
\lambda
=
\frac{1240}{6375}\,\mathrm{nm}
\approx
0.1945\,\mathrm{nm}.
```

因此：

```math
\boxed{
\lambda_{K_\alpha}\approx0.195\,\mathrm{nm}
}
```

这个结果与实际铁 $K_\alpha$ 波长非常接近，说明有效核电荷近似很有解释力。

---

## 九、连续谱与特征谱的对比

| 对比项 | 连续谱 | 特征谱 |
|---|---|---|
| 产生机制 | 高速电子减速产生轫致辐射 | 内层电子空穴被外层电子填补 |
| 光谱形状 | 连续背景 | 分立尖峰 |
| 能量是否连续 | 连续 | 分立 |
| 是否有短波限 | 有 | 每条谱线波长固定 |
| 峰的位置主要由什么决定 | 短波限由管电压决定 | 由靶材原子序数决定 |
| 改变管电流 | 强度变，位置不变 | 强度变，位置不变 |
| 改变管电压 | 短波限和强度变化 | 超过临界值后，位置基本不变 |
| 改变靶材 | 强度有所变化 | 谱线位置明显变化 |

> [!IMPORTANT] 核心结论
> 连续谱告诉我们入射电子怎样减速；特征谱告诉我们靶原子的内层能级怎样分布。

---

## 十、俄歇过程

当外层电子填补内层空穴时，释放的能量不一定以 X 光子形式放出。

还有另一种可能：

1. 一个外层电子填补内层空穴；
2. 释放出的能量传给另一个电子；
3. 第二个电子从原子中逸出。

这个逸出的电子叫做**俄歇电子**。

例如，若 $L$ 层电子填补 $K$ 空穴，能量又击出一个 $M$ 层电子，则俄歇电子动能近似为：

```math
E_{\mathrm{Auger}}
\approx
B_K-B_L-B_M.
```

特征 X 射线和俄歇电子是内层空穴退激发的两条竞争通道。

---

## 十一、康普顿散射

### 11.1 本节要解决的问题

经典电磁理论认为：

1. 入射电磁波驱动电子受迫振动；
2. 电子振动频率等于入射波频率；
3. 电子重新辐射出的波频率应保持不变。

所以经典理论预言：

```math
\lambda'=\lambda.
```

但实验发现：

- 散射光中有波长不变的成分；
- 也有波长变长的成分；
- 波长改变量与散射角有关。

即：

```math
\lambda'\gt \lambda.
```

这说明部分 X 射线光子把能量和动量传给了电子。

### 11.2 康普顿实验规律

设：

- 入射 X 射线波长为 $\lambda$ ；
- 散射后波长为 $\lambda'$ ；
- 光子散射角为 $\theta$ 。

实验发现：

```math
\boxed{
\Delta\lambda
=
\lambda'-\lambda
=
\frac{h}{m_ec}(1-\cos\theta)
}
```

令：

```math
\lambda_C=\frac{h}{m_ec},
```

称为电子的康普顿波长：

```math
\boxed{
\lambda_C
=
2.426\,\mathrm{pm}
=
0.002426\,\mathrm{nm}
=
0.02426\,\text{\AA}
}
```

于是：

```math
\boxed{
\Delta\lambda
=
\lambda_C(1-\cos\theta)
}
```

---

## 十二、康普顿公式的完整推导

### 12.1 物理模型

把 X 射线看作一个光子。

碰撞前：

- 光子能量为 $E=pc=h\nu$ ；
- 光子动量为 $p=h/\lambda$ ；
- 电子静止，静止质量为 $m_e$ 。

碰撞后：

- 光子动量为 $p'=h/\lambda'$ ；
- 光子与原方向夹角为 $\theta$ ；
- 电子获得反冲动量 $P$ ；
- 电子总能量为 $E_e$ 。

模型假设：

1. 电子碰撞前近似自由且静止；
2. 碰撞过程满足能量守恒；
3. 碰撞过程满足动量守恒；
4. 反冲电子使用相对论能量动量关系。

### 12.2 能量守恒

碰撞前总能量：

```math
pc+m_ec^2.
```

碰撞后总能量：

```math
p'c+E_e.
```

所以：

```math
pc+m_ec^2=p'c+E_e.
```

整理得：

```math
E_e=m_ec^2+c(p-p').
```

### 12.3 动量守恒

矢量形式：

```math
\vec p=\vec p\,'+\vec P.
```

因此：

```math
\vec P=\vec p-\vec p\,'.
```

两边平方：

```math
P^2=p^2+p'^2-2pp'\cos\theta.
```

### 12.4 使用电子的相对论关系

电子满足：

```math
E_e^2=P^2c^2+m_e^2c^4.
```

将

```math
E_e=m_ec^2+c(p-p')
```

和

```math
P^2=p^2+p'^2-2pp'\cos\theta
```

代入：

```math
\left[
m_ec^2+c(p-p')
\right]^2
=
c^2
\left(
p^2+p'^2-2pp'\cos\theta
\right)
+
m_e^2c^4.
```

展开左边：

```math
m_e^2c^4
+
2m_ec^3(p-p')
+
c^2(p-p')^2.
```

消去两边的 $m_e^2c^4$ ，并注意：

```math
(p-p')^2
=
p^2+p'^2-2pp',
```

得到：

```math
2m_ec(p-p')
=
2pp'(1-\cos\theta).
```

约去 $2$ ：

```math
m_ec(p-p')
=
pp'(1-\cos\theta).
```

两边除以 $pp'$ ：

```math
m_ec
\left(
\frac1{p'}-\frac1p
\right)
=
1-\cos\theta.
```

因为：

```math
p=\frac h\lambda,
\qquad
p'=\frac h{\lambda'},
```

所以：

```math
\frac1p=\frac{\lambda}{h},
\qquad
\frac1{p'}=\frac{\lambda'}{h}.
```

代入得：

```math
m_ec
\frac{\lambda'-\lambda}{h}
=
1-\cos\theta.
```

最终：

```math
\boxed{
\lambda'-\lambda
=
\frac{h}{m_ec}(1-\cos\theta)
}
```

推导完成。

---

## 十三、康普顿公式的物理意义

### 13.1 波长改变量只与散射角有关

```math
\Delta\lambda
=
\lambda_C(1-\cos\theta).
```

它与：

- 入射波长无关；
- 靶材种类无关；
- X 射线强度无关。

在自由电子近似下，只取决于：

- 散射角 $\theta$ ；
- 电子质量 $m_e$ 。

### 13.2 散射角越大，波长增加越多

当

```math
\theta=0,
```

有：

```math
\Delta\lambda=0.
```

光子沿原方向前进，几乎没有能量传给电子。

当

```math
\theta=90^\circ,
```

有：

```math
\Delta\lambda=\lambda_C.
```

当

```math
\theta=180^\circ,
```

有：

```math
\Delta\lambda_{\max}=2\lambda_C.
```

所以：

```math
\boxed{
\Delta\lambda_{\max}
=
4.852\,\mathrm{pm}
}
```

### 13.3 为什么散射后波长一定变长

光子把一部分能量传给电子。

因此：

```math
E'\lt E.
```

又因为：

```math
E=\frac{hc}{\lambda},
```

所以：

```math
E'\downarrow
\quad\Longrightarrow\quad
\lambda'\uparrow.
```

即：

```math
\lambda'\gt \lambda.
```

---

## 十四、康普顿散射的能量形式

设入射光子能量为：

```math
E=h\nu.
```

散射后光子能量为：

```math
E'=h\nu'.
```

康普顿公式可以改写成：

```math
\boxed{
E'
=
\frac{E}
{1+\dfrac{E}{m_ec^2}(1-\cos\theta)}
}
```

定义：

```math
\gamma=\frac{E}{m_ec^2},
```

则：

```math
E'
=
\frac{E}{1+\gamma(1-\cos\theta)}.
```

反冲电子获得的动能为：

```math
T=E-E'.
```

所以：

```math
\boxed{
T
=
E
\frac{\gamma(1-\cos\theta)}
{1+\gamma(1-\cos\theta)}
}
```

### 14.1 散射光子的最小能量

散射光子能量最小时，光子损失能量最多。

这发生在：

```math
\theta=180^\circ.
```

因为：

```math
1-\cos180^\circ=2,
```

所以：

```math
\boxed{
E'_{\min}
=
\frac{E}{1+2E/(m_ec^2)}
}
```

### 14.2 反冲电子最大动能

```math
T_{\max}=E-E'_{\min}.
```

代入得：

```math
\boxed{
T_{\max}
=
\frac{2E^2}
{m_ec^2+2E}
}
```

---

## 十五、典型例题四：入射光子能量等于电子静止能

已知：

```math
E=m_ec^2=511\,\mathrm{keV}.
```

求散射光子的最小能量。

### 模型识别

散射光子能量最小，对应：

```math
\theta=180^\circ.
```

使用：

```math
E'_{\min}
=
\frac{E}{1+2E/(m_ec^2)}.
```

因为：

```math
\frac{E}{m_ec^2}=1,
```

所以：

```math
E'_{\min}
=
\frac{E}{1+2}
=
\frac{E}{3}.
```

于是：

```math
E'_{\min}
=
\frac{511}{3}\,\mathrm{keV}
\approx
170\,\mathrm{keV}.
```

因此：

```math
\boxed{
E'_{\min}
\approx
170\,\mathrm{keV}
}
```

反冲电子获得的最大动能为：

```math
T_{\max}
=
511-170
\approx
341\,\mathrm{keV}.
```

---

## 十六、典型例题五：由散射角求波长和反冲电子能量

入射 X 射线波长为：

```math
\lambda=0.0710\,\mathrm{nm},
```

散射角为：

```math
\theta=90^\circ.
```

求散射后波长及电子获得的能量。

### 第一步：计算波长改变量

```math
\Delta\lambda
=
\lambda_C(1-\cos90^\circ)
=
\lambda_C.
```

所以：

```math
\Delta\lambda
=
0.002426\,\mathrm{nm}.
```

### 第二步：散射后波长

```math
\lambda'
=
\lambda+\Delta\lambda
=
0.0710+0.002426.
```

因此：

```math
\boxed{
\lambda'
=
0.07343\,\mathrm{nm}
}
```

### 第三步：入射光子能量

```math
E
=
\frac{1240}{0.0710}\,\mathrm{eV}
\approx
17.46\,\mathrm{keV}.
```

### 第四步：散射光子能量

```math
E'
=
\frac{1240}{0.07343}\,\mathrm{eV}
\approx
16.89\,\mathrm{keV}.
```

### 第五步：反冲电子动能

```math
T=E-E'.
```

所以：

```math
T
\approx
17.46-16.89
=
0.577\,\mathrm{keV}.
```

即：

```math
\boxed{
T\approx577\,\mathrm{eV}
}
```

---

## 十七、为什么实验中还有波长不变的散射光

康普顿模型假设电子近似自由。

但物质中有些电子束缚得很紧。

当光子与整个原子发生相干散射时，动量主要传给整个原子。

原子质量 $M$ 远大于电子质量：

```math
M\gg m_e.
```

若把康普顿公式中的质量换成原子质量：

```math
\Delta\lambda
=
\frac{h}{Mc}(1-\cos\theta),
```

这个改变量极小，实验上近似看作：

```math
\Delta\lambda\approx0.
```

所以散射光中同时存在：

- 波长改变的康普顿散射；
- 波长基本不变的相干散射。

---

## 十八、为什么可见光的康普顿效应不明显

康普顿波长改变量最大只有：

```math
2\lambda_C
\approx
4.85\,\mathrm{pm}.
```

对于可见光：

```math
\lambda
\sim
500\,\mathrm{nm}
=
5\times10^5\,\mathrm{pm}.
```

相对改变量最多约为：

```math
\frac{\Delta\lambda}{\lambda}
\sim
\frac{4.85}{5\times10^5}
\sim
10^{-5}.
```

太小，很难观察。

而对于 X 射线：

```math
\lambda\sim50\,\mathrm{pm},
```

相对改变量可达百分之几，因此明显。

所以不是可见光完全没有康普顿散射，而是相对波长变化太小。

---

## 十九、康普顿效应证明了什么

光电效应主要证明：

```math
\boxed{
\text{光子的能量是 }E=h\nu
}
```

康普顿效应进一步证明：

```math
\boxed{
\text{光子具有动量 }p=\frac h\lambda
}
```

因此康普顿效应说明光子能够像粒子一样：

- 携带能量；
- 携带动量；
- 与电子发生碰撞；
- 满足能量守恒和动量守恒。

但这不否定光的波动性。

X 射线衍射证明波动性，康普顿散射证明粒子性。二者共同体现波粒二象性。

---

## 二十、X 射线的吸收与衰减

### 20.1 “吸收”更准确地说是原射线束的衰减

X 射线穿过物质时，原传播方向上的强度减小。

光子可能：

- 被真正吸收；
- 被散射到其他方向；
- 转化为其他粒子。

因此严格来说，公式中的 $\mu$ 常叫**线性衰减系数**。

课程中通常统称为吸收系数。

### 20.2 X 射线与物质相互作用的三种主要机制

#### 光电效应

光子被束缚电子完全吸收，光子消失。

电子获得动能：

```math
T=h\nu-B.
```

其中 $B$ 是该电子的结合能。

#### 康普顿散射

光子与近似自由电子碰撞。

- 光子仍然存在；
- 光子能量减小；
- 传播方向改变；
- 电子获得反冲动能。

#### 电子对产生

当光子能量足够高时，在原子核附近可以转化成电子和正电子：

```math
\gamma\rightarrow e^-+e^+.
```

至少需要提供二者的静止能量：

```math
E_\gamma\geq2m_ec^2.
```

因此阈值为：

```math
\boxed{
E_\gamma\geq1.022\,\mathrm{MeV}
}
```

原子核的存在主要用于满足动量守恒。

---

## 二十一、指数衰减定律

### 21.1 建立模型

设 X 射线进入材料前强度为：

```math
I_0.
```

通过厚度 $x$ 后，强度为：

```math
I(x).
```

考虑一层很薄的材料 $dx$ 。

在这层材料中损失的强度 $-dI$ 应当：

- 与当前强度 $I$ 成正比；
- 与厚度 $dx$ 成正比。

所以：

```math
-dI=\mu I\,dx.
```

即：

```math
\frac{dI}{I}=-\mu\,dx.
```

积分：

```math
\int_{I_0}^{I}\frac{dI}{I}
=
-\mu\int_0^x dx.
```

得到：

```math
\ln\frac{I}{I_0}
=
-\mu x.
```

因此：

```math
\boxed{
I=I_0e^{-\mu x}
}
```

### 21.2 线性衰减系数的意义

```math
\mu
```

表示单位长度材料使射线束发生衰减的能力。

量纲为：

```math
[\mu]=\mathrm{m^{-1}}
```

或常用：

```math
\mathrm{cm^{-1}}.
```

$\mu$ 越大：

- 材料吸收越强；
- 穿透能力越弱；
- 相同厚度下透射强度越小。

### 21.3 质量衰减系数

线性衰减系数与物质密度有关。

为了更方便比较不同密度的材料，定义质量衰减系数：

```math
\boxed{
\frac{\mu}{\rho}
}
```

其常用单位为：

```math
\mathrm{cm^2/g}.
```

需要区分：

- $\mu/\rho$ ：质量衰减系数；
- $\rho x$ ：质量厚度。

两者相乘：

```math
\mu x
=
\frac{\mu}{\rho}\rho x.
```

因此衰减定律也可写成：

```math
I
=
I_0
\exp
\left[
-\frac{\mu}{\rho}(\rho x)
\right].
```

### 21.4 半值层

使强度减少为原来一半的厚度称为半值层：

```math
I=\frac{I_0}{2}.
```

代入：

```math
\frac12=e^{-\mu x_{1/2}}.
```

取对数：

```math
\ln2=\mu x_{1/2}.
```

所以：

```math
\boxed{
x_{1/2}=\frac{\ln2}{\mu}
}
```

即：

```math
\boxed{
x_{1/2}\approx\frac{0.693}{\mu}
}
```

---

## 二十二、典型例题六：透射强度和半值层

某材料对某种 X 射线的线性衰减系数为：

```math
\mu=0.80\,\mathrm{cm^{-1}}.
```

射线穿过：

```math
x=3.0\,\mathrm{cm}
```

的材料后，求透射率及半值层。

### 透射率

```math
\frac{I}{I_0}
=
e^{-\mu x}
=
e^{-0.80\times3.0}.
```

所以：

```math
\frac{I}{I_0}
=
e^{-2.4}
\approx
0.0907.
```

即：

```math
\boxed{
\frac{I}{I_0}\approx9.1\%
}
```

### 半值层

```math
x_{1/2}
=
\frac{0.693}{0.80}\,\mathrm{cm}.
```

得到：

```math
\boxed{
x_{1/2}\approx0.866\,\mathrm{cm}
}
```

---

## 二十三、总衰减系数

不同能量范围内，三种相互作用可能同时存在。

因此总衰减系数可写为：

```math
\boxed{
\mu_{\text{总}}
=
\mu_{\text{光电}}
+
\mu_{\text{康普顿}}
+
\mu_{\text{电子对}}
}
```

定性上：

| 光子能量范围 | 常见主导过程 |
|---|---|
| 较低能量、高 $Z$ 材料 | 光电效应较强 |
| 中等能量 | 康普顿散射常较重要 |
| $E_\gamma\gt 1.022\,\mathrm{MeV}$ | 电子对产生开始可能发生 |

在医学影像中：

- 光电吸收有助于形成不同组织之间的对比；
- 康普顿散射会产生散射背景，降低图像清晰度。

---

## 二十四、X 射线吸收限

### 24.1 什么是吸收限

当入射光子能量还低于某一内层电子的结合能时，不能把它电离。

例如：

```math
E_\gamma\lt B_K,
```

就不能击出 $K$ 层电子。

当能量刚好达到：

```math
E_\gamma=B_K,
```

突然打开了一个新的光电吸收通道。

于是吸收系数会发生突跃。

这个突跃位置叫做：

```math
\boxed{\text{K 吸收限}}
```

同理还有：

- L 吸收限；
- M 吸收限。

若 K 吸收限对应波长为 $\lambda_K$ ，则：

```math
\boxed{
B_K=\frac{hc}{\lambda_K}
}
```

### 24.2 吸收限和特征谱线的区别

这是本章最容易混淆的概念之一。

#### K 吸收限

表示从 K 层把电子完全移到连续区所需的能量：

```math
E_{K,\text{edge}}=B_K.
```

#### $K_\alpha$ 特征线

表示 L 层电子跃迁到 K 层释放的能量：

```math
E_{K_\alpha}=B_K-B_L.
```

因此：

```math
\boxed{
E_{K,\text{edge}}\gt E_{K_\alpha}
}
```

也就是：

```math
\boxed{
\lambda_{K,\text{edge}}
\lt{}
\lambda_{K_\alpha}
}
```

吸收限是“从束缚态到连续区”，特征线是“两个束缚能级之间的跃迁”。

### 24.3 能量图与波长图的方向相反

因为：

```math
E=\frac{hc}{\lambda},
```

所以：

- 能量增加，波长减小；
- 能量图上向右，往往对应波长图上向左。

因此讨论吸收限“高能侧”和“短波侧”时，要特别注意横轴是什么。

---

## 二十五、典型例题七：由 L 吸收限估算 K 层电离能

钕原子的原子序数为：

```math
Z=60,
```

L 吸收限为：

```math
\lambda_L=0.19\,\mathrm{nm}.
```

估算从 K 层电离一个电子所需的能量。

### 第一步：由 L 吸收限求 L 层结合能

```math
B_L=\frac{hc}{\lambda_L}.
```

代入：

```math
B_L
=
\frac{1240}{0.19}\,\mathrm{eV}
\approx
6.53\,\mathrm{keV}.
```

### 第二步：由莫塞莱定律求 $K_\alpha$ 能量

课程中常用：

```math
\nu_{K_\alpha}
=
0.248\times10^{16}(Z-1)^2\,\mathrm{Hz}.
```

代入 $Z=60$ ：

```math
\nu_{K_\alpha}
=
0.248\times10^{16}\times59^2
\approx
8.63\times10^{18}\,\mathrm{Hz}.
```

于是：

```math
E_{K_\alpha}
=
h\nu_{K_\alpha}
\approx
35.7\,\mathrm{keV}.
```

### 第三步：利用能级关系

因为：

```math
E_{K_\alpha}=B_K-B_L,
```

所以：

```math
B_K=E_{K_\alpha}+B_L.
```

代入：

```math
B_K
\approx
35.7+6.53
=
42.2\,\mathrm{keV}.
```

所以：

```math
\boxed{
B_K\approx42\,\mathrm{keV}
}
```

> [!TIP] 核心突破口
> 这道题的关键不是直接套一个公式，而是建立能量关系：
>
> ```math
> K_\alpha\text{ 光子能量}
> =
> K\text{ 层结合能}
> -
> L\text{ 层结合能}.
> ```

---

## 二十六、吸收限的应用

### 26.1 X 射线滤波片

实际 X 射线源常同时产生：

- $K_\alpha$ ；
- $K_\beta$ ；
- 连续背景。

为了得到接近单色的 $K_\alpha$ 射线，可以选择一种材料，使它的 K 吸收边位于：

```math
E_{K_\alpha}
\lt{}
E_{\text{edge}}
\lt{}
E_{K_\beta}.
```

这样：

- $K_\alpha$ 能量低于吸收限，较容易通过；
- $K_\beta$ 能量高于吸收限，被强烈吸收。

于是 $K_\beta$ 被优先滤掉。

### 26.2 医学造影

不同元素在吸收限附近的吸收系数变化很大。

造影剂中的高原子序数元素，例如碘，对 X 射线有较强吸收。

选择吸收限上下两种接近的 X 射线能量，分别成像，再进行相减处理，可以：

- 削弱骨骼、肌肉等共同背景；
- 突出造影剂分布；
- 更清楚地显示血管结构。

---

## 二十七、本章核心概念辨析

| 概念 | 本质 | 主要决定因素 | 高频错误 |
|---|---|---|---|
| 连续谱 | 电子减速产生轫致辐射 | 管电压、管电流、靶材 $Z$ | 认为最短波长由靶材决定 |
| 特征谱 | 内层电子跃迁 | 靶材原子序数 $Z$ | 认为改变管电压会移动谱线 |
| 短波限 | 单光子可获得的最大能量 | 管电压 $U$ | 把它当作强度最大处 |
| K 吸收限 | 电离 K 层电子的阈值 | K 层结合能 | 与 $K_\alpha$ 谱线混淆 |
| $K_\alpha$ 线 | $L\rightarrow K$ 跃迁 | $B_K-B_L$ | 写成 $B_K$ |
| 康普顿散射 | 光子与近似自由电子碰撞 | 散射角、电子质量 | 认为改变量取决于靶材 |
| 相干散射 | 整个原子或紧束缚电子响应 | 原子整体质量 | 误认为违反能量守恒 |
| 线性衰减系数 | 单位长度的衰减能力 | 材料、密度、光子能量 | 与质量衰减系数混淆 |

---

## 二十八、本章公式分级卡

### A 级：必须直接默写

#### 1. 光子能量与动量

```math
\boxed{
E=h\nu=\frac{hc}{\lambda}
}
```

```math
\boxed{
p=\frac h\lambda=\frac Ec
}
```

#### 2. 布拉格公式

```math
\boxed{
2d\sin\theta=n\lambda
}
```

#### 3. 连续谱短波限

```math
\boxed{
eU=\frac{hc}{\lambda_{\min}}
}
```

快捷形式：

```math
\boxed{
\lambda_{\min}(\mathrm{nm})
=
\frac{1.24}{U(\mathrm{kV})}
}
```

#### 4. 康普顿公式

```math
\boxed{
\lambda'-\lambda
=
\frac{h}{m_ec}(1-\cos\theta)
}
```

#### 5. 指数衰减公式

```math
\boxed{
I=I_0e^{-\mu x}
}
```

### B 级：必须理解并会使用

#### 1. 散射光子能量

```math
\boxed{
E'
=
\frac{E}
{1+\dfrac{E}{m_ec^2}(1-\cos\theta)}
}
```

#### 2. 最大反冲电子动能

```math
\boxed{
T_{\max}
=
\frac{2E^2}
{m_ec^2+2E}
}
```

#### 3. 半值层

```math
\boxed{
x_{1/2}=\frac{\ln2}{\mu}
}
```

#### 4. 特征谱能量

```math
\boxed{
E_{K_\alpha}=B_K-B_L
}
```

```math
\boxed{
E_{K_\beta}=B_K-B_M
}
```

#### 5. 莫塞莱定律

```math
\boxed{
\sqrt{\nu}=A(Z-\sigma)
}
```

对 $K_\alpha$ 线：

```math
\boxed{
\nu_{K_\alpha}
\approx
0.248\times10^{16}(Z-1)^2\,\mathrm{Hz}
}
```

### C 级：理解来源即可

#### 总衰减系数

```math
\mu_{\text{总}}
=
\mu_{\text{光电}}
+
\mu_{\text{康普顿}}
+
\mu_{\text{电子对}}.
```

#### 质量衰减形式

```math
I
=
I_0
\exp
\left[
-\frac{\mu}{\rho}\rho x
\right].
```

#### 俄歇电子近似能量

```math
E_{\mathrm{Auger}}
\approx
B_K-B_L-B_M.
```

---

## 二十九、本章必须记住的常数

| 常数 | 数值 | 主要用途 |
|---|---:|---|
| $hc$ | $1240\,\mathrm{eV\cdot nm}$ | 波长与光子能量转换 |
| $hc$ | $1.24\,\mathrm{keV\cdot nm}$ | X 射线计算最方便 |
| 电子静止能 $m_ec^2$ | $511\,\mathrm{keV}$ | 康普顿散射、电子对产生 |
| 电子康普顿波长 $h/(m_ec)$ | $2.426\,\mathrm{pm}$ | 康普顿波长改变量 |
| 电子对产生阈值 | $1.022\,\mathrm{MeV}$ | 判断能否产生正负电子对 |
| $1\,\text{\AA}$ | $0.1\,\mathrm{nm}$ | X 射线常用长度换算 |
| $\ln2$ | $0.693$ | 半值层计算 |

其中最值得闭卷背诵的是：

```math
\boxed{
hc=1240\,\mathrm{eV\cdot nm}
}
```

```math
\boxed{
m_ec^2=511\,\mathrm{keV}
}
```

```math
\boxed{
\lambda_C=2.426\,\mathrm{pm}
}
```

---

## 三十、常见题型与标准解题流程

### 题型一：X 射线管连续谱

题目给：

- 管电压；
- 最短波长；
- 最大光子能量。

统一使用：

```math
eU=E_{\max}=\frac{hc}{\lambda_{\min}}.
```

快速判断：

- $U$ 增大， $\lambda_{\min}$ 减小；
- 管电流改变，不影响 $\lambda_{\min}$ ；
- 靶材改变，不影响 $\lambda_{\min}$ 。

### 题型二：布拉格衍射

步骤：

1. 判断给的是 $\theta$ 还是 $2\theta$ ；
2. 确定衍射级次 $n$ ；
3. 代入 $2d\sin\theta=n\lambda$ ；

4. 必要时再使用 $E=\frac{hc}{\lambda}$ ；

5. 检查是否满足 $\sin\theta\leq1$ 。

### 题型三：特征谱与吸收限

先画出结合能关系：

```math
B_K\gt B_L\gt B_M.
```

再写：

```math
E_{K_\alpha}=B_K-B_L.
```

```math
E_{K,\text{edge}}=B_K.
```

绝不能把 $K_\alpha$ 光子能量直接写成 $B_K$ 。

### 题型四：康普顿波长变化

若已知散射角，直接用：

```math
\Delta\lambda
=
\lambda_C(1-\cos\theta).
```

再计算：

```math
\lambda'=\lambda+\Delta\lambda.
```

若要求电子动能：

```math
T
=
\frac{hc}{\lambda}
-
\frac{hc}{\lambda'}.
```

### 题型五：康普顿能量极值

看到“散射光子能量最小”或“电子动能最大”，立即判断：

```math
\theta=180^\circ.
```

然后使用：

```math
E'_{\min}
=
\frac{E}{1+2E/(m_ec^2)}.
```

### 题型六：X 射线衰减

使用：

```math
I=I_0e^{-\mu x}.
```

常见变式如下。

#### 求厚度

```math
x
=
\frac1\mu
\ln\frac{I_0}{I}.
```

#### 求半值层

```math
x_{1/2}
=
\frac{0.693}{\mu}.
```

#### 多层材料

若依次通过多种材料：

```math
I
=
I_0
e^{-\mu_1x_1}
e^{-\mu_2x_2}
\cdots
```

即：

```math
\boxed{
I
=
I_0
e^{-(\mu_1x_1+\mu_2x_2+\cdots)}
}
```

---

## 三十一、高频失分点

### 31.1 把布拉格角写错

错误：

> 直接把入射线和衍射线之间的夹角代入 $\sin\theta$ 。

正确：

> 若仪器读数是两条射线夹角 $2\theta$ ，应先除以 $2$ 。

### 31.2 认为连续谱短波限由靶材决定

错误：

> 换成重元素靶，最短波长变短。

正确：

```math
\lambda_{\min}=\frac{hc}{eU}
```

只由管电压决定。

### 31.3 认为提高管电压会移动特征峰

错误：

> 电压越大， $K_\alpha$ 峰波长越短。

正确：

> 超过临界电压后，特征峰位置主要由靶材决定，管电压主要影响强度。

### 31.4 把 K 吸收限与 $K_\alpha$ 线混为一谈

正确关系：

```math
E_{K,\text{edge}}=B_K,
```

```math
E_{K_\alpha}=B_K-B_L.
```

### 31.5 康普顿公式忘记 $1-\cos\theta$

尤其容易误写为：

```math
\sin\theta
\quad\text{或}\quad
1-\sin\theta.
```

正确是：

```math
\boxed{1-\cos\theta}.
```

### 31.6 把康普顿波长与最大波长改变量混淆

电子康普顿波长：

```math
\lambda_C=\frac{h}{m_ec}.
```

最大波长改变量：

```math
\Delta\lambda_{\max}=2\lambda_C.
```

### 31.7 非相对论处理高能反冲电子

康普顿公式的严格推导必须使用：

```math
E_e^2=P^2c^2+m_e^2c^4.
```

不能在普遍情况下直接使用：

```math
T=\frac{P^2}{2m_e}.
```

只有反冲电子速度远低于光速时，后者才是近似。

### 31.8 误以为衰减一定是线性的

错误：

```math
I=I_0-\mu x.
```

正确：

```math
I=I_0e^{-\mu x}.
```

因为越往后剩余光子越少，单位厚度能够继续损失的光子数也越少。

---

## 三十二、本章核心因果链

```math
\begin{aligned}
&\text{高速电子撞击金属靶}\\
&\quad\downarrow\\
&\begin{cases}
\text{电子减速}
\rightarrow
\text{轫致辐射}
\rightarrow
\text{连续谱和短波限},\\[2mm]
\text{内层电子被击出}
\rightarrow
\text{产生空穴}
\rightarrow
\text{外层电子跃迁}
\rightarrow
\text{特征谱}.
\end{cases}\\
&\quad\downarrow\\
&\text{特征谱随 }Z\text{ 变化}
\rightarrow
\text{莫塞莱定律}
\rightarrow
\text{确定原子序数}\\
&\quad\downarrow\\
&\text{X 射线通过晶体}
\rightarrow
\text{布拉格衍射}
\rightarrow
\text{证明波动性}\\
&\quad\downarrow\\
&\text{X 射线与电子碰撞}
\rightarrow
\text{康普顿效应}
\rightarrow
\text{证明光子动量}\\
&\quad\downarrow\\
&\text{X 射线通过物质}
\rightarrow
\text{光电、康普顿、电子对效应}
\rightarrow
\text{指数衰减与吸收限}.
\end{aligned}
```

---

## 三十三、必须理解的五个模型

### 模型一：晶体是天然光栅

晶格间距与 X 射线波长同数量级，因此能发生衍射。

### 模型二：电子减速产生连续谱

电子能以任意比例损失动能，所以光子能量连续；单个光子最多获得 $eU$ 。

### 模型三：内层空穴产生特征谱

空穴一旦形成，外层电子以分立能量跃迁，产生元素特有的 X 射线。

### 模型四：光子与自由电子发生相对论碰撞

康普顿散射本质是光子和电子之间的能量、动量交换。

### 模型五：光子穿过物质具有固定衰减概率

每一薄层都使当前剩余光子减少固定比例，因此得到指数衰减。

---

## 三十四、闭卷自测问题

1. 为什么研究 X 射线衍射必须用晶体，而不能用普通机械光栅？
2. 布拉格公式中的 $\theta$ 是哪两个方向之间的夹角？
3. 为什么 X 射线连续谱既是连续的，又存在一个最短波长？
4. 管电压、管电流和靶材分别影响 X 射线谱的哪些特征？
5. $K_\alpha$ 、 $K_\beta$ 、 $L_\alpha$ 分别对应什么跃迁？
6. 为什么特征谱的位置基本不随管电压改变？
7. 莫塞莱定律为什么含有 $Z-\sigma$ ，而不是简单的 $Z$ ？
8. 康普顿效应中，为什么散射后的光子波长变长？
9. 康普顿波长与最大康普顿波长改变量有什么区别？
10. 为什么康普顿波长改变量与入射波长无关？
11. 为什么康普顿实验中还会出现波长不变的散射成分？
12. 光电效应、康普顿散射和电子对产生的物理过程有何区别？
13. 为什么 X 射线强度随厚度按指数规律衰减，而不是线性衰减？
14. K 吸收限和 $K_\alpha$ 特征线分别代表什么能量？
15. 为什么吸收系数随光子能量变化时会在某些位置突然跳跃？
16. 一束 X 射线通过两个半值层后，强度变为原来的多少？

第 16 题答案：

```math
\frac{I}{I_0}
=
\left(
\frac12
\right)^2
=
\frac14.
```

---

## 三十五、考前最后一分钟口诀

> **晶体衍射看波性，布拉格式记 $2d\sin\theta=n\lambda$ ；**
> **电子刹车成连续谱，短波极限只看管电压；**
> **内层空穴出特征谱，谱线位置主要看原子序数；**
> **康普顿碰撞守恒量，波长变化记 $1-\cos\theta$ ；**
> **穿过物质指数衰减，吸收限就是内层电离门槛。**
