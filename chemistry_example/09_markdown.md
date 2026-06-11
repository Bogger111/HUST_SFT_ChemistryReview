# 例题

## Section 1 *氢原子能级*

### E1
计算氢原子从 $n=1$ 到 $n=\infty$ 的电离能，先求单个原子所需能量，
再求 $1\ \mathrm{mol}$ 氢原子的电离能。已知
$1\ \mathrm{eV}=1.602\times10^{-19}\ \mathrm{J}$，
$N_A=6.02\times10^{23}\ \mathrm{mol^{-1}}$。

<details>
<summary>Answer</summary>

氢原子能级：

$$
E_n=-\frac{13.6}{n^2}\ \mathrm{eV}
$$

$$
E_1=-13.6\ \mathrm{eV},\qquad E_\infty=0
$$

单个原子电离能：

$$
\Delta E=0-(-13.6)=13.6\ \mathrm{eV}
$$

$$
13.6\ \mathrm{eV}
=13.6\times1.602\times10^{-19}
=2.18\times10^{-18}\ \mathrm{J}
$$

每摩尔：

$$
2.18\times10^{-18}\times6.02\times10^{23}
=1.31\times10^6\ \mathrm{J\cdot mol^{-1}}
=1310\ \mathrm{kJ\cdot mol^{-1}}
$$

</details>

### E2
计算氢原子 $n=3\rightarrow n=2$ 跃迁发射光子的波长。用
$E_n=-13.6/n^2\ \mathrm{eV}$，$hc=1240\ \mathrm{eV\cdot nm}$。

<details>
<summary>Answer</summary>

$$
E_3=-\frac{13.6}{9}=-1.51\ \mathrm{eV}
$$

$$
E_2=-\frac{13.6}{4}=-3.40\ \mathrm{eV}
$$

发射光子能量为能级差的绝对值：

$$
\Delta E=|-3.40-(-1.51)|=1.89\ \mathrm{eV}
$$

$$
\lambda=\frac{hc}{\Delta E}
=\frac{1240}{1.89}
=656\ \mathrm{nm}
$$

这是 Balmer 线系中的红线。

</details>

## Section 2 *物质波与量子数*

### E3
计算速度为 $5.9\times10^5\ \mathrm{m\cdot s^{-1}}$ 的电子的 de Broglie 波长。
已知 $h=6.626\times10^{-34}\ \mathrm{J\cdot s}$，
$m_e=9.11\times10^{-31}\ \mathrm{kg}$。

<details>
<summary>Answer</summary>

$$
\lambda=\frac{h}{mv}
$$

$$
\lambda
=\frac{6.626\times10^{-34}}
{(9.11\times10^{-31})(5.9\times10^5)}
=1.23\times10^{-9}\ \mathrm{m}
$$

即：

$$
\lambda\approx1.2\times10^{-9}\ \mathrm{m}=12\ \mathrm{\AA}
$$

</details>

### E4
判断 $\varphi(3,2,1)$ 代表哪个亚层轨道，并说明该亚层有多少个轨道、
最多容纳多少电子。

<details>
<summary>Answer</summary>

$\varphi(3,2,1)$ 中：

$$
n=3,\qquad l=2,\qquad m=1
$$

$l=2$ 对应 $d$ 亚层，因此它代表 $3d$ 亚层中的一个取向轨道。

亚层轨道数：

$$
2l+1=2\times2+1=5
$$

每个轨道最多容纳 2 个自旋相反电子：

$$
5\times2=10
$$

所以 $3d$ 亚层有 5 个轨道，最多容纳 10 个电子。

</details>

## Section 3 *有效核电荷*

### E5
用 Slater 规则材料中给出的 Na 价电子结果 $Z^*=2.20$，估算 Na 的
$3s$ 电子能量。用

$$
E=-13.6\frac{(Z^*)^2}{n^2}\ \mathrm{eV}
$$

其中 $n=3$。

<details>
<summary>Answer</summary>

$$
E=-13.6\frac{(2.20)^2}{3^2}
$$

$$
E=-13.6\times\frac{4.84}{9}
=-7.3\ \mathrm{eV}
$$

能量为负，表示该电子处于受原子核束缚的状态。

</details>
