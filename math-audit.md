# Math Rendering Audit



---

<!-- notes/00-course-overview.md -->

# 原子物理复习总纲

> **用户原始要求**
>
> 参照review.pdf来给我梳理复习思路，一定要比源文件更详细

这本《原子物理学》的目录其实很清楚。整门课的主线可以概括成一句话：

> **从“原子是什么样子”出发，经过“原子为什么稳定、为什么发光”，进入“电子的量子态、自旋和多电子结构”，最后扩展到 X 射线和原子核。**

原子物理位于经典物理和量子物理之间；其真正任务是：

> **用实验事实逼迫我们放弃经典图像，并逐步建立量子图像。**

### 一、这门课程究竟在研究什么

原子物理研究的是：

- 原子的内部结构；
- 原子中电子的运动状态；
- 原子的能级与光谱；
- 原子在外场中的行为；
- 多电子之间的耦合与排布；
- 光子与物质的相互作用。

整门课程不是六章彼此孤立的内容，而是一条不断升级的理论链：

```math
\text{核式结构}
\rightarrow
\text{分立能级}
\rightarrow
\text{波函数}
\rightarrow
\text{自旋与精细结构}
\rightarrow
\text{多电子与周期律}
```

同时，X 射线与康普顿散射从另一条线说明：

```math
\text{光不仅有波动性，也具有能量和动量}
```

这门课的学习任务分为两部分：

1. 建立物理图像，理解实验现象、理论模型和模型之间的因果关系；
2. 掌握核心公式，并能完成必要的计算、判断与推导。

---

### 二、整门课程的核心问题链

#### 1. 原子内部的正电荷和质量怎样分布

第一章通过 $\alpha$ 粒子散射回答：

> 原子的正电荷和绝大部分质量集中在非常小的原子核中，原子绝大部分空间是空的。

这一章解决的是原子的“空间结构”。

#### 2. 电子为什么不会坠入原子核

卢瑟福模型按照经典理论会导致原子坍塌，也无法解释分立的原子光谱。

第二章通过玻尔模型引入：

- 定态；
- 角动量量子化；
- 能级；
- 跃迁。

这一章解决的是原子的“能量结构”。

#### 3. 电子的所谓“轨道”到底是什么

玻尔模型仍然把电子看成沿确定圆轨道运动，但它存在许多硬性规定。

第三章引入：

- 德布罗意波；
- 波函数；
- 概率解释；
- 不确定关系；
- 薛定谔方程；
- 量子数。

这一章完成从“经典轨道”到“量子态”的转变。

#### 4. 为什么谱线还会出现精细分裂

即使氢原子没有原子实极化和轨道贯穿，谱线仍然会出现精细结构。

第四章引入：

- 电子自旋；
- 轨道磁矩和自旋磁矩；
- 总角动量；
- 朗德因子；
- 自旋—轨道耦合；
- 塞曼效应。

#### 5. 多个电子怎样共同运动

第五章讨论：

- 电子组态；
- $L-S$ 耦合与 $j-j$ 耦合；
- 泡利不相容原理；
- 洪特规则；
- 元素周期表。

#### 6. 光子与电子碰撞时会发生什么

第六章重点讨论 X 射线和康普顿散射，说明光子具有确定的能量和动量：

```math
E=h\nu,
\qquad
p=\frac{h}{\lambda}
```

---

### 三、整门课程的知识地图

| 层次 | 核心问题 | 对应章节 | 最终得到什么 |
|---|---|---|---|
| 原子内部有什么 | 正电荷和质量怎样分布 | 第一章 卢瑟福模型 | 核式原子模型、散射截面 |
| 为什么光谱是分立的 | 电子为什么不会坠入原子核 | 第二章 玻尔模型 | 能级、跃迁、氢光谱 |
| “轨道”到底是什么 | 微观粒子怎样描述 | 第三章 量子力学初步 | 波函数、概率、薛定谔方程、量子数 |
| 谱线为什么还有细分裂 | 电子是否还有额外自由度 | 第四章 精细结构 | 自旋、总角动量、磁矩、塞曼效应 |
| 多个电子怎样共同运动 | 多电子能级为何呈周期性 | 第五章 多电子原子 | 耦合、泡利原理、洪特规则、周期表 |
| 光子与电子怎样碰撞 | X 射线的粒子性如何验证 | 第六章 X 射线 | 康普顿散射、光子能量和动量 |

---

### 四、三次最重要的认知转变

#### 第一次：从“均匀原子”到“核式原子”

汤姆逊模型认为正电荷分布在整个原子范围内。

卢瑟福散射实验发现：

- 大多数粒子几乎不偏转；
- 少数粒子发生大角散射；
- 极少数粒子几乎反向弹回。

这说明原子内部绝大部分空间是空的，正电荷和质量集中在很小的原子核中。

#### 第二次：从“连续轨道”到“分立能级”

卢瑟福模型按照经典电动力学会导致：

- 电子不断辐射；
- 电子能量连续减小；
- 电子最终落入原子核；
- 原子应发射连续光谱。

实验却表明原子稳定，而且光谱是线状的。

玻尔因此提出定态和能级跃迁。

#### 第三次：从“电子沿轨道运动”到“波函数描述状态”

现代量子力学不再追问电子沿哪一条确定轨道运动，而是研究：

- 波函数；
- 粒子在各处出现的概率；
- 某物理量可能的测量值；
- 测量结果的概率分布。

---

### 五、复习优先级

#### 第一优先级：必须会算、会画、会解释

- 卢瑟福散射公式和实验计数；
- 类氢原子的半径、速度、能量和跃迁波长；
- 德布罗意波长；
- 波函数概率解释和无限深势阱；
- 氢原子的三个空间量子数；
- 角动量耦合和原子态符号；
- 朗德因子和塞曼分裂；
- 康普顿波长改变公式。

#### 第二优先级：必须建立清楚的物理图像

- 汤姆逊模型为什么失败；
- 玻尔模型为什么既成功又不完整；
- 弗兰克—赫兹实验；
- 史特恩—盖拉赫实验；
- 碱金属双线；
- 正常与反常塞曼效应；
- 泡利不相容原理和洪特规则；
- 康普顿散射中为什么同时出现原波长和变长成分。

#### 第三优先级：知道结论和适用条件

- 玻尔—索末菲修正；
- $j-j$ 耦合；
- 帕邢—巴克效应；
- 同科电子原子态筛选；
- X 射线产生、吸收和布拉格衍射。

---

## 六、各章核心结构

### 第一章：卢瑟福模型

#### 核心问题

如何通过散射实验反推出原子内部的电荷分布？

#### 核心逻辑

```math
\text{电子被发现}
\rightarrow
\text{汤姆逊模型}
\rightarrow
\alpha\text{ 粒子散射异常}
\rightarrow
\text{汤姆逊模型失败}
\rightarrow
\text{卢瑟福核式模型}
```

#### 核心公式

```math
a=
\frac{Z_1Z_2e^2}
{4\pi\varepsilon_0E}
```

```math
b=\frac{a}{2}\cot\frac{\theta}{2}
```

```math
\frac{d\sigma}{d\Omega}
=
\frac{a^2}
{16\sin^4(\theta/2)}
```

```math
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega
```

### 第二章：玻尔模型

#### 核心问题

原子为什么稳定？原子为什么发射分立光谱？

#### 核心逻辑

```math
\text{卢瑟福模型的困难}
\rightarrow
\text{量子概念}
\rightarrow
\text{玻尔三个假设}
\rightarrow
r_n,v_n,E_n
\rightarrow
\text{里德伯公式}
```

#### 核心公式

```math
L=\mu vr=n\hbar
```

```math
r_n=
a_0\frac{m_e}{\mu}\frac{n^2}{Z}
```

```math
v_n=\frac{Z\alpha c}{n}
```

```math
E_n=
-\frac{\mu}{m_e}
13.6\frac{Z^2}{n^2}\,\mathrm{eV}
```

```math
h\nu=|E_i-E_f|
```

