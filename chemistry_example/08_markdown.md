# 例题

## Section 1 *反应速率*

### E1
对基元反应

$$
\mathrm{A}+2\mathrm{B}\rightarrow3\mathrm{C}
$$

若 $-\mathrm{d}[A]/\mathrm{d}t=1.0\times10^{-3}\
\mathrm{mol\cdot dm^{-3}\cdot s^{-1}}$，求
$+\mathrm{d}[C]/\mathrm{d}t$ 和反应速率 $v$。

<details>
<summary>Answer</summary>

按化学计量数归一化：

$$
v=-\frac{\mathrm{d}[A]}{\mathrm{d}t}
=\frac{1}{3}\frac{\mathrm{d}[C]}{\mathrm{d}t}
$$

$$
v=1.0\times10^{-3}\ \mathrm{mol\cdot dm^{-3}\cdot s^{-1}}
$$

$$
\frac{\mathrm{d}[C]}{\mathrm{d}t}=3v
=3.0\times10^{-3}\ \mathrm{mol\cdot dm^{-3}\cdot s^{-1}}
$$

</details>

## Section 2 *积分速率方程*

### E2
已知某一级反应速率常数
$k=2.2\times10^{-5}\ \mathrm{s^{-1}}$。求其半衰期。

<details>
<summary>Answer</summary>

一级反应：

$$
t_{1/2}=\frac{0.693}{k}
$$

$$
t_{1/2}=\frac{0.693}{2.2\times10^{-5}}
=3.15\times10^4\ \mathrm{s}
$$

$$
3.15\times10^4\ \mathrm{s}=8.75\ \mathrm{h}
$$

</details>

### E3
某一级反应初始质量为 $2.00\ \mathrm{g}$，
$k=2.2\times10^{-5}\ \mathrm{s^{-1}}$。反应 $2.00\ \mathrm{h}$ 后剩余多少？
假设质量与浓度成正比。

<details>
<summary>Answer</summary>

一级反应满足：

$$
\ln\frac{[A]}{[A]_0}=-kt
$$

时间换算：

$$
t=2.00\ \mathrm{h}=7200\ \mathrm{s}
$$

$$
\frac{m}{m_0}=e^{-kt}
=e^{-(2.2\times10^{-5})(7200)}
=e^{-0.1584}=0.853
$$

$$
m=2.00\times0.853=1.71\ \mathrm{g}
$$

</details>

### E4
某二级反应 $\mathrm{A}\rightarrow\mathrm{P}$，
$[A]_0=1.00\ \mathrm{mol\cdot dm^{-3}}$，
$k=0.50\ \mathrm{mol^{-1}\cdot dm^3\cdot h^{-1}}$。求
$t=4.0\ \mathrm{h}$ 时 $[A]$。

<details>
<summary>Answer</summary>

二级反应积分式：

$$
\frac{1}{[A]}=\frac{1}{[A]_0}+kt
$$

$$
\frac{1}{[A]}=\frac{1}{1.00}+0.50\times4.0
=3.00
$$

$$
[A]=0.333\ \mathrm{mol\cdot dm^{-3}}
$$

</details>

## Section 3 *活化能*

### E5
已知基元反应 $\mathrm{A}\rightarrow\mathrm{B}$ 的
$\Delta H=67\ \mathrm{kJ\cdot mol^{-1}}$，正反应
$E_a=90\ \mathrm{kJ\cdot mol^{-1}}$。求逆反应活化能。若
$0^\circ\mathrm{C}$ 时 $k_1=1.1\times10^{-5}\ \mathrm{min^{-1}}$，
求 $45^\circ\mathrm{C}$ 时 $k_2$。取
$R=8.314\ \mathrm{J\cdot mol^{-1}\cdot K^{-1}}$。

<details>
<summary>Answer</summary>

能量图关系：

$$
\Delta H=E_{a,\text{正}}-E_{a,\text{逆}}
$$

$$
E_{a,\text{逆}}=90-67=23\ \mathrm{kJ\cdot mol^{-1}}
$$

Arrhenius 两温度式：

$$
\ln\frac{k_2}{k_1}
=\frac{E_a}{R}\left(\frac{1}{T_1}-\frac{1}{T_2}\right)
$$

$$
T_1=273.15\ \mathrm{K},\qquad T_2=318.15\ \mathrm{K}
$$

$$
\ln\frac{k_2}{k_1}
=\frac{90000}{8.314}
\left(\frac{1}{273.15}-\frac{1}{318.15}\right)
=5.61
$$

$$
k_2=k_1e^{5.61}
=1.1\times10^{-5}\times273
=3.0\times10^{-3}\ \mathrm{min^{-1}}
$$

</details>
