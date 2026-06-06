# 大学化学公式总表

本表按课程章节整理。背公式时不要只背等式，还要同时记住适用条件、符号意义和常见错误。

## 第一章 气体与液体

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 理想气体 | \(pV=nRT\) | \(T\) 必须用 K；\(R\) 与 \(p,V\) 单位匹配 |
| Boyle 定律 | \(p_1V_1=p_2V_2\) | 等温、定量气体 |
| Charles-Gay-Lussac 定律 | \(\frac{V_1}{T_1}=\frac{V_2}{T_2}\) | 等压、定量气体 |
| 综合气体定律 | \(\frac{p_1V_1}{T_1}=\frac{p_2V_2}{T_2}\) | 同一份气体，物质的量不变 |
| 摩尔质量 | \(M=\frac{mRT}{pV}\) | 由 \(pV=nRT,\ n=m/M\) 得到 |
| 气体密度 | \(\rho=\frac{pM}{RT}\) | \(M\) 与 \(\rho\) 单位要匹配 |
| 分压 | \(P_{\text{总}}=\sum P_i,\ P_A=x_AP_{\text{总}}\) | 分压对应相同 \(V,T\) |
| 分体积 | \(V_{\text{总}}=\sum V_i,\ V_A=x_AV_{\text{总}}\) | 分体积对应相同 \(p,T\) |
| 混合气体统一式 | \(P_{\text{总}}V_A=P_AV_{\text{总}}=n_ART\) | 不能写成 \(P_AV_A=n_ART\) |
| 压缩系数 | \(Z=\frac{pV}{nRT}\) | \(Z<1\) 吸引力主导，\(Z>1\) 自身体积主导 |
| Van der Waals 方程 | \(\left(P+\frac{an^2}{V^2}\right)(V-nb)=nRT\) | 压力加校正项，体积减校正项 |
| Clausius-Clapeyron | \(\lg p=-\frac{\Delta H_{\text{vap}}}{2.303RT}+B\) | 用 \(\lg\) 时分母有 \(2.303R\) |
| 两点式 | \(\lg\frac{p_2}{p_1}=\frac{\Delta H_{\text{vap}}}{2.303R}\left(\frac{T_2-T_1}{T_2T_1}\right)\) | \(p_1,p_2\) 单位保持一致即可 |

## 第二章 溶液

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 质量分数 | \(\omega_B=\frac{m_B}{m_{\text{溶液}}}\) | 分母是溶液总质量 |
| 摩尔分数 | \(x_B=\frac{n_B}{\sum n_i}\) | 必须先换算为物质的量 |
| 质量摩尔浓度 | \(m_B=\frac{n_B}{m_A(\text{kg})}\) | 分母是溶剂质量，单位 kg |
| 体积分数 | \(\varphi_B=\frac{V_B}{\sum V_i}\) | 通常取混合前体积 |
| 物质的量浓度 | \(c_B=\frac{n_B}{V_{\text{溶液}}}\) | 分母是溶液体积 |
| Raoult 定律 | \(p=p^0x_1\) | \(x_1\) 是溶剂摩尔分数 |
| 蒸气压下降 | \(\Delta p=p^0x_2\) | 非挥发性、非电解质稀溶液 |
| 沸点升高 | \(\Delta T_b=K_bm\) | 温差 K 和 \(^\circ C\) 数值相同 |
| 凝固点降低 | \(\Delta T_f=K_fm\) | 常用于摩尔质量测定 |
| 渗透压 | \(\pi=cRT\) | 稀溶液近似；电解质需考虑粒子数 |
| 活度 | \(a_i=\gamma_i c_i/c^\theta\) | 实际溶液用有效浓度描述 |

