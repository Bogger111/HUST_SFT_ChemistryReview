# 例题

## Section 1 *热力学概念*

### E1
设有一电炉丝浸于水中，接上电源，通以电流一段时间。如果按以下几种情况作为系统，试问
$Q$、$W$、$\Delta U$ 为正、为负还是为零？

1. 以水为系统；
2. 以电炉丝和水为系统；
3. 以电炉丝、水、电源以及其他一切有影响的部分为系统。

<details>
<summary>Answer</summary>

1. $Q>0,\ W=0,\ \Delta U>0$
2. $Q=0,\ W>0,\ \Delta U>0$
3. $Q=0,\ W=0,\ \Delta U=0$

</details>

### E2
一体系由 $A$ 态变化到 $B$ 态，沿途径 I 放热 $100\ \mathrm{J}$，对体系做功
$50\ \mathrm{J}$。

1. 由 $A$ 态沿途径 II 到 $B$ 态，体系做功 $80\ \mathrm{J}$，则过程 $Q$ 值为多少？
2. 如果体系再由 $B$ 态沿途径 III 回到 $A$ 态，得到 $50\ \mathrm{J}$ 的功，体系是吸热还是放热，$Q$ 值是多少？

<details>
<summary>Answer</summary>

途径 I：

$$
Q=-100\ \mathrm{J},\qquad W=50\ \mathrm{J}
$$

$$
\Delta U_{A\rightarrow B}=Q+W=-100+50=-50\ \mathrm{J}
$$

1. 体系做功 $80\ \mathrm{J}$，即 $W=-80\ \mathrm{J}$：

$$
Q=\Delta U-W=-50-(-80)=30\ \mathrm{J}
$$

2. 返回过程：

$$
\Delta U_{B\rightarrow A}=50\ \mathrm{J}
$$

体系得到 $50\ \mathrm{J}$ 的功，即 $W=50\ \mathrm{J}$：

$$
Q=\Delta U-W=50-50=0
$$

</details>

### E3
在 $101.3\ \mathrm{kPa}$ 和 $100^\circ\mathrm{C}$ 条件下，反应：

$$
\mathrm{H_2(g)}+\frac{1}{2}\mathrm{O_2(g)}=\mathrm{H_2O(g)}
$$

的 $\Delta H=-241.8\ \mathrm{kJ\cdot mol^{-1}}$，求 $\Delta U$。

<details>
<summary>Answer</summary>

恒温、恒压过程中：

$$
\Delta H=\Delta U+p\Delta V
$$

对理想气体：

$$
p\Delta V=\Delta n_gRT
$$

$$
\Delta n_g=1-\left(1+\frac{1}{2}\right)=-0.5
$$

$$
\Delta U=\Delta H-\Delta n_gRT
$$

$$
\Delta U
=-241.8-\left[(-0.5)(8.314\times10^{-3})(373)\right]
=-240.3\ \mathrm{kJ\cdot mol^{-1}}
$$

</details>

### E4
$1\ \mathrm{mol}$ 柠檬酸（固体）在 $298\ \mathrm{K}$ 恒容燃烧放热
$1989.7\ \mathrm{kJ}$。计算 $10\ \mathrm{g}$ 固体柠檬酸在
$298\ \mathrm{K}$ 恒压下燃烧时放出的热。

<details>
<summary>Answer</summary>

柠檬酸燃烧反应式为：

$$
\mathrm{C_6H_8O_7(s)}+\frac{9}{2}\mathrm{O_2(g)}
=6\mathrm{CO_2(g)}+4\mathrm{H_2O(l)}
$$

$$
\Delta n_g=6-\frac{9}{2}=1.5
$$

恒容燃烧热：

$$
\Delta U=-1989.7\ \mathrm{kJ\cdot mol^{-1}}
$$

恒压燃烧热：

$$
\Delta H=\Delta U+\Delta n_gRT
$$

$$
\Delta H
=-1989.7+1.5\times(8.314\times10^{-3})\times298
=-1986.0\ \mathrm{kJ\cdot mol^{-1}}
$$