```math
\frac{1}{\lambda}
=
R_MZ^2
\left(
\frac{1}{n_f^2}
-
\frac{1}{n_i^2}
\right)
```

### 第三章：量子力学初步

#### 核心逻辑

```math
\text{波粒二象性}
\rightarrow
\text{德布罗意波}
\rightarrow
\text{波函数}
\rightarrow
\text{概率解释}
\rightarrow
\text{薛定谔方程}
\rightarrow
\text{量子数}
```

#### 核心公式

```math
\lambda=\frac{h}{p}
```

```math
\int_{\text{全空间}}|\psi|^2d\tau=1
```

```math
\Delta x\,\Delta p_x\geq\frac{\hbar}{2}
```

```math
i\hbar\frac{\partial\psi}{\partial t}
=
\hat H\psi
```

### 第四章：精细结构和电子自旋

#### 核心逻辑

```math
\text{轨道角动量}
\rightarrow
\text{轨道磁矩}
\rightarrow
\text{史特恩—盖拉赫实验}
\rightarrow
\text{电子自旋}
\rightarrow
\mathbf J=\mathbf L+\mathbf S
\rightarrow
\text{塞曼效应}
```

#### 核心公式

```math
\boldsymbol\mu_L
=
-\frac{e}{2m_e}\mathbf L
```

```math
\mu_B=\frac{e\hbar}{2m_e}
```

```math
g_J
=
1+
\frac{
J(J+1)+S(S+1)-L(L+1)
}{
2J(J+1)
}
```

```math
\Delta E=g_Jm_J\mu_BB
```

### 第五章：多电子原子

#### 核心逻辑

```math
\text{电子组态}
\rightarrow
\text{角动量耦合}
\rightarrow
\text{泡利原理}
\rightarrow
\text{洪特规则}
\rightarrow
\text{周期表}
```

需要重点区分电子组态和原子态，并掌握原子态符号：

```math
^{2S+1}L_J
```

### 第六章：X 射线

#### 核心公式

```math
2d\sin\theta=n\lambda
```

```math
eU=\frac{hc}{\lambda_{\min}}
```

```math
\Delta\lambda
=
\lambda'-\lambda
=
\frac{h}{m_ec}(1-\cos\theta)
```

---

## 七、四棵公式树

### 公式树一：库仑相互作用

```math
V(r)\propto\frac{1}{r},
\qquad
F(r)\propto\frac{1}{r^2}
```

由此产生：

- 卢瑟福散射；
- 玻尔轨道；
- 类氢原子能级；
- 氢原子薛定谔方程。

### 公式树二：量子关系

```math
E=h\nu,
\qquad
p=\hbar k=\frac{h}{\lambda}
```

由此产生：

- 光电效应；
- 德布罗意波；
- 康普顿散射；
- 平面波；
- 能量和动量算符。

### 公式树三：角动量量子化

```math
J^2=j(j+1)\hbar^2,
\qquad
J_z=m_j\hbar
```

由此产生：

- 空间量子化；
- 电子自旋；
- 角动量耦合；
- 原子态符号；
- 磁场中能级分裂。

### 公式树四：磁矩与外场

```math
\Delta E=-\boldsymbol\mu\cdot\mathbf B
```

由此产生：

- 轨道磁矩；
- 自旋磁矩；
- 朗德因子；
- 史特恩—盖拉赫实验；
- 塞曼效应；
- 帕邢—巴克效应。

---

## 八、常见题型的标准思路

### 题型一：实验为什么推翻旧理论

固定回答结构：

1. 旧理论预测什么；
2. 实验观察到什么；
3. 两者矛盾在哪里；
4. 新理论引入什么概念；
5. 新理论怎样解释现象。

### 题型二：类氢原子计算

1. 判断核电荷数 $Z$ ；
2. 判断是否需要约化质量；
3. 写出 $r_n$ 、 $v_n$ 、 $E_n$ ；
4. 判断求的是结合能、激发能还是电离能；
5. 使用 $\Delta E=hc/\lambda$ 求光子；
6. 检查 $Z$ 和 $n$ 的标度是否合理。

### 题型三：散射计数

```math
\rho,t,M
\rightarrow
n_t
\rightarrow
\sigma\text{ 或 }\frac{d\sigma}{d\Omega}
\rightarrow
\Delta\Omega
\rightarrow
N_{\mathrm{det}}
```

### 题型四：原子态枚举

```math
l_1,l_2
\rightarrow
L
```

```math
s_1,s_2
\rightarrow
S
```

```math
L,S
\rightarrow
J
```

```math
^{2S+1}L_J
```

### 题型五：塞曼分裂

1. 写出初末态的 $L$ 、 $S$ 、 $J$ ；
2. 计算 $g_J$ ；
3. 列出所有 $m_J$ ；
4. 计算能级移动；
5. 使用 $\Delta m_J=0,\pm1$ ；
6. 合并频率相同的跃迁；
7. 判断 $\pi$ 线和 $\sigma$ 线。

---

## 九、四轮复习法

### 第一轮：搭建章节骨架

每章回答：

- 实验事实是什么；
- 旧理论有什么困难；
- 新理论引入什么概念；
- 核心公式有哪些；
- 模型的适用条件和局限是什么。

### 第二轮：打通公式来源

重点推导：

1. 卢瑟福 $b-\theta$ 关系和散射截面；
2. 玻尔半径、速度和能量；
3. 里德伯公式；
4. 无限深势阱；
5. 角动量合成；
6. 朗德因子的使用；
7. 康普顿公式中的守恒关系。

### 第三轮：使用作业训练

建议顺序：

1. Homework 1：卢瑟福散射概率和计数；
2. Homework 2 第 1 题：类氢体系；
3. Homework 2 第 2 题：同位素位移；
4. Homework 2 第 3 题：介子原子与有限核尺寸；
5. Homework 3 第 1 题：史特恩—盖拉赫实验；
6. Homework 3 第 0、2 题：塞曼效应和 Na 双线。

每做完一道题，写三行总结：

- 这题属于哪个模型；
- 最容易错在哪里；
- 改变一个条件后结论如何变化。

### 第四轮：闭卷输出

1. 画课程总知识图；
2. 写出全部量子数及其取值；
3. 画氢原子、碱金属、精细结构和塞曼分裂能级图；
4. 默写核心公式；
5. 用自己的话解释关键实验。

---

## 十、最终复习策略

这门课最容易陷入两个极端：

- 只背实验故事，不会计算；
- 只背公式，不知道公式在描述什么。

对每个知识点都应当问：

1. 它由什么实验提出？
2. 它解决了什么矛盾？
3. 它的核心数学关系是什么？
4. 它在哪些条件下失效？

整门课程可以概括为：

```math
\boxed{
\text{实验发现异常}
\rightarrow
\text{旧模型失效}
\rightarrow
\text{提出新模型}
\rightarrow
\text{得到能级和量子数}
\rightarrow
\text{再用实验检验}
}
```


---

<!-- notes/01-rutherford-model.md -->

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

典型动能为几个 $\mathrm{MeV}$ 。

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
- 大多数散射角小于约 $2^\circ$ ；
- 少量粒子发生大角散射；
- 约每数千个粒子中有一个散射角大于 $90^\circ$ ；
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

这远小于实验中的 $90^\circ$ 甚至 $180^\circ$ 。

多次随机小角散射的典型累积满足：

```math
\theta_{\mathrm{rms}}
\sim
\sqrt{N}\,\delta\theta
```

而不是 $N\delta\theta$ ，因此也不能稳定累积成反向散射。

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

若几乎正对原子核入射，即 $b\approx0$ ，粒子会受到强烈反向斥力。

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

> 一个电荷为 $Z_1e$ 、动能为 $E$ 的粒子，在静止的 $Z_2e$ 点电荷库仑场中运动。

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

## 十二、 $b-\theta$ 关系的推导思路

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

- $b$ 越小， $\theta$ 越大；
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

