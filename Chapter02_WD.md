# 第二章 白矮星


## 回顾
WD 
$M~1M_{\odot},R~5000km$  
$\rho ~ 10^{6}g/cm^{3}$  
最有名的是 Sirius B  
$M~ 0.75 -0.95 M_{\odot}$
$L~\frac{1}{360}L_{\odot}~10^{31}erg/s$  
Adam 1915: 
Teff ~8000k  
$L=4\pi R^2 \sigma T^4$  
$R=18800 km$
Eddington (1908): 有一类天体与太阳质量相似但半径比天王星还小很多

Adam (1925) 
$\Delta Z=(1-\frac{2GM}{Rc^2})^{-1/2}-1$  
有前面得到的M/R与红移得到的M/R一致,因此验证了

Eddington 1926   
* 评价Adam的工作一石二鸟：
   - 验证了广义相对论
   - $\rho ~2000 \rho_{白金}$
  
* Dirac 1926.08 ~ Fermi Dirac 分布  
   - 费米字在量子态的概率分布只能小于等于1  
* Fowler 1926.12 
   - 满足Fermi Dirac分布的压强：电子简并压强 ；与引力平衡  
* Chandrasekhar 1930  
   - 必须要考虑狭义相对论  
   - 电子的能量$E_e=\sqrt{p^2c^2+m^2_e c^4}$
   - $P_e\propto \rho^{4/3}$
* Chandrasekhar 1930   极限  
   - $M_{ch}\sim 1.4M_{\odot}$  
* Landau 1932 提出中子星 
   -  发现中子 
   -  1967年发现脉冲星  
* Kaplan 1949 广义相对论的效应
   -  白矮星的质量半径关系M-R 

## 简并的开始

恒星->Fermi-Dirac分布

* 恒星的结构：  
   - 假定区域内面积为A，壳层r+dr，
   - $m(r0)=\int_0^r \rho 4\pi r^2dr$
   - $[-P(r+dr)+P(r)]=\frac{Gm(r)}{r^2}dm$
   - 流体静力学平衡$\frac{dP}{dr}=\frac{Gm(r)}{r^2}dm$

从流体静力学平衡开始讨论：
方程右边积分:  
$W=-\int^R_0\frac{Gm(r)}{r}\rho 4\pi r^2dr$  
$W=\int^R_0\frac{dP}{dr}4\pi r^3dr$  
$W=-3\int^R_0\rho4\pi r^3dr$  
所以称呼上边方程为Virial定理  

假定$P= K\rho_0^{\Gamma}$,考虑能量守恒  
绝热演化中，内能的变化应该是
$d(\frac{\epsilon}{\rho_0})=-Pd\frac{l}{\rho_0}$
绝热$dQ=0$  
$\epsilon=\rho_0 c^2+\frac{\rho}{\Gamma-1}$  
$\epsilon'=\frac{\rho}{\Gamma-1}$  
$W=-3(\Gamma-1)U$ <-维里定理

$U=\int^R_0\epsilon 4\pi r^2dr$   
$E=W+U=-\frac{3\Gamma-4}{3(\Gamma-1)}|W|$  
$W\sim -\frac{GM^2}{R}$  

Maxwell -Boltzmann 分布
$P=\frac{\rho_0}{\mu mu_u}kT$  
维里定理：  
* $-W=3\int^R_0 P 4\pi r^2dr$  
  - $=\frac{3kT}{mu m_u}\int^R_0  4\pi r^2dr$  
  - $=\frac{3M}{mu m_u}RT$  
  - $=3\times 2 \times \frac{1}{2}kT *N_{粒子数}$  

$-W=2U$  
$\bar{T}\propto\frac{M}{R}, \bar{\rho}\propto \frac{M}{R^3}$  
* $\Delta P_e \sim <(\vec{P_1}-\vec{P2})^2>^(1/2)=<2\vec{P_1}^2>^{1/2}$
  - $\sim (6m_ek\bar{T})^{1/2}$

$\frac{3}{2}k\bar{T}=\frac{P_1^2}{2m_e^2}$  
$\bar{T}\propto(\frac{12meGMm_u \mu}{7R})^{1/2}$  
$(\Gamma \sim 5/3)$

$\Delta q_e\sim(\frac{\mu_e m_u}{\rho_0})^{1/3}$
$\Delta q_e\sim(\frac{4\pi \mu_e}{\rho_0})^{1/3}$  
没抄完这一页

代入太阳质量的

$~40[1\times 10^{-26}(\frac{M}{M_{\odot}}^{1/6}(\frac{R}{R_\odot})^{1/2}g cm^2 s^{-1})^3]$  

$\sim 180h^3 (\frac{M}{M_{\odot}}^{1/2}(\frac{R}{R_\odot})^{3/2}$
当$M~M_{\odot},R\sim\frac{R_{\odot}}{30}$  

$(\Delta p_e \Delta q_e)^3\sim h^3$

Fermi Dirac 分布
$R_{WD}<\frac{R_{\odot}}{30}$

## 简并压强

费米子组成的气体在温度低密度高的时候必须考虑

$f=\frac{1}{e^{(\epsilon_e-\mu)/kt}+1}$ 注意+1和-1,+1是费米狄拉克分布，-1是玻色爱因斯坦分布

相空间中$(\vec{x},\vec{p})$

如果$\rho很大$，T很小，$T\rightarrow0$
* f=
  - 0 $\epsilon_e>\mu$
  - 1 $\epsilon_e<\mu$