柠檬酸摩尔质量 $M=192\ \mathrm{g\cdot mol^{-1}}$：

$$
q_p=\frac{10\ \mathrm{g}}{192\ \mathrm{g\cdot mol^{-1}}}
\times(-1986.0\ \mathrm{kJ\cdot mol^{-1}})
=-103.4\ \mathrm{kJ}
$$

即放出热量 $103.4\ \mathrm{kJ}$。

</details>

### E5
1. $1.00\ \mathrm{mol}$ 水在 $373\ \mathrm{K}$、$p=101325\ \mathrm{Pa}$ 下蒸发为理想气体，吸热 $2259\ \mathrm{J\cdot g^{-1}}$。问此过程的 $Q_1$、$W_1$，以及水的 $\Delta U_1$ 和 $\Delta H_1$。
2. 始态同 1，当外界压力恒定为 $0.5p$ 时，将水蒸发，然后将此 $0.5p$、$373\ \mathrm{K}$ 的水气恒温可逆压缩为 $p$、$373\ \mathrm{K}$ 的水气，求此过程的 $Q_2$、$W_2$，以及水的 $\Delta U_2$ 和 $\Delta H_2$。
3. 将 $1.00\ \mathrm{mol}$ 水在 $373\ \mathrm{K}$、$p$ 下突然放在 $373\ \mathrm{K}$ 的真空箱中，水气立即充满整个真空箱（水全部汽化），测其压力为 $p$，求该过程的 $Q_3$、$W_3$，以及水的 $\Delta U_3$ 和 $\Delta H_3$。
4. 比较 1、2、3 的结果，可总结出哪些结论？

已知 $M(\mathrm{H_2O})=18.01\ \mathrm{g\cdot mol^{-1}}$。

<details>
<summary>Answer</summary>

#### 1

正常相变温度、压力下为可逆相变：

$$
Q_1=2259\ \mathrm{J\cdot g^{-1}}\times1.00\ \mathrm{mol}\times18.01\ \mathrm{g\cdot mol^{-1}}
=40.7\ \mathrm{kJ}
$$

$$
W_1=-p_{\text{外}}(V_g-V_l)\approx-pV_g=-nRT
$$

$$
W_1=-1.00\times8.314\times373
=-3.10\ \mathrm{kJ}
$$

$$
\Delta U_1=Q_1+W_1=40.7-3.10=37.6\ \mathrm{kJ}
$$

恒压过程：

$$
\Delta H_1=Q_p=Q_1=40.7\ \mathrm{kJ}
$$

#### 2

该过程终态与过程 1 相同，因此：

$$
\Delta U_2=\Delta U_1=37.6\ \mathrm{kJ},\qquad
\Delta H_2=\Delta H_1=40.7\ \mathrm{kJ}
$$

第一步对抗外压 $0.5p$ 汽化：

$$
W_a\approx-0.5pV_1=-nRT=-3.10\ \mathrm{kJ}
$$

第二步从 $0.5p$ 恒温可逆压缩至 $p$，且 $V_2/V_1=1/2$：

$$
W_b=-nRT\ln\frac{V_2}{V_1}
=nRT\ln2=2.15\ \mathrm{kJ}
$$

$$
W_2=W_a+W_b=-3.10+2.15=-0.95\ \mathrm{kJ}
$$

$$
Q_2=\Delta U_2-W_2
=37.6-(-0.95)=38.6\ \mathrm{kJ}
$$

#### 3

向真空汽化：

$$
W_3=0
$$

由于终态与过程 1 相同：

$$
\Delta U_3=\Delta U_1=37.6\ \mathrm{kJ}
$$

$$
Q_3=\Delta U_3-W_3=37.6\ \mathrm{kJ}
$$

$$
\Delta H_3=\Delta H_1=40.7\ \mathrm{kJ}
$$

#### 4

在始态和终态相同的条件下，$\Delta U$ 和 $\Delta H$ 只与状态有关，与路径无关；$Q$ 和 $W$ 与路径有关。

</details>