若 $b=100\,\mathrm{fm}$ ，则 $\theta\approx16.9^\circ$ ；若 $b=1000\,\mathrm{fm}$ ，则 $\theta\approx1.7^\circ$ 。

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

此时 $b=14.8\,\mathrm{fm}$ ，说明 $b$ 与 $r_{\min}$ 不相等。

若实验在最近距离 $r_{\min}$ 处仍符合点电荷散射，只能推出：

```math
R_{\mathrm{核}}\lt r_{\min}
```

因此最近接距离给出的是核半径上限。

---

## 十八、为什么需要散射截面

$b-\theta$ 关系描述单个粒子轨迹，但实验不能测量每个粒子的 $b$ 。

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

若小探测器面积为 $S$ ，距散射点为 $R$ ，且正对散射点：

```math
\boxed{
\Delta\Omega\approx\frac{S}{R^2}
}
```

若探测器法线与粒子方向夹角为 $\beta$ ：

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

高频错误是把公式误写成 $\sin^4\theta$ 。正确分母是：

```math
\sin^4\frac{\theta}{2}
```

---

## 二十四、从截面计算实验计数

设：

- 入射粒子总数为 $N_0$ ；
- 靶的面原子数密度为 $n_t$ ；
- 探测器立体角为 $\Delta\Omega$ 。

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

若探测效率为 $\eta$ ：

```math
N_{\mathrm{det}}
=
N_0n_t
\frac{d\sigma}{d\Omega}
\Delta\Omega\,\eta
```

若靶的质量密度为 $\rho$ 、厚度为 $t$ 、摩尔质量为 $M$ ：

```math
\boxed{
n_t
=
\frac{\rho tN_A}{M}
}
```

