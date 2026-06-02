# 例题

## Section 1 *气体*

### E1
某气体在 $293\ \mathrm{K}$ 和 $9.97\times10^4\ \mathrm{Pa}$ 时占有体积
$0.19\ \mathrm{dm^3}$，质量为 $0.132\ \mathrm{g}$。试求该气体的摩尔质量，并指出它可能是何种气体。

<details>
<summary>Answer</summary>

由理想气体状态方程：

$$
n=\frac{pV}{RT}
=\frac{(9.97\times10^4\ \mathrm{Pa})(0.19\times10^{-3}\ \mathrm{m^3})}
{(8.314\ \mathrm{J\cdot mol^{-1}\cdot K^{-1}})(293\ \mathrm{K})}
=7.78\times10^{-3}\ \mathrm{mol}
$$

$$
M=\frac{m}{n}
=\frac{0.132\ \mathrm{g}}{7.78\times10^{-3}\ \mathrm{mol}}
=17.0\ \mathrm{g\cdot mol^{-1}}
$$

该气体可能为 $\mathrm{NH_3}$。

</details>

### E2
在 $25.0^\circ\mathrm{C}$、$748\ \mathrm{mmHg}$ 下，要产生
$75.0\ \mathrm{L}$ 的 $\mathrm{N_2}$，计算需要叠氮化钠的质量。

<details>
<summary>Answer</summary>

反应方程式：

$$
2\mathrm{NaN_3(s)}\rightarrow 2\mathrm{Na(s)}+3\mathrm{N_2(g)}
$$

$$
n(\mathrm{N_2})=\frac{pV}{RT}
=\frac{(748/760\ \mathrm{atm})(75.0\ \mathrm{L})}
{(0.08206\ \mathrm{L\cdot atm\cdot mol^{-1}\cdot K^{-1}})(298.15\ \mathrm{K})}
=3.02\ \mathrm{mol}
$$

$$
n(\mathrm{NaN_3})=\frac{2}{3}n(\mathrm{N_2})=2.01\ \mathrm{mol}
$$

$$
m(\mathrm{NaN_3})=2.01\ \mathrm{mol}\times65.0\ \mathrm{g\cdot mol^{-1}}
=1.31\times10^2\ \mathrm{g}
$$

需要 $\mathrm{NaN_3}$ 约 $131\ \mathrm{g}$。

</details>

### E3
$\mathrm{A}$、$\mathrm{B}$ 两种气体在一定温度下，在同一容器中混合。混合后，下面表达式是否正确？

1. $p_A V_A=n_A RT$
2. $p_{\text{总}}V=n_A RT$
3. $p_{\text{总}}V_A=n_A RT$
4. $p_A V=n_A RT$
5. $p_A(V_A+V_B)=n_A RT$
6. $(p_A+p_B)V_A=n_A RT$

<details>
<summary>Answer</summary>

对理想气体混合物：

$$
p_A V=n_A RT,\qquad p_{\text{总}}V_A=n_A RT
$$

若 $V_A$、$V_B$ 为分体积，则 $V=V_A+V_B$，且
$p_{\text{总}}=p_A+p_B$。

因此：

1. 不正确
2. 不正确
3. 正确
4. 正确
5. 正确
6. 正确

</details>

### E4
在深海潜水时，如以氧气 $2\%$、氮气 $8\%$、氦气 $90\%$ 的混合气体在
$90\ \mathrm{m}$ 的深度呼吸时，总压为 $10\ \mathrm{atm}$，求各气体的分压。

<details>
<summary>Answer</summary>

由道尔顿分压定律：

$$
p_i=x_i p_{\text{总}}
$$

$$
p(\mathrm{O_2})=0.02\times10\ \mathrm{atm}=0.20\ \mathrm{atm}
$$

$$
p(\mathrm{N_2})=0.08\times10\ \mathrm{atm}=0.80\ \mathrm{atm}
$$

$$
p(\mathrm{He})=0.90\times10\ \mathrm{atm}=9.0\ \mathrm{atm}
$$

</details>
