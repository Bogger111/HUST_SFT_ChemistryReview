# 例题

## Section 1 *弱酸弱碱*

### E1
乳酸 $\mathrm{CH_3CHOHCOOH}$ 的 $K_a=1.37\times10^{-4}$。计算
$0.10\ \mathrm{mol\cdot dm^{-3}}$ 乳酸溶液的 pH 和电离度。

<details>
<summary>Answer</summary>

先检查弱酸近似条件：

$$
\frac{c}{K_a}=\frac{0.10}{1.37\times10^{-4}}=730>400
$$

可用一元弱酸近似：

$$
[H_3O^+]\approx\sqrt{K_ac}
=\sqrt{(1.37\times10^{-4})(0.10)}
=3.7\times10^{-3}\ \mathrm{mol\cdot dm^{-3}}
$$

$$
pH=-\lg(3.7\times10^{-3})=2.43
$$

$$
\alpha=\frac{[H_3O^+]}{c}
=\frac{3.7\times10^{-3}}{0.10}
=3.7\%
$$

</details>

### E2
将 $2.45\ \mathrm{g}$ 固体 $\mathrm{NaCN}$ 配成 $500\ \mathrm{cm^3}$ 溶液。
已知 $M(\mathrm{NaCN})=49\ \mathrm{g\cdot mol^{-1}}$，
$K_a(\mathrm{HCN})=4.93\times10^{-10}$，求溶液 pH。

<details>
<summary>Answer</summary>

$$
c(\mathrm{CN^-})
=\frac{2.45/49}{0.500}
=0.10\ \mathrm{mol\cdot dm^{-3}}
$$

$\mathrm{CN^-}$ 是 $\mathrm{HCN}$ 的共轭碱：

$$
K_b(\mathrm{CN^-})
=\frac{K_w}{K_a(\mathrm{HCN})}
=\frac{1.0\times10^{-14}}{4.93\times10^{-10}}
=2.0\times10^{-5}
$$

$$
[OH^-]\approx\sqrt{K_bc}
=\sqrt{(2.0\times10^{-5})(0.10)}
=1.4\times10^{-3}\ \mathrm{mol\cdot dm^{-3}}
$$

$$
pOH=-\lg(1.4\times10^{-3})=2.85
$$

$$
pH=14.00-2.85=11.15
$$

</details>

## Section 2 *同离子效应与缓冲*

### E3
向 $1.0\ \mathrm{dm^3}$ 的 $0.10\ \mathrm{mol\cdot dm^{-3}}$ $\mathrm{HAc}$
溶液中加入固体 $\mathrm{NaAc}$，使 $[Ac^-]=1.0\ \mathrm{mol\cdot dm^{-3}}$。
取 $K_a(\mathrm{HAc})=1.8\times10^{-5}$，求 $[H_3O^+]$、pH 和
$\mathrm{HAc}$ 的电离度。

<details>
<summary>Answer</summary>

这是 $\mathrm{HAc}/\mathrm{Ac^-}$ 共轭酸碱体系：

$$
[H_3O^+]=K_a\frac{c_{\mathrm{HAc}}}{c_{\mathrm{Ac^-}}}
$$

$$
[H_3O^+]
=1.8\times10^{-5}\times\frac{0.10}{1.0}
=1.8\times10^{-6}\ \mathrm{mol\cdot dm^{-3}}
$$

$$
pH=-\lg(1.8\times10^{-6})=5.74
$$

$$
\alpha=\frac{1.8\times10^{-6}}{0.10}
=1.8\times10^{-5}=0.0018\%
$$

加入同离子 $\mathrm{Ac^-}$ 后，$\mathrm{HAc}$ 电离被明显抑制。

</details>

### E4
已知 $\mathrm{H_3PO_4}$ 的 $K_{a1}=7.52\times10^{-3}$，
$K_{a2}=6.23\times10^{-8}$。按两性离子近似公式计算
$\mathrm{NaH_2PO_4}$ 溶液的 pH。

<details>
<summary>Answer</summary>

$\mathrm{H_2PO_4^-}$ 是两性离子，可用近似：

$$
[H_3O^+]\approx\sqrt{K_{a1}K_{a2}}
$$

$$
[H_3O^+]
=\sqrt{(7.52\times10^{-3})(6.23\times10^{-8})}
=2.16\times10^{-5}\ \mathrm{mol\cdot dm^{-3}}
$$

$$
pH=-\lg(2.16\times10^{-5})=4.67
$$

因此 $pH\approx4.68$。

</details>

### E5
欲配制 $pH=9.20$、$[NH_3\cdot H_2O]=1.0\ \mathrm{mol\cdot dm^{-3}}$
的缓冲溶液 $500\ \mathrm{cm^3}$。已知
$K_b(\mathrm{NH_3})=1.8\times10^{-5}$，浓氨水浓度为
$15\ \mathrm{mol\cdot dm^{-3}}$，$M(\mathrm{NH_4Cl})=53.5\ \mathrm{g\cdot mol^{-1}}$。
求需 $\mathrm{NH_4Cl}$ 质量和浓氨水体积。

<details>
<summary>Answer</summary>

$$
pOH=14.00-9.20=4.80
$$

$$
[OH^-]=10^{-4.80}=1.6\times10^{-5}\ \mathrm{mol\cdot dm^{-3}}
$$

弱碱缓冲体系满足：

$$
[OH^-]=K_b\frac{[NH_3\cdot H_2O]}{[NH_4^+]}
$$

$$
[NH_4^+]
=\frac{K_b[NH_3\cdot H_2O]}{[OH^-]}
=\frac{(1.8\times10^{-5})(1.0)}{1.6\times10^{-5}}
\approx1.1\ \mathrm{mol\cdot dm^{-3}}
$$

$$
m(\mathrm{NH_4Cl})
=0.500\times1.1\times53.5
\approx29\ \mathrm{g}
$$

$$
V(\text{浓氨水})
=\frac{1.0\times0.500}{15}
=0.033\ \mathrm{dm^3}
=33\ \mathrm{cm^3}
$$

需称取约 $29\ \mathrm{g}$ $\mathrm{NH_4Cl}$，取约
$33\ \mathrm{cm^3}$ 浓氨水，加水定容至 $500\ \mathrm{cm^3}$。

</details>