## 第三章 化学热力学

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 体积功 | \(W=-p_{\text{外}}\Delta V\) | 膨胀时 \(W<0\) |
| 可逆体积功 | \(W=-\int p_{\text{外}}\,dV\) | 可逆过程常取 \(p_{\text{外}}\approx p\) |
| 第一定律 | \(\Delta U=Q+W\) | 本课程符号：吸热、受功为正 |
| 恒容热 | \(Q_V=\Delta U\) | 恒容且无非体积功 |
| 焓 | \(H=U+pV\) | 状态函数 |
| 恒压热 | \(Q_p=\Delta H\) | 恒压且无非体积功 |
| 恒压恒容热关系 | \(\Delta H=\Delta U+\Delta n_gRT\) | 只统计气体计量数 |
| 盖斯定律 | \(\Delta H_{\text{总}}=\sum \Delta H_i\) | 反应反向则焓变变号 |
| 标准反应焓 | \(\Delta_rH^\theta=\sum\nu\Delta_fH^\theta(\text{产物})-\sum\nu\Delta_fH^\theta(\text{反应物})\) | 稳定单质 \(\Delta_fH^\theta=0\) |
| 键焓估算 | \(\Delta H\approx\sum D(\text{断键})-\sum D(\text{成键})\) | 断键吸热，成键放热 |
| 熵变 | \(\Delta_rS^\theta=\sum\nu S^\theta(\text{产物})-\sum\nu S^\theta(\text{反应物})\) | 注意计量数 |
| Gibbs-Helmholtz | \(\Delta G=\Delta H-T\Delta S\) | 恒温近似常用 |
| 转变温度 | \(T=\frac{\Delta H}{\Delta S}\) | \(\Delta G=0\) 时 |
| 标准反应自由能 | \(\Delta_rG^\theta=\sum\nu\Delta_fG^\theta(\text{产物})-\sum\nu\Delta_fG^\theta(\text{反应物})\) | 判断标准态方向 |

## 第四章 化学平衡

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 浓度平衡常数 | \(K_c=\frac{[C]^c[D]^d}{[A]^a[B]^b}\) | 使用平衡浓度 |
| 压力平衡常数 | \(K_p=\frac{p_C^cp_D^d}{p_A^ap_B^b}\) | 使用气体平衡分压 |
| \(K_p,K_c\) 关系 | \(K_p=K_c(RT)^{\Delta n_g}\) | \(\Delta n_g\) 只统计气体 |
| 标准平衡常数 | \(K^\theta=\prod a_i^{\nu_i}\) | 热力学公式用 \(K^\theta\) |
| \(\Delta G^\theta\) 与 \(K^\theta\) | \(\Delta G_T^\theta=-2.303RT\lg K^\theta\) | \(T\) 用 K，\(R\) 单位匹配 |
| 任意态自由能 | \(\Delta G_T=\Delta G_T^\theta+2.303RT\lg Q\) | 非标准态要用 \(Q\) |
| 判据 | \(\Delta G_T=2.303RT\lg(Q/K^\theta)\) | \(Q<K\) 正向自发 |
| 多重平衡 | \(K_{\text{总}}=K_1K_2\cdots\) | 反应相加，常数相乘 |
| Van't Hoff 方程 | \(\lg\frac{K_2}{K_1}=-\frac{\Delta H^\theta}{2.303R}\left(\frac1{T_2}-\frac1{T_1}\right)\) | 放热升温 \(K\) 减小 |
| 转化率 | \(\alpha=\frac{\text{已转化量}}{\text{起始量}}\times100\%\) | 注意限量组分 |

## 第五章 酸碱平衡

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 酸常数 | \(K_a=\frac{[H_3O^+][A^-]}{[HA]}\) | 弱酸电离平衡 |
| 碱常数 | \(K_b=\frac{[BH^+][OH^-]}{[B]}\) | 弱碱电离平衡 |
| 共轭关系 | \(K_aK_b=K_w\) | 必须是共轭酸碱对 |
| 水的离子积 | \(K_w=[H_3O^+][OH^-]\) | 298 K 为 \(1.0\times10^{-14}\) |
| pH | \(pH=-\lg[H_3O^+]\) | 稀水溶液常用 |
| pOH | \(pOH=-\lg[OH^-]\) | 298 K 时 \(pH+pOH=14\) |
| 一元弱酸近似 | \([H_3O^+]\approx\sqrt{K_ac}\) | \(c/K_a\ge400\) |
| 一元弱碱近似 | \([OH^-]\approx\sqrt{K_bc}\) | 求 pH 前先求 pOH |
| 电离度 | \(\alpha\approx\sqrt{K_a/c}\) 或 \(\sqrt{K_b/c}\) | 近似条件同上 |
| 缓冲公式 | \(pH=pK_a+\lg\frac{[A^-]}{[HA]}\) | 酸在分母，盐在分子 |
| 指示剂范围 | \(pH=pK_a\pm1\) | 粗略变色范围 |
| 中和平衡常数 | \(K=\frac1{K_w}\) 或由酸碱常数组合 | 强酸强碱中和趋于完全 |

