# 例题

## Section 1 *Gibbs*

### E1
分别计算在 $298\ \mathrm{K}$ 和 $673\ \mathrm{K}$ 时，反应

$$
\mathrm{N_2(g)}+3\mathrm{H_2(g)}\rightleftharpoons2\mathrm{NH_3(g)}
$$

的平衡常数。

<details>
<summary>Answer</summary>

#### 298 K

$$
\Delta G_{298}^{\theta}
=2\Delta G_f^{\theta}(\mathrm{NH_3(g)})
-\Delta G_f^{\theta}(\mathrm{N_2(g)})
-3\Delta G_f^{\theta}(\mathrm{H_2(g)})
$$

$$
\Delta G_{298}^{\theta}
=2\times(-16.5)-0-0
=-33.0\ \mathrm{kJ\cdot mol^{-1}}
$$

$$
\Delta G^{\theta}=-2.303RT\lg K_p^{\theta}
$$

$$
\lg K_p^{\theta}
=-\frac{\Delta G_{298}^{\theta}}{2.303RT}
=5.786
$$

$$
K_p^{\theta}=6.11\times10^5
$$

#### 673 K

$$
\Delta G_T^{\theta}
=\Delta H_{298}^{\theta}-T\Delta S_{298}^{\theta}
=41.3\ \mathrm{kJ\cdot mol^{-1}}
$$

$$
\lg K_p^{\theta}
=-\frac{\Delta G_{673}^{\theta}}{2.303RT}
=-3.211
$$

$$
K_p^{\theta}=6.15\times10^{-4}
$$

</details>

### E2
由 $\mathrm{MnO_2(s)}$ 和 $\mathrm{HCl}$ 制备 $\mathrm{Cl_2(g)}$ 的反应为：

$$
\mathrm{MnO_2(s)}+4\mathrm{H^+(aq)}+2\mathrm{Cl^-(aq)}
\rightleftharpoons
\mathrm{Mn^{2+}(aq)}+\mathrm{Cl_2(g)}+2\mathrm{H_2O(l)}
$$

各物质的 $\Delta G_f^\theta\ (\mathrm{kJ\cdot mol^{-1}})$ 分别为：

| 物质 | $\mathrm{MnO_2(s)}$ | $\mathrm{H^+(aq)}$ | $\mathrm{Cl^-(aq)}$ | $\mathrm{Mn^{2+}(aq)}$ | $\mathrm{Cl_2(g)}$ | $\mathrm{H_2O(l)}$ |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| $\Delta G_f^\theta$ | $-465.2$ | $0$ | $-131.3$ | $-228.0$ | $0$ | $-237.2$ |

1. 标态下，$298\ \mathrm{K}$ 时，反应能否自发？
2. 若用 $12.0\ \mathrm{mol\cdot dm^{-3}}$ 的 $\mathrm{HCl}$，其他物质仍为标态，$298\ \mathrm{K}$ 时，反应能否自发？

<details>
<summary>Answer</summary>

#### 1

$$
\Delta G_{298}^{\theta}
=\left[-228.0+0+2(-237.2)\right]
-\left[(-465.2)+4(0)+2(-131.3)\right]
$$

$$
\Delta G_{298}^{\theta}
=25.4\ \mathrm{kJ\cdot mol^{-1}}>0
$$

因此，标态下反应不能自发进行。

#### 2

反应商为：

$$
Q=
\frac{
(p_{\mathrm{Cl_2}}/p^\theta)(c_{\mathrm{Mn^{2+}}}/c^\theta)
}{
(c_{\mathrm{H^+}}/c^\theta)^4(c_{\mathrm{Cl^-}}/c^\theta)^2
}
$$

代入 $c_{\mathrm{H^+}}=c_{\mathrm{Cl^-}}=12.0\ \mathrm{mol\cdot dm^{-3}}$：

$$
Q=\frac{1\times1}{12.0^4\times12.0^2}
=3.35\times10^{-7}
$$

$$
\Delta G_T
=\Delta G^{\theta}+2.303RT\lg Q
$$

$$
\Delta G_T
=25.4+2.303\times(8.314\times10^{-3})\times298\times\lg(3.35\times10^{-7})
=-11.5\ \mathrm{kJ\cdot mol^{-1}}
$$

因此，在该浓度条件下反应能自发进行。

</details>