若每秒入射粒子数为 $I$ ，测量时间为 $T$ ：

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
\sigma(\theta\gt \theta_0)
=
\int_{\theta_0}^{\pi}
\frac{d\sigma}{d\Omega}
d\Omega
```

结果：

```math
\boxed{
\sigma(\theta\gt \theta_0)
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

所有 $b\lt b_0$ 的粒子都会有 $\theta\gt \theta_0$ ，因此：

```math
\sigma=\pi b_0^2
```

特别地：

```math
\boxed{
\sigma(\theta\gt 90^\circ)
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
\sigma_{\gt 90^\circ}
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

例：把金靶 $Z=79$ 换成铝靶 $Z=13$ ，同时把能量降为原来一半：

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
P=n_t\sigma(\theta\gt \theta_0)
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
\sigma(\theta\gt \theta_0)
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

1. 把 $\sin^4(\theta/2)$ 错写成 $\sin^4\theta$ ；
2. 把截面直接当概率，忘记乘靶面密度；
3. 把微分截面当总截面，忘记乘立体角；
4. 把 $b$ 当成最近接距离；
5. 把 $197\,\mathrm{g/mol}$ 直接当成 $197\,\mathrm{kg/mol}$ ；
6. 忘记 $1\,\mu\mathrm m=10^{-6}\,\mathrm m$ ；
7. 概率换成百分数时少乘或多乘 $100$ ；
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
5. $b$ 、 $\theta$ 、 $r_{\min}$ 分别是什么？
6. 为什么 $b$ 越小， $\theta$ 越大？
7. 参数 $a$ 的物理意义是什么？
8. 为什么要从 $b$ 转换到散射截面？
9. 微分截面和概率有什么区别？
10. 为什么计数公式要乘靶面密度？
11. 为什么散射率与 $Z^2/E^2$ 有关？
12. 为什么小角区域受到电子屏蔽修正？
13. 最近接距离为什么只能给出核半径上限？
14. 卢瑟福模型为什么不是完整原子理论？


---

<!-- notes/02-bohr-model.md -->

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
n_i\gt n_f
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
E_n\lt 0
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

其中 $n_f\gt n_i$ 。

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
n_i\gt n_f
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
M_D\gt M_H
```

所以：

```math
\mu_D\gt \mu_H
```

有限质量里德伯常数：

```math
R_M
=
R_\infty\frac{\mu}{m_e}
```

因此：

```math
R_D\gt R_H
```

同一跃迁满足：

```math
\frac{1}{\lambda}\propto R_M
```

所以：

```math
\boxed{
\lambda_D\lt \lambda_H
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
s\gt p\gt d\gt f
}
```

相同主量子数下通常：

```math
E_{ns}\lt E_{np}\lt E_{nd}\lt E_{nf}
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
\delta_s\gt \delta_p\gt \delta_d\gt \delta_f\approx0
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
r_1=2.36\,\mathrm{fm}\lt R_N=7.1\,\mathrm{fm}
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


---

<!-- notes/03-introduction-to-quantum-mechanics.md -->

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


---

<!-- notes/04-fine-structure-and-electron-spin.md -->

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


---

<!-- notes/05-multi-electron-atoms-and-pauli-principle.md -->

---
title: 原子物理第五章：多电子原子与泡利原理
aliases:
  - 第五章 多电子原子
  - 泡利原理
tags:
  - 原子物理
  - 期末复习
  - 多电子原子
  - 泡利不相容原理
---

# 第五章 多电子原子：泡利原理

本章从单电子原子进入真正的多电子体系，主要讨论：

1. 氦原子的光谱和能级；
2. 两个电子的角动量耦合；
3. 泡利不相容原理；
4. 电子组态、洪特定则与元素周期表。

本章公式不算特别多，但概念层级多、符号多、状态计数容易混乱。考试最常见的任务包括：

- 根据电子组态列出可能的原子态；
- 由 $L,S$ 求 $J$ ；
- 正确书写光谱项符号；
- 用泡利原理删去不允许的状态；
- 用洪特定则判断基态；
- 用朗德间隔定则判断精细结构间隔；
- 写出元素的基态电子组态。

---

## 一、本章到底解决什么问题

### 1. 一句话概括

> 当原子中有两个或更多电子时，电子之间怎样相互作用、怎样占据量子态，又怎样共同决定原子的能级、光谱和元素周期性？

前几章的问题相对简单：

- 氢原子只有一个电子；
- 类氢离子也只有一个电子；
- 碱金属虽然有许多电子，但常可近似成“封闭原子实 + 一个价电子”。

而一般原子中，电子不但受到原子核吸引，还彼此排斥。于是总势能中出现

```math
\frac{e^2}{4\pi\varepsilon_0 r_{12}}.
```

电子 1 的位置会影响电子 2 受到的作用，电子 2 的位置也会反过来影响电子 1。两个电子不能再被完全分开处理。

### 2. 本章核心因果链

```math
\text{单电子原子}
\rightarrow
\text{加入第二个电子}
\rightarrow
\text{出现电子—电子库仑排斥}
```

```math
\rightarrow
\text{单电子量子数不足以描述整个原子}
\rightarrow
\text{各电子的轨道角动量、自旋角动量发生耦合}
```

```math
\rightarrow
\text{形成总轨道角动量 }L\text{、总自旋 }S\text{、总角动量 }J
```

```math
\rightarrow
\text{同一电子组态分裂成多个原子态}
\rightarrow
\text{泡利原理限制哪些状态能够存在}
```

```math
\rightarrow
\text{洪特定则决定哪一个状态最低}
\rightarrow
\text{电子依次填充形成元素周期表}.
```

因此，本章的逻辑不是简单地“多几个电子”，而是：

> 电子数增加以后，出现了相互作用、全同性、交换对称性和状态占据规则。

---

## 二、多电子原子为什么比氢原子难

### 1. 氢原子的哈密顿量

氢原子只有一个电子：

```math
H=
-\frac{\hbar^2}{2m_e}\nabla^2
-\frac{Ze^2}{4\pi\varepsilon_0 r}.
```

电子只受到中心力作用，薛定谔方程可以严格分离变量求解，能量主要由主量子数 $n$ 决定。

### 2. 氦原子的哈密顿量

氦原子核电荷为 $+2e$ ，有两个电子。忽略原子核运动时：

```math
\boxed{
H=
-\frac{\hbar^2}{2m_e}\nabla_1^2
-\frac{\hbar^2}{2m_e}\nabla_2^2
-\frac{2e^2}{4\pi\varepsilon_0 r_1}
-\frac{2e^2}{4\pi\varepsilon_0 r_2}
+\frac{e^2}{4\pi\varepsilon_0 r_{12}}
}
```

前四项分别是两个电子的动能及原子核对两个电子的吸引；最后一项

```math
\boxed{
\frac{e^2}{4\pi\varepsilon_0 r_{12}}
}
```

是两个电子之间的库仑排斥能。

### 3. 真正的困难在哪里

如果没有电子—电子作用，总波函数可以写成两个单电子波函数的乘积：

```math
\Psi(\mathbf r_1,\mathbf r_2)
=
\psi_a(\mathbf r_1)\psi_b(\mathbf r_2).
```

但加入 $1/r_{12}$ 后，电子 1 和电子 2 的坐标被耦合在一起，不能再把两者完全独立处理。

更准确的图像是：

> 每个电子都在原子核和其他电子共同形成的平均势场中运动，同时电子之间还存在超出平均场的关联。

### 4. 屏蔽和有效核电荷

每个电子受到原子核吸引，但其他电子会屏蔽一部分核电荷，故价电子实际感受到的有效核电荷满足

```math
Z_{\mathrm{eff}}\lt Z.
```

必须区分：

- 裸核电荷： $Z$ ；
- 电子实际感受到的有效核电荷： $Z_{\mathrm{eff}}$ 。

内层电子屏蔽越强，外层电子通常束缚得越弱。

---

## 三、例题：忽略电子间作用计算氦原子基态

忽略电子间排斥后，把两个电子都看成在 $Z=2$ 的类氢势场中独立运动。

类氢离子的能级为

```math
E_n=-13.6\frac{Z^2}{n^2}\ \mathrm{eV}.
```

基态中两个电子都取 $n=1$ ，单个电子能量为

```math
E_1=-13.6\times2^2=-54.4\ \mathrm{eV}.
```

两个电子的总能量为

```math
\boxed{
E_{\mathrm{He}}^{(0)}=2E_1=-108.8\ \mathrm{eV}
}
```

氦原子失去一个电子后变成 $\mathrm{He}^+$ ，其基态能量为

```math
E_{\mathrm{He}^+}=-54.4\ \mathrm{eV}.
```

因此该近似预测的第一电离能为

```math
I_1^{(0)}
=(-54.4)-(-108.8)
=54.4\ \mathrm{eV}.
```

实验值约为

```math
I_1=24.6\ \mathrm{eV}.
```

误差很大。原因是忽略电子排斥，相当于让每个电子完整感受到 $Z=2$ 的核吸引，导致电子被估计得过于牢固。

氦原子的实际总结合能约为

```math
24.6+54.4=79.0\ \mathrm{eV},
```

故实际基态能量约为

```math
\boxed{
E_{\mathrm{He}}\approx-79.0\ \mathrm{eV}
}
```

与简单近似相比，能量被抬高约

```math
(-79.0)-(-108.8)=29.8\ \mathrm{eV}.
```

这一差异主要来自电子—电子排斥及其引起的波函数调整。

### 方法总结

看到“忽略电子间相互作用”的题，应当：

1. 把每个电子看成独立的类氢电子；
2. 分别计算单电子能量；
3. 对所有电子求和；
4. 电离能用“末态总能量减初态总能量”；
5. 与实验比较时，指出忽略电子排斥会使束缚能估计过大。

---

## 四、氦原子光谱的特殊结构

氦是最简单的二电子原子，但已经出现单电子原子中没有的新现象：

- 氦有单重态和三重态两套能级、两套近似独立的光谱；
- 三重态对应能级通常低于相应单重态；
- $2^3S_1$ 和 $2^1S_0$ 是亚稳态；
- 氦基态为 $1^1S_0$ ；
- 第一激发能约为 $19.82\,\mathrm{eV}$ ；
- 第一电离能约为 $24.59\,\mathrm{eV}$ 。

### 1. 氦原子的基态组态

两个电子都进入最低的 $1s$ 轨道：

```math
\boxed{
1s^2
}
```

因为

```math
l_1=l_2=0,
```

总轨道角动量只能为

```math
L=0.
```

最终基态为

```math
\boxed{
1s^2\ {}^1S_0
}
```

而不存在

```math
1s^2\ {}^3S_1.
```

### 2. 氦的普通低激发态

通常一个电子留在 $1s$ ，另一个电子被激发到 $2s,2p,3s,3p,\ldots$ ，例如

```math
1s2s,\qquad1s2p,\qquad1s3s,\qquad1s3p.
```

这些组态中的两个电子可以形成

```math
S=0
```

或

```math
S=1,
```

于是出现单重态和三重态两套结构。

---

## 五、两个电子的自旋怎样合成

每个电子的自旋量子数均为

```math
s_1=s_2=\frac12.
```

两个角动量的合成规则为

```math
S=s_1+s_2,\ s_1+s_2-1,\ldots,|s_1-s_2|,
```

所以

```math
\boxed{
S=1\quad\text{或}\quad S=0
}
```

### 1. $S=1$ ：三重态

当 $S=1$ 时，

```math
M_S=1,0,-1.
```

共有三个自旋状态，因此称为三重态：

```math
\boxed{
2S+1=3
}
```

三个自旋波函数为

```math
\chi_{1,1}=\uparrow\uparrow,
```

```math
\chi_{1,0}
=
\frac{1}{\sqrt2}
\left(
\uparrow\downarrow+
\downarrow\uparrow
\right),
```

```math
\chi_{1,-1}=\downarrow\downarrow.
```

交换两个电子后不变，因此是对称自旋波函数。

### 2. $S=0$ ：单重态

当 $S=0$ 时，只能有 $M_S=0$ ：

```math
\boxed{
\chi_{0,0}
=
\frac{1}{\sqrt2}
\left(
\uparrow\downarrow-
\downarrow\uparrow
\right)
}
```

只有一个状态，因此

```math
\boxed{
2S+1=1
}
```

交换两个电子后波函数变号，所以是反对称自旋波函数。

### 3. 高频易错点

三重态并不等于“两个电子都同向”。三重态还包括

```math
\frac{\uparrow\downarrow+\downarrow\uparrow}{\sqrt2}.
```

真正决定单重态或三重态的是总自旋量子数 $S$ ，不是简单观察箭头方向。

---

## 六、为什么氦有两套近似独立的光谱

电偶极跃迁算符主要作用于空间坐标，不直接改变自旋，因此有选择定则

```math
\boxed{
\Delta S=0
}
```

所以：

- 单重态通常只能跃迁到单重态；
- 三重态通常只能跃迁到三重态；
- 单重态和三重态之间的跃迁被禁戒。

于是氦原子产生单重态系统和三重态系统两套近似独立的光谱。

历史上也称：

- 单重态氦：仲氦或 parahelium；
- 三重态氦：正氦或 orthohelium。

它们不是两种不同元素，而是同一个氦原子的两类量子态。

---

## 七、为什么三重态通常低于相应单重态

### 1. 错误解释

错误说法是：

> 两个自旋平行的电子磁性相吸，所以三重态能量较低。

电子自旋磁矩之间的直接磁相互作用很弱，不是主要原因。

### 2. 正确原因：交换效应

电子是全同费米子，总波函数交换两个电子时必须变号：

```math
\Psi_{\mathrm{总}}
=
\Psi_{\mathrm{空间}}
\chi_{\mathrm{自旋}}.
```

#### 单重态

单重态自旋波函数反对称，因此空间波函数必须对称：

```math
\Psi_+
=
\frac{1}{\sqrt2}
\left[
\phi_a(1)\phi_b(2)
+
\phi_a(2)\phi_b(1)
\right].
```

#### 三重态

三重态自旋波函数对称，因此空间波函数必须反对称：

```math
\Psi_-
=
\frac{1}{\sqrt2}
\left[
\phi_a(1)\phi_b(2)
-
\phi_a(2)\phi_b(1)
\right].
```

当 $\mathbf r_1=\mathbf r_2$ 时，三重态的反对称空间波函数趋于零，意味着两个电子更不容易同时出现在同一位置附近，平均距离更大，库仑排斥较小，因此能量较低。

### 3. 直接积分和交换积分

简单近似下：

```math
E_{\text{单重态}}=E_0+J+K,
```

```math
E_{\text{三重态}}=E_0+J-K,
```

其中 $J$ 是直接库仑积分， $K$ 是交换积分。于是

```math
E_{\text{单}}-E_{\text{三}}=2K\gt 0,
```

故

```math
\boxed{
E_{\text{三重态}}\lt E_{\text{单重态}}
}
```

交换能不是一种额外的经典力，而是电子全同性、波函数交换对称性与库仑相互作用共同产生的量子效应。

---

## 八、亚稳态为什么寿命特别长

亚稳态是指：向更低能级的主要电偶极跃迁被选择定则禁止，只能通过更弱过程衰变，因而寿命远长于普通激发态。

普通允许跃迁寿命常在 $10^{-8}\,\mathrm s$ 量级，而亚稳态可能达到毫秒、秒甚至数千秒。

### 1. $2^3S_1$ 为什么寿命很长

基态为

```math
1^1S_0.
```

跃迁

```math
2^3S_1\rightarrow1^1S_0
```

要求总自旋从 $S=1$ 变为 $S=0$ ，即

```math
\Delta S=1,
```

违反电偶极跃迁的 $\Delta S=0$ 。此外， $S\rightarrow S$ 也不满足通常的轨道选择规则，所以该态高度禁戒。

### 2. $2^1S_0$ 为什么也是亚稳态

跃迁

```math
2^1S_0\rightarrow1^1S_0
```

虽然满足 $\Delta S=0$ ，但属于

```math
J=0\rightarrow J=0
```

且两态宇称相同，单光子电偶极跃迁被禁止，只能通过双光子等较弱过程衰变。

---

## 九、电子组态、光谱项和能级

### 1. 电子组态

电子按 $n,l$ 分布的方式称为电子组态，例如

```math
1s^2,\qquad1s2p,\qquad2p^2,\qquad3s3p.
```

组态说明电子分布在哪些亚壳层，但尚未说明角动量如何耦合。

### 2. 光谱项

同一组态下，不同电子角动量可以形成不同的 $L,S$ ，用

```math
\boxed{
{}^{2S+1}L
}
```

表示一个光谱项。

例如 $1s2p$ 可以形成

```math
{}^1P,\qquad{}^3P.
```

### 3. 精细结构能级

加入自旋—轨道耦合后，每个光谱项按 $J$ 分裂：

```math
\boxed{
{}^{2S+1}L_J
}
```

例如

```math
{}^3P
\rightarrow
{}^3P_0,\ {}^3P_1,\ {}^3P_2.
```

### 4. 磁子能级

加入外磁场后，同一 $J$ 能级再按

```math
M_J=-J,-J+1,\ldots,J
```

分裂。

层级关系为

```math
\boxed{
\text{电子组态}
\rightarrow
\text{光谱项 }{}^{2S+1}L
\rightarrow
\text{精细结构能级 }{}^{2S+1}L_J
\rightarrow
\text{磁子能级 }M_J
}
```

---

## 十、主壳层、亚壳层和轨道

### 1. 主壳层

主量子数相同的电子属于同一主壳层：

```math
n=1,2,3,\ldots
```

| $n$ | 壳层 |
|---:|---|
| 1 | K |
| 2 | L |
| 3 | M |
| 4 | N |

一个主壳层最多容纳

```math
\boxed{
2n^2
}
```

个电子。

### 2. 亚壳层

同一 $n$ 中， $l$ 相同的状态构成同一亚壳层：

```math
l=0,1,2,3,\ldots
```

分别记作 $s,p,d,f,\ldots$ 。

一个 $l$ 亚壳层中有 $2l+1$ 个不同的 $m_l$ 轨道，每个轨道最多容纳两个自旋相反的电子，所以亚壳层最多容纳

```math
\boxed{
2(2l+1)
}
```

个电子。

| 亚壳层 | $l$ | 轨道数 | 最大电子数 |
|---|---:|---:|---:|
| $s$ | 0 | 1 | 2 |
| $p$ | 1 | 3 | 6 |
| $d$ | 2 | 5 | 10 |
| $f$ | 3 | 7 | 14 |

### 3. 推导主壳层容量

对固定 $n$ ：

```math
l=0,1,\ldots,n-1.
```

总空间轨道数为

```math
\sum_{l=0}^{n-1}(2l+1)=n^2.
```

每个空间轨道可放两个自旋不同的电子，因此

```math
\boxed{
N_{\max}=2n^2
}
```

---

## 十一、两个电子的 $L-S$ 耦合

对较轻原子，先把所有电子的轨道角动量合成为

```math
\mathbf L=\sum_i\mathbf l_i,
```

把所有电子的自旋角动量合成为

```math
\mathbf S=\sum_i\mathbf s_i,
```

再合成

```math
\boxed{
\mathbf J=\mathbf L+\mathbf S
}
```

这叫罗素—桑德斯耦合或 $L-S$ 耦合。

### 1. 总自旋 $S$

对两个电子：

```math
s_1=s_2=\frac12,
```

所以

```math
\boxed{
S=0,1
}
```

对应单重态和三重态。

### 2. 总轨道角动量 $L$

```math
\boxed{
L=l_1+l_2,\ l_1+l_2-1,\ldots,|l_1-l_2|
}
```

例如一个 $p$ 电子和一个 $d$ 电子：

```math
l_1=1,\qquad l_2=2,
```

故

```math
L=3,2,1,
```

分别对应 $F,D,P$ 。

### 3. 总角动量 $J$

```math
\boxed{
J=L+S,L+S-1,\ldots,|L-S|
}
```

当 $S=0$ 时， $J=L$ ；当 $S=1$ 且 $L\ge1$ 时，通常有

```math
J=L+1,L,L-1.
```

但若 $L=0,S=1$ ，则只能有 $J=1$ ，所以“多重度为 3”不等于“一定有三个 $J$ 能级”。

---

## 十二、原子态符号

原子态写作

```math
\boxed{
{}^{2S+1}L_J
}
```

其中：

- 左上角 $2S+1$ ：多重度；
- 中间字母 $L$ ：总轨道角动量；
- 右下角 $J$ ：总角动量。

| $L$ | 0 | 1 | 2 | 3 | 4 | 5 |
|---:|---|---|---|---|---|---|
| 符号 | S | P | D | F | G | H |

例如

```math
{}^3D_2
```

表示

```math
S=1,\qquad L=2,\qquad J=2.
```

而

```math
{}^2P_{3/2}
```

表示

```math
S=\frac12,\qquad L=1,\qquad J=\frac32.
```

---

## 十三、典型例题： $pd$ 组态的原子态

求一个 $p$ 电子和一个 $d$ 电子在 $L-S$ 耦合下可形成的原子态。

### 第一步：总自旋

```math
S=0,1.
```

### 第二步：总轨道角动量

```math
l_p=1,\qquad l_d=2,
```

所以

```math
L=3,2,1,
```

对应 $F,D,P$ 。

### 第三步：列单重态

当 $S=0$ 时， $J=L$ ：

```math
\boxed{
{}^1P_1,\quad{}^1D_2,\quad{}^1F_3
}
```

### 第四步：列三重态

当 $S=1$ 时：

```math
{}^3P_{0,1,2},
```

```math
{}^3D_{1,2,3},
```

```math
{}^3F_{2,3,4}.
```

因此全部原子态为

```math
\boxed{
{}^1P_1,\ {}^1D_2,\ {}^1F_3,\
{}^3P_{0,1,2},\
{}^3D_{1,2,3},\
{}^3F_{2,3,4}
}
```

共 12 个精细结构能级。

### 微观状态数验算

一个 $p$ 电子有 6 个单电子状态，一个 $d$ 电子有 10 个，因此总微观状态数为

```math
6\times10=60.
```

单重态贡献：

```math
1(3+5+7)=15.
```

三重态贡献：

```math
3(3+5+7)=45.
```

合计

```math
15+45=60.
```

验算正确。

---

## 十四、 $j-j$ 耦合

对较重原子，自旋—轨道相互作用较强，每个电子先形成

```math
\mathbf j_1=\mathbf l_1+\mathbf s_1,
```

```math
\mathbf j_2=\mathbf l_2+\mathbf s_2,
```

再合成

```math
\boxed{
\mathbf J=\mathbf j_1+\mathbf j_2
}
```

这叫 $j-j$ 耦合。

### 耦合次序对比

#### $L-S$ 耦合

```math
\mathbf l_1+\mathbf l_2=\mathbf L,
```

```math
\mathbf s_1+\mathbf s_2=\mathbf S,
```

```math
\mathbf L+\mathbf S=\mathbf J.
```

#### $j-j$ 耦合

```math
\mathbf l_1+\mathbf s_1=\mathbf j_1,
```

```math
\mathbf l_2+\mathbf s_2=\mathbf j_2,
```

```math
\mathbf j_1+\mathbf j_2=\mathbf J.
```

现实原子还可能处在两种极限之间，称为中间耦合。

---

## 十五、泡利不相容原理

### 1. 原理内容

> 一个原子中不能有两个电子处于完全相同的量子状态。

单电子状态由四个量子数标记：

```math
n,\quad l,\quad m_l,\quad m_s.
```

所以任意两个电子不能同时具有完全相同的

```math
\boxed{
n,l,m_l,m_s
}
```

所有电子都有 $s=\tfrac12$ ，所以 $s$ 本身不能区分不同电子，真正起区分作用的是 $n,l,m_l,m_s$ 。

### 2. 更深层表述

电子属于费米子。全同费米子系统的总波函数交换任意两个电子后必须变号：

```math
\boxed{
\Psi(1,2)=-\Psi(2,1)
}
```

若两个电子处于完全相同的单粒子状态，交换前后波函数既应相同又应变号，只能得到

```math
\Psi=0.
```

因此这种状态不存在。

泡利原理不是一种普通经典斥力，而是费米子多体波函数反对称性对允许状态施加的根本限制。

---

## 十六、泡利原理怎样解释氦基态

氦基态组态为

```math
1s^2.
```

两个电子都有

```math
n=1,\qquad l=0,\qquad m_l=0.
```

前三个量子数已经相同，因此 $m_s$ 必须不同：

```math
m_{s1}=+\frac12,\qquad m_{s2}=-\frac12.
```

更严格地说，它们必须组成反对称的单重态 $S=0$ 。因此氦基态只能是

```math
\boxed{
1s^2\ {}^1S_0
}
```

而不能是

```math
1s^2\ {}^3S_1.
```

---

## 十七、同科电子和非同科电子

### 1. 同科电子

具有相同 $n,l$ 的电子称为同科电子或等价电子，例如

```math
2p^2,\qquad3d^3,\qquad4f^2.
```

### 2. 非同科电子

$n$ 或 $l$ 不同的电子称为非同科电子，例如

```math
2p3p,\qquad2p3d,\qquad1s2s.
```

对非同科电子，普通角动量合成得到的状态通常都可以存在；对同科电子，泡利原理会删去一部分状态。

---

## 十八、同科 $p^2$ 电子的允许状态

若暂时忽略泡利限制，两个 $p$ 电子有

```math
l_1=l_2=1,
```

所以

```math
L=2,1,0,
```

而

```math
S=1,0.
```

表面上可形成

```math
{}^1S,\ {}^1P,\ {}^1D,\ {}^3S,\ {}^3P,\ {}^3D.
```

但对同科 $p^2$ 电子，泡利原理只允许

```math
\boxed{
{}^1S,\qquad{}^1D,\qquad{}^3P
}
```

进一步加上 $J$ ：

```math
\boxed{
{}^1S_0,\qquad
{}^1D_2,\qquad
{}^3P_0,\ {}^3P_1,\ {}^3P_2
}
```

### 对称性解释

- $L=0,2$ 的空间部分对称；
- $L=1$ 的空间部分反对称。

总波函数必须反对称。

当 $S=0$ 时，自旋部分反对称，所以空间部分必须对称，允许 $L=0,2$ ，即 ${}^1S,{}^1D$ 。

当 $S=1$ 时，自旋部分对称，所以空间部分必须反对称，只允许 $L=1$ ，即 ${}^3P$ 。

### 状态数验算

$p$ 亚壳层共有 6 个单电子状态，从中选 2 个：

```math
\binom62=15.
```

允许项的状态数为

```math
{}^1S:\ 1,
```

```math
{}^1D:\ 5,
```

```math
{}^3P:\ 9.
```

合计

```math
1+5+9=15.
```

---

## 十九、同科电子的常见结论

### 1. $s^2$

```math
\boxed{
s^2\rightarrow{}^1S_0
}
```

### 2. $p^2$

```math
\boxed{
p^2\rightarrow{}^3P,\ {}^1D,\ {}^1S
}
```

### 3. $p^3$

```math
\boxed{
p^3\rightarrow{}^4S,\ {}^2D,\ {}^2P
}
```

其中

```math
{}^4S_{3/2}
```

满足

```math
S=\frac32,\qquad L=0,\qquad J=\frac32.
```

### 4. 满壳层

例如

```math
s^2,\qquad p^6,\qquad d^{10},\qquad f^{14}.
```

所有 $m_l$ 和 $m_s$ 成对填满，因此

```math
\boxed{
L=0,\quad S=0,\quad J=0
}
```

对应

```math
\boxed{
{}^1S_0
}
```

---

## 二十、洪特定则

泡利原理决定哪些状态允许存在，洪特定则判断允许状态中哪一个能量最低。

### 第一定则：总自旋最大的能级最低

```math
\boxed{
S_{\max}\Rightarrow E_{\min}
}
```

直观上，自旋尽量平行时，由于总波函数反对称，空间部分使电子更相互避开，从而降低平均库仑排斥能。

### 第二定则：同一 $S$ 下， $L$ 最大的最低

```math
\boxed{
L_{\max}\Rightarrow E_{\min}
}
```

### 第三定则：确定最低 $J$

#### 少于半满

```math
\boxed{
J_{\min}=|L-S|
}
```

#### 多于半满

```math
\boxed{
J_{\max}=L+S
}
```

#### 恰好半满

通常最大 $S$ ，且常有 $L=0$ 。

---

## 二十一、例题：碳和硅的基态原子态

碳的基态电子组态为

```math
1s^22s^22p^2.
```

闭壳层 $1s^22s^2$ 的 $L=S=0$ ，只需分析 $2p^2$ 。

允许项为

```math
{}^3P,\qquad{}^1D,\qquad{}^1S.
```

洪特第一定则选最大 $S$ ，所以最低项为 ${}^3P$ 。

$p$ 亚壳层半满为 3 个电子， $p^2$ 少于半满，所以取最小 $J$ ：

```math
J_{\min}=|L-S|=|1-1|=0.
```

因此碳基态为

```math
\boxed{
2p^2\ {}^3P_0
}
```

硅的价电子组态为 $3p^2$ ，同理：

```math
\boxed{
3p^2\ {}^3P_0
}
```

---

## 二十二、例题：氮原子的基态原子态

氮的价电子组态为

```math
2p^3.
```

允许项包括

```math
{}^4S,\qquad{}^2D,\qquad{}^2P.
```

洪特第一定则选最大 $S$ 。 ${}^4S$ 中

```math
2S+1=4
\Rightarrow
S=\frac32,
```

高于双重态的 $S=\tfrac12$ ，故最低项是 ${}^4S$ 。

由于 $L=0$ ，所以

```math
J=S=\frac32.
```

因此氮基态为

```math
\boxed{
2p^3\ {}^4S_{3/2}
}
```

---

## 二十三、例题：氧原子的基态原子态

氧的价电子组态为

```math
2p^4.
```

$p^4$ 与 $p^2$ 具有相同的 $L,S$ 项：

```math
{}^3P,\qquad{}^1D,\qquad{}^1S.
```

洪特第一定则仍选 ${}^3P$ 。但 $p^4$ 多于半满，因此洪特第三定则取最大 $J$ ：

```math
J_{\max}=L+S=1+1=2.
```

所以氧基态为

```math
\boxed{
2p^4\ {}^3P_2
}
```

这正体现：

- 少于半满取最小 $J$ ；
- 多于半满取最大 $J$ 。

---

## 二十四、空穴等价法

满 $p$ 亚壳层为 $p^6$ ，因此：

- $p^5$ 相当于一个空穴；
- $p^4$ 相当于两个空穴。

在允许的 $L,S$ 项方面：

```math
p^5\leftrightarrow p^1,
```

```math
p^4\leftrightarrow p^2.
```

所以 $p^4$ 与 $p^2$ 具有相同的光谱项集合，但洪特第三定则给出的 $J$ 排序相反。

---

## 二十五、朗德间隔定则

### 1. 适用范围

只适用于：

- $L-S$ 耦合较好；
- 同一个 ${}^{2S+1}L$ 光谱项；
- 不同 $J$ 精细结构能级之间。

不能用于比较不同组态或不同 $L,S$ 项。

### 2. 自旋—轨道能量

```math
H_{SO}=A\,\mathbf L\cdot\mathbf S.
```

利用

```math
\mathbf L\cdot\mathbf S
=
\frac12
\left(
\mathbf J^2-\mathbf L^2-\mathbf S^2
\right),
```

可得

```math
\boxed{
E_J=
E_0+
\frac A2
\left[
J(J+1)-L(L+1)-S(S+1)
\right]
}
```

比较相邻 $J$ 与 $J-1$ ：

```math
\boxed{
E_J-E_{J-1}=AJ
}
```

这就是朗德间隔定则：相邻 $J$ 能级的间隔正比于较大的那个 $J$ 。

### 3. ${}^3P_J$ 示例

```math
L=1,\qquad S=1,\qquad J=0,1,2.
```

有

```math
E_1-E_0=A,
```

```math
E_2-E_1=2A.
```

所以

```math
\boxed{
\Delta E_{1,0}:\Delta E_{2,1}=1:2
}
```

### 4. ${}^3D_J$ 示例

```math
L=2,\qquad S=1,\qquad J=1,2,3.
```

所以

```math
\boxed{
\Delta E_{2,1}:\Delta E_{3,2}=2:3
}
```

---

## 二十六、多电子原子的跃迁选择定则

在 $L-S$ 耦合下，电偶极跃迁常用选择定则为

```math
\boxed{
\Delta S=0
}
```

```math
\boxed{
\Delta L=0,\pm1
}
```

但

```math
L=0\not\leftrightarrow L'=0.
```

同时

```math
\boxed{
\Delta J=0,\pm1
}
```

但

```math
J=0\not\leftrightarrow J'=0.
```

磁量子数满足

```math
\boxed{
\Delta M_J=0,\pm1
}
```

电偶极跃迁还要求宇称改变。

“禁戒”不等于绝对不发生，而是最低阶电偶极跃迁矩阵元为零。真实原子仍可能通过磁偶极、电四极、双光子、自旋—轨道混合或外场扰动发生跃迁，只是概率更小。

---

## 二十七、电子填充的三条基本规则

### 1. 能量最低原理

基态电子优先占据能量较低的轨道。

多电子原子中轨道能量不仅由 $n$ 决定，还受穿透、屏蔽、电子排斥和交换作用影响。

### 2. 泡利不相容原理

一个轨道由 $n,l,m_l$ 确定，每个轨道最多容纳两个自旋相反的电子：

```math
\uparrow\downarrow.
```

### 3. 洪特规则

在简并轨道中：

- 先每个轨道放一个电子；
- 单占电子自旋尽量平行；
- 然后才开始配对。

例如 $p^3$ 应写成

```math
\uparrow\qquad\uparrow\qquad\uparrow.
```

---

## 二十八、轨道能量的经验次序

常用马德隆规则或 $n+l$ 规则：

1. $n+l$ 较小者先填；
2. 若 $n+l$ 相同， $n$ 较小者先填。

例如

```math
4s:\quad n+l=4,
```

```math
3d:\quad n+l=5,
```

所以开始填充时通常 $4s$ 先于 $3d$ 。

常用顺序：

```math
\boxed{
1s\lt 2s\lt 2p\lt 3s\lt 3p\lt 4s\lt 3d\lt 4p\lt 5s\lt 4d\lt 5p
}
```

继续为

```math
6s\lt 4f\lt 5d\lt 6p\lt 7s\lt 5f\lt 6d\lt 7p.
```

### 填充顺序不等于电离顺序

虽然中性原子常先填 $4s$ 后填 $3d$ ，但过渡金属形成离子时通常先失去 $4s$ 电子。

例如

```math
\mathrm{Fe}:[\mathrm{Ar}]3d^64s^2,
```

形成 $\mathrm{Fe}^{2+}$ 时通常为

```math
[\mathrm{Ar}]3d^6.
```

---

## 二十九、常见反常组态

### 1. 铬

机械填充似乎得到

```math
[\mathrm{Ar}]3d^44s^2,
```

实际为

```math
\boxed{
\mathrm{Cr}:[\mathrm{Ar}]3d^54s^1
}
```

### 2. 铜

机械填充似乎得到

```math
[\mathrm{Ar}]3d^94s^2,
```

实际为

```math
\boxed{
\mathrm{Cu}:[\mathrm{Ar}]3d^{10}4s^1
}
```

半满或全满亚壳层因交换能等因素相对稳定。

---

## 三十、元素周期表为什么具有周期性

元素周期性来自电子组态的周期性重复。

- 第一周期填充 $1s$ ，长度为 2；
- 第二周期填充 $2s,2p$ ，长度为 $2+6=8$ ；
- 第三周期主要填充 $3s,3p$ ，长度为 8；
- 第四周期填充 $4s,3d,4p$ ，长度为 $2+10+6=18$ ；
- 第六周期填充 $6s,4f,5d,6p$ ，长度为 $2+14+10+6=32$ 。

### 周期表分区

| 分区 | 最后填入亚壳层 | 容量 |
|---|---|---:|
| $s$ 区 | $ns$ | 2 |
| $p$ 区 | $np$ | 6 |
| $d$ 区 | $(n-1)d$ | 10 |
| $f$ 区 | $(n-2)f$ | 14 |

同族元素具有相似的最外层电子组态，因此化学性质相似。

例如：

- 碱金属： $ns^1$ ；
- 卤素： $ns^2np^5$ ；
- 稀有气体： $ns^2np^6$ ，氦例外为 $1s^2$ 。

---

## 三十一、公式分级卡

### A 级：必须直接写出

#### 两个角动量合成

```math
\boxed{
j=j_1+j_2,\ j_1+j_2-1,\ldots,|j_1-j_2|
}
```

#### 两电子总自旋

```math
\boxed{
S=0,1
}
```

#### 总轨道角动量

```math
\boxed{
L=l_1+l_2,\ldots,|l_1-l_2|
}
```

#### 总角动量

```math
\boxed{
J=L+S,\ldots,|L-S|
}
```

#### 原子态符号

```math
\boxed{
{}^{2S+1}L_J
}
```

#### 亚壳层容量

```math
\boxed{
N_l=2(2l+1)
}
```

#### 主壳层容量

```math
\boxed{
N_n=2n^2
}
```

#### 朗德间隔定则

```math
\boxed{
E_J-E_{J-1}=AJ
}
```

### B 级：必须理解并会使用

#### 电子排斥项

```math
\boxed{
V_{12}=
\frac{e^2}{4\pi\varepsilon_0r_{12}}
}
```

#### 自旋—轨道能量

```math
\boxed{
E_J=
E_0+
\frac A2
[J(J+1)-L(L+1)-S(S+1)]
}
```

#### 电偶极选择定则

```math
\boxed{
\Delta S=0,\qquad
\Delta L=0,\pm1,\qquad
\Delta J=0,\pm1
}
```

并排除

```math
L=0\leftrightarrow0,
\qquad
J=0\leftrightarrow0.
```

### C 级：理解来源即可

- 氦原子的完整哈密顿量；
- 交换积分 $K$ 的具体积分形式；
- 同科电子允许项的系统推导；
- 复杂组态的全部微观态展开；
- 中间耦合的矩阵对角化。

---

## 三十二、本章值得记住的数值

| 数值 | 用途 |
|---|---|
| $13.6\,\mathrm{eV}$ | 氢原子里德伯能量 |
| $54.4\,\mathrm{eV}$ | $\mathrm{He}^+$ 基态电离能 |
| $24.6\,\mathrm{eV}$ | 氦原子第一电离能 |
| $19.82\,\mathrm{eV}$ | 氦原子第一激发能量级 |
| $s=\tfrac12$ | 任意电子的自旋量子数 |

---

## 三十三、高频失分点

### 1. 把电子组态当成原子态

$2p^2$ 是电子组态，可以形成

```math
{}^3P,\ {}^1D,\ {}^1S
```

多个光谱项，基态才是 ${}^3P_0$ 。

### 2. 忘记左上角是 $2S+1$

例如

```math
{}^3P_2
```

表示 $S=1$ ，不是 $S=3$ 。

### 3. 求 $J$ 时只写 $L+S$

正确范围是

```math
J=L+S,L+S-1,\ldots,|L-S|.
```

### 4. 认为三重态一定有三个 $J$ 能级

${}^3S$ 中 $L=0,S=1$ ，只能有 $J=1$ 。

### 5. 对同科电子不使用泡利限制

同科 $p^2$ 只能形成

```math
{}^1S,\quad{}^1D,\quad{}^3P.
```

### 6. 认为一上一下必然是单重态

```math
\frac{1}{\sqrt2}
(\uparrow\downarrow+\downarrow\uparrow)
```

属于三重态；带减号的组合才属于单重态。

### 7. 洪特第三定则前忘记判断半满

- $p$ 半满：3；
- $d$ 半满：5；
- $f$ 半满：7。

### 8. 把朗德间隔定则用于不同光谱项

它只能比较同一个 ${}^{2S+1}L$ 项中的相邻 $J$ 能级。

### 9. 认为 $4s$ 永远低于 $3d$

中性原子开始填充时常先填 $4s$ ，但形成过渡金属离子时通常先失去 $4s$ 电子。

### 10. 把禁戒理解为绝对不发生

禁戒表示最低阶跃迁概率很小，不是绝对不发生。

---

## 三十四、常见题型与解题流程

### 题型一：由两个非同科电子列原子态

1. 由轨道字母读出 $l_1,l_2$ ；
2. 求 $L=l_1+l_2,\ldots,|l_1-l_2|$ ；
3. 对两个电子写 $S=0,1$ ；
4. 对每组 $L,S$ 求全部 $J$ ；
5. 写成 ${}^{2S+1}L_J$ ；
6. 用微观状态数验算。

### 题型二：同科电子允许项

1. 先列普通角动量耦合可能；
2. 判断是否同科；
3. 用泡利原理删去不允许项；
4. 熟记：

```math
s^2\rightarrow{}^1S_0,
```

```math
p^2\rightarrow{}^3P,\ {}^1D,\ {}^1S,
```

```math
p^3\rightarrow{}^4S,\ {}^2D,\ {}^2P.
```

### 题型三：判断基态原子态

1. 写基态电子组态；
2. 去掉闭壳层，只看未满亚壳层；
3. 列允许的 $L,S$ 项；
4. 洪特第一定则取最大 $S$ ；
5. 洪特第二定则取最大 $L$ ；
6. 判断少于还是多于半满；
7. 用洪特第三定则确定 $J$ 。

### 题型四：朗德间隔定则

1. 确认属于同一 ${}^{2S+1}L$ 项；
2. 列出全部 $J$ ；
3. 使用 $E_J-E_{J-1}=AJ$ ；
4. 写出间隔比例；
5. 倒转次序只改变上下顺序，不改变间隔绝对值比例。

### 题型五：电子组态填充

1. 按 $n+l$ 规则确定大致顺序；
2. 使用亚壳层容量；
3. 使用泡利原理；
4. 使用洪特规则；
5. 检查 Cr、Cu 等常见例外；
6. 形成离子时注意通常先移走 $4s$ 。

---

## 三十五、本章核心因果链总结

```math
\text{多个电子}
\Rightarrow
\text{电子间库仑排斥}
\Rightarrow
\text{单电子能级图不再充分}
```

```math
\Rightarrow
\text{角动量耦合}
\Rightarrow
L,S,J
\Rightarrow
{}^{2S+1}L_J
```

```math
\text{电子全同性}
\Rightarrow
\text{总波函数反对称}
\Rightarrow
\text{泡利不相容原理}
```

```math
\Rightarrow
\text{同科电子允许态减少}
\Rightarrow
\text{洪特定则选基态}
```

```math
\Rightarrow
\text{电子组态周期性}
\Rightarrow
\text{元素周期表与化学性质周期性}.
```

---

## 三十六、必须理解的模型

1. **平均场与屏蔽模型**
   每个电子在原子核和其他电子形成的平均势场中运动。

2. **角动量耦合模型**
   轻原子常用 $L-S$ 耦合，重原子更接近 $j-j$ 耦合。

3. **全同费米子模型**
   电子不可区分，总波函数必须反对称。

4. **交换效应模型**
   三重态较低不是经典磁吸引，而是空间反对称性降低电子重叠和排斥。

5. **电子填充模型**
   能量最低、泡利原理和洪特规则共同决定基态电子组态。

---

## 三十七、闭卷自测

1. 为什么氦原子不能像氢原子一样严格分离求解？
2. 氦哈密顿量中 $1/r_{12}$ 表示什么？
3. 忽略电子排斥时，为什么会高估氦的第一电离能？
4. 电子组态、光谱项、精细结构能级有什么区别？
5. 两个电子的总自旋为什么只能取 $S=0,1$ ？
6. 单重态和三重态的自旋波函数分别具有什么交换对称性？
7. 为什么三重态通常比相应单重态低？
8. 为什么单重态和三重态之间跃迁通常禁戒？
9. $2^3S_1$ 为什么是亚稳态？
10. 一个 $p$ 电子和一个 $d$ 电子可形成哪些原子态？
11. ${}^3D_2$ 中 $S,L,J$ 分别是多少？
12. $L-S$ 耦合和 $j-j$ 耦合的耦合顺序分别是什么？
13. 泡利不相容原理的四量子数表述是什么？
14. 为什么氦基态没有 $1s^2\,{}^3S_1$ ？
15. 两个同科 $p$ 电子为什么只能形成 ${}^1S,{}^1D,{}^3P$ ？
16. $s,p,d,f$ 亚壳层分别最多容纳多少电子？
17. 怎样由亚壳层容量推导主壳层容量 $2n^2$ ？
18. 洪特三条定则分别是什么？
19. 为什么碳基态为 ${}^3P_0$ ，氧基态却为 ${}^3P_2$ ？
20. 氮原子 $2p^3$ 的基态为什么是 ${}^4S_{3/2}$ ？
21. 朗德间隔定则怎样推导？
22. ${}^3P_J$ 的相邻间隔比是多少？
23. 为什么 $4s$ 先填充，却常在形成离子时先失去？
24. 铬和铜的反常电子组态分别是什么？
25. 元素周期表的周期性为什么本质上是电子组态的周期性？

---

## 结论

> 电子组态说明电子放在哪里，角动量耦合说明它们怎样组成原子态，泡利原理决定哪些状态允许存在，洪特定则决定其中哪一个是基态。


---

<!-- notes/06-x-rays.md -->

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