## 第七章 电化学

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 电动势 | \(E_{\text{池}}=E_{\text{正}}-E_{\text{负}}\) | 正极还原，负极氧化 |
| 自由能与电动势 | \(\Delta G=-nFE\) | \(E>0\) 对应 \(\Delta G<0\) |
| 标准自由能 | \(\Delta G^\theta=-nFE^\theta\) | \(n\) 是转移电子数 |
| 标准电动势与平衡 | \(E^\theta=\frac{2.303RT}{nF}\lg K^\theta\) | 298 K 可写 \(0.0592/n\) |
| 298 K 形式 | \(E^\theta=\frac{0.0592}{n}\lg K^\theta\) | 电势不随配平系数倍增 |
| 电池 Nernst | \(E=E^\theta-\frac{0.0592}{n}\lg Q\) | 298 K |
| 电极 Nernst | \(E=E^\theta+\frac{0.0592}{n}\lg\frac{(Ox)^m}{(Red)^q}\) | 半反应按还原方向写 |
| 氢电极 | \(E(H^+/H_2)=-0.0592pH\) | \(p_{H_2}=p^\theta\)，298 K |
| 浓差电池测 pH | \(E_{\text{池}}=0.0592pH\) | 与标准氢电极比较 |

## 第八章 化学动力学

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 反应速率 | \(v=-\frac1a\frac{d[A]}{dt}=\frac1c\frac{d[C]}{dt}\) | 按计量数归一化 |
| 速率方程 | \(v=k[A]^m[B]^n\) | 非基元反应由实验确定 |
| 一级积分式 | \(\ln[A]=\ln[A]_0-kt\) | \(\ln[A]\) 对 \(t\) 直线 |
| 一级半衰期 | \(t_{1/2}=\frac{0.693}{k}\) | 与初始浓度无关 |
| 二级积分式 | \(\frac1{[A]}=\frac1{[A]_0}+kt\) | \(1/[A]\) 对 \(t\) 直线 |
| 二级半衰期 | \(t_{1/2}=\frac1{k[A]_0}\) | 与初始浓度成反比 |
| 三级积分式 | \(\frac1{[A]^2}=\frac1{[A]_0^2}+2kt\) | 斜率为 \(2k\) |
| 三级半衰期 | \(t_{1/2}=\frac3{2k[A]_0^2}\) | 较少见 |
| 零级积分式 | \([A]=[A]_0-kt\) | 匀速消耗 |
| 零级半衰期 | \(t_{1/2}=\frac{[A]_0}{2k}\) | 与初始浓度成正比 |
| Arrhenius | \(\ln k=-\frac{E_a}{RT}+C\) | \(T\) 用 K |
| 两温度式 | \(\ln\frac{k_2}{k_1}=\frac{E_a}{R}\left(\frac1{T_1}-\frac1{T_2}\right)\) | \(E_a\) 与 \(R\) 单位一致 |
| 活化能与反应热 | \(\Delta H=E_{a,\text{正}}-E_{a,\text{逆}}\) | 近似能垒图关系 |
| 稳态近似 | \(\frac{d[\text{中间体}]}{dt}\approx0\) | 中间体浓度近似恒定 |

