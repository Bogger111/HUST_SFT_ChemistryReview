# 例题

## Section 1 *电极电势*

### E1
已知 $E^\theta(\mathrm{Fe^{3+}/Fe^{2+}})=0.771\ \mathrm{V}$，
$E^\theta(\mathrm{Sn^{4+}/Sn^{2+}})=0.151\ \mathrm{V}$。求反应

$$
2\mathrm{Fe^{3+}}+\mathrm{Sn^{2+}}
\rightarrow2\mathrm{Fe^{2+}}+\mathrm{Sn^{4+}}
$$

的 $E^\theta_{\text{池}}$ 和 $K^\theta$。

<details>
<summary>Answer</summary>

正极为 $\mathrm{Fe^{3+}/Fe^{2+}}$，负极为
$\mathrm{Sn^{4+}/Sn^{2+}}$：

$$
E^\theta_{\text{池}}=0.771-0.151=0.620\ \mathrm{V}
$$

该反应转移电子数 $n=2$。298 K 下：

$$
\lg K^\theta=\frac{nE^\theta_{\text{池}}}{0.0592}
=\frac{2\times0.620}{0.0592}=20.95
$$

$$
K^\theta=8.8\times10^{20}
$$

</details>

### E2
在标准状态下，酸性溶液中 $\mathrm{O_2}$ 氧化 $\mathrm{Fe^{2+}}$：

$$
\mathrm{O_2}+4\mathrm{H^+}+4\mathrm{Fe^{2+}}
\rightarrow2\mathrm{H_2O}+4\mathrm{Fe^{3+}}
$$

已知 $E^\theta(\mathrm{O_2/H_2O})=1.23\ \mathrm{V}$，
$E^\theta(\mathrm{Fe^{3+}/Fe^{2+}})=0.77\ \mathrm{V}$。求
$E^\theta_{\text{池}}$ 和 $K^\theta$。

<details>
<summary>Answer</summary>

$$
E^\theta_{\text{池}}=E^\theta_{\text{正}}-E^\theta_{\text{负}}
=1.23-0.77=0.46\ \mathrm{V}
$$

该反应转移 $n=4$ 个电子：

$$
\lg K^\theta=\frac{4\times0.46}{0.0592}=31.1
$$

$$
K^\theta\approx1.2\times10^{31}
$$

</details>

## Section 2 *Nernst 方程*

### E3
计算电池

$$
(-)\ \mathrm{Pt|Fe^{2+}(0.10\ M),Fe^{3+}(0.20\ M)||Ag^+(1.0\ M)|Ag}\ (+)
$$

的电动势。已知
$E^\theta(\mathrm{Ag^+/Ag})=0.7996\ \mathrm{V}$，
$E^\theta(\mathrm{Fe^{3+}/Fe^{2+}})=0.771\ \mathrm{V}$，电池反应为

$$
\mathrm{Fe^{2+}}+\mathrm{Ag^+}\rightarrow\mathrm{Fe^{3+}}+\mathrm{Ag}
$$

<details>
<summary>Answer</summary>

$$
E^\theta_{\text{池}}=0.7996-0.771=0.0286\ \mathrm{V}
$$

反应商为：

$$
Q=\frac{[\mathrm{Fe^{3+}}]}{[\mathrm{Fe^{2+}}][\mathrm{Ag^+}]}
=\frac{0.20}{0.10\times1.0}=2.0
$$

该反应 $n=1$：

$$
E_{\text{池}}=E^\theta_{\text{池}}-\frac{0.0592}{n}\lg Q
$$

$$
E_{\text{池}}=0.0286-0.0592\lg2.0
=0.0108\ \mathrm{V}
$$

</details>

### E4
已知

$$
\mathrm{ClO_3^-}+6\mathrm{H^+}+6e^-\rightarrow\mathrm{Cl^-}+3\mathrm{H_2O}
\qquad E_1^\theta=1.45\ \mathrm{V}
$$

$$
\frac12\mathrm{Cl_2}+e^-\rightarrow\mathrm{Cl^-}
\qquad E_2^\theta=1.36\ \mathrm{V}
$$

求

$$
\mathrm{ClO_3^-}+6\mathrm{H^+}+5e^-\rightarrow
\frac12\mathrm{Cl_2}+3\mathrm{H_2O}
$$

的 $E_3^\theta$。

<details>
<summary>Answer</summary>

目标半反应等于反应 1 减反应 2。电极电势不能直接相减，应先转化为
$\Delta G^\theta=-nFE^\theta$：

$$
5E_3^\theta=6E_1^\theta-1E_2^\theta
$$

$$
E_3^\theta=\frac{6\times1.45-1\times1.36}{5}
=1.47\ \mathrm{V}
$$

</details>

### E5
已知

$$
\mathrm{Cr_2O_7^{2-}}+14\mathrm{H^+}+6e^-
\rightarrow2\mathrm{Cr^{3+}}+7\mathrm{H_2O}
\qquad E^\theta=1.23\ \mathrm{V}
$$

当 $[\mathrm{Cr^{3+}}]=1$、$[\mathrm{Cr_2O_7^{2-}}]=1$、
$[H^+]=1.0\times10^{-3}\ \mathrm{mol\cdot dm^{-3}}$ 时，求 $E$。

<details>
<summary>Answer</summary>

$$
E=E^\theta-\frac{0.0592}{6}
\lg\frac{[\mathrm{Cr^{3+}}]^2}
{[\mathrm{Cr_2O_7^{2-}}][H^+]^{14}}
$$

$$
Q=\frac{1}{1\times(10^{-3})^{14}}=10^{42}
$$

$$
E=1.23-\frac{0.0592}{6}\lg10^{42}
=1.23-0.414
=0.82\ \mathrm{V}
$$

酸度进入 $14$ 次方，因此对该电极电势影响很大。

</details>