## 第九章 原子结构

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 光子能量 | \(E=h\nu\) | 频率越高，能量越大 |
| 光电效应 | \(E_k=h\nu-E_0\) | 频率决定最大动能 |
| Rydberg 公式 | \(\frac1\lambda=R_H(\frac1{n_1^2}-\frac1{n_2^2})\) | \(n_2>n_1\) |
| Bohr 半径 | \(r_n=a_0n^2\) | 氢原子近似 |
| 氢原子能级 | \(E_n=-\frac{13.6}{n^2}\text{ eV}\) | \(n\to\infty\) 时趋近 0 |
| 跃迁能量 | \(\Delta E=h\nu=\frac{hc}{\lambda}\) | 吸收向高能级，发射向低能级 |
| de Broglie | \(\lambda=\frac hp=\frac h{mv}\) | 动量越大，波长越短 |
| 电子加速 | \(eV=\frac12mv^2\) | 可与 de Broglie 联用 |
| 测不准 | \(\Delta x\Delta p\ge\frac h{4\pi}\) | 否定经典确定轨道 |
| 径向分布 | \(D(r)=4\pi r^2R^2\) | 球壳概率分布 |
| 有效核电荷 | \(Z^*=Z-\sigma\) | \(\sigma\) 为屏蔽常数 |
| 轨道数 | 第 \(n\) 层轨道数 \(n^2\) | 最大电子数 \(2n^2\) |

## 第十章 分子与晶体结构

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 离子半径 | \(r_0=r_++r_-\) | \(r_0\) 是离子核间距 |
| Lande 模型 | \(r_-=\frac{r_0}{\sqrt2},\ r_+=r_0-r_-\) | 特定几何模型 |
| Born-Haber 循环 | \(\Delta H_{\text{overall}}=\sum \Delta H_i\) | 注意符号约定 |
| Born-Lande | \(U=\frac{N_AAZ_1Z_2e^2}{4\pi\varepsilon_0r_0}(1-\frac1n)\) | 比较时看 \(Z_1Z_2/r_0\) |
| VSEPR | 价层电子对数 \(=\frac{\text{中心价电子数}+\text{配原子提供电子数}}2\) | 多重键按一个电子域 |
| 偶极矩 | \(\mu=q d\) | 偶极矩是矢量 |
| Debye 换算 | \(1D=3.336\times10^{-30}C\cdot m\) | 常见单位换算 |
| 范德华力 | \(F_{\text{vdW}}\propto\frac1{r^6}\) | 距离增大迅速减弱 |
| 空间利用率 | \(\frac{\text{晶胞球数}\times\text{单球体积}}{\text{晶胞体积}}\times100\%\) | fcc/hcp 为 74% |
| 半径比规则 | \(r_+/r_-\) 判断配位数 | 0.225, 0.414, 0.732 为常用界值 |
| 离子势 | \(\phi=\frac z r\) | 电荷高、半径小，极化能力强 |
| 键级 | \(BO=\frac{N_b-N_a}{2}\) | 键级越大，键越强 |

## 第十三章 有机与高分子

| 主题 | 公式 | 适用和提醒 |
|---|---|---|
| 开链烷烃 | \(C_nH_{2n+2}\) | 无环、无重键 |
| 单烯烃 | \(C_nH_{2n}\) | 开链一个双键 |
| 单炔烃 | \(C_nH_{2n-2}\) | 开链一个三键 |
| Hückel 规则 | \(\pi\text{电子数}=4n+2\) | 环状、平面、闭合共轭 |
| 辛烷值 | \(\frac{V_{\text{异辛烷}}}{V_{\text{异辛烷}}+V_{\text{正庚烷}}}\times100\) | 通常按体积分数 |
| 扭转能估算 | \(E_{\text{总}}=\sum E_i\) | 乙烷重叠约 \(12\ kJ\cdot mol^{-1}\) |
| 聚合度 | \(M=nM_0,\ n=\frac M{M_0}\) | \(M_0\) 是链节相对分子质量 |
| 数均分子量 | \(M_n=\frac{\sum N_iM_i}{\sum N_i}\) | 按分子数平均 |
| 重均分子量 | \(M_w=\frac{\sum N_iM_i^2}{\sum N_iM_i}\) | 高分子量部分影响大 |
| 分散系数 | \(D=\frac{M_w}{M_n}\) | \(D\ge1\)，越接近 1 越窄 |
| 缩聚通式 | \(nA\!-\!A+nB\!-\!B\rightarrow[-A\!-\!B-]_n+\text{小分子}\) | 常有小分子副产物 |
| 加聚通式 | \(nCH_2=CHX\rightarrow[-CH_2-CHX-]_n\) | 单体加成成链 |

