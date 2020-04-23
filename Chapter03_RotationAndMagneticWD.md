# 第三章 转动和磁场对WD结构的影响

## 一、磁流体方程 （Euler方程）

$\rho\frac{d\vec{v}}{dt}==(-\bigtriangledown P -\rho\bigtriangledown\Phi+\frac{1}{c})\vec{J}\times\vec{B})\cdot\vec{x}$  
左右积分

$\frac{1}{2}\frac{d^2I}{dt^2}=2T+W+3\Pi+m$


$I=\int\rho x^2dx$ 广义转动惯量  
$T=\frac{1}{2}\int\rho v^2dx$宏观整体运动动能  
$W=\frac{1}{2}\int\Phi dx^3$
$\Pi=\int\rho d^3x$气体压强积分  
$\frac{3}{2}\Pi$是内能  
$m=\frac{1}{8\pi}\int B^2d^3x$  （m总磁能）

平衡时，自引力的系统  
$\frac{dI}{dt}\sim const$  
$\frac{d^I}{dt^2}=0$  
维里定理  $2T+W+3\Pi+m=0$  $(W+2K=0, K=\frac{3}{2}\Pi)$

## 二  磁场WD 无转动

$T=0$ 非转动  
$W+3\Pi+m=0$  
$\sigma -> \infty$  磁通量  
$\Phi_M\sim<B>R^2$ 守恒

非相对论(NRD) $Pi\propto\rho^{5/3}$  
相对论(ERD) $Pi\propto\rho^{4/3}$  
$-\alpha_{3/2}\frac{GM^2}{R}+\beta_{3/2}\frac{M^{5/3}}{R^2}+\gamma_{3/2}\frac{\Phi_M^2}{R}=0$  (NRD)  
$-\alpha_{3}\frac{GM^2}{R}+\beta_{3}\frac{M^{5/3}}{R^2}+\gamma_{3}\frac{\Phi_M^2}{R}=0$  (NRD)  

其中$\alpha \beta \gamma$为正参数  
增加$\Phi_M$降低引力势  
$G'=G-\frac{\gamma\Phi_M^2}{αM^2}=G(1=\frac{m}{|w|})$  
求解NRD方程
$R=\frac{\beta_{3/2}}{\alpha_{3/2}G'M^{2/3}}=\frac{R_0}{1-\frac{m}{||w}}$  
R_0是B=0时候的WD半径  
令$\delta=\frac{m}{|w|}$   
$\delta ↑ R↑$ 

### ERD $\delta<<1$
$M^{2/3}=\frac{\beta_3}{\alpha_3G}(1+\frac{\gamma_3\Phi_M^2}{\beta_3M^{4/3}})$  
$M^{2/3}=\frac{\beta_3}{\alpha_3G}(1+\frac{\gamma_3\Phi_M^2}{\beta_3M^{2}}M^{2/3})$  
$M^{2/3}=\frac{\beta_3}{\alpha_3G}(1+\frac{\gamma_3\Phi_M^2}{\alpha_3M^{2}}$  
$M=(\frac{\beta_3}{\alpha_3G})^{3/2}(1+\frac{3}{2}\frac{\gamma_3\Phi_M^2}{\alpha_3M^{2}})=M_0(1+\frac{3}{2}\delta)$  
说明B的存在对M的增加是小量，影响不大  

总能量：
$\Gamma=1+\frac{1}{n}, n\simeq 3$    
$E=-\frac{3\Gamma-4}{3(\Gamma-1)}|w|=\frac{3-n}{3}|w|<<|w|$  
得到$\frac{\Delta E}{E}=-\frac{\Delta R}{R}$  
又因为$\Delta E=\Delta m$ 

$\frac{\Delta R}{R}=\frac{3}{3-n}\frac{\Delta m}{|w|}\frac{3}{3-n}\Delta delta$  

$R=R_0 e^{\frac{3}{3-n}\delta}$  

## 三、Maclaurin 椭球

考虑转动的自引力系统 $\rho = const$  
转动角速度 $\Omega$  
引力势的分布为 $\Phi = -\pi G \rho[A-A_1x_1^2-A_2y^2-A_3z^2]$  四极函数
其中$A_1+A_2+A_3=2$  
满足Poisson方橙  
$▽^2\Phi=4\pi G\rho$  
形式解
$\Phi =-G \rho \int\frac{d^3x'}{|\vec{x}-\vec{x'}|}$ 
其中展开
$\frac{1}{|\vec{x}-\vec{x'}|}=\sum^{\infty}_{l=0}\frac{r^l_<}{r_>^{l+1}}P_l(cos\theta)P_l(cos\theta')+[与\Phi相关项]$  
$r_<=min(r,r')$  
$r_>=max(r,r')$  
椭球的表面为  
$\frac{\sin^2\theta}{a^2}+\frac{\cos^2\theta}{c^2}=\frac{1}{R^2}$  
a半长轴 c半短轴  
$R=R(\theta)$  
$\Phi =-2\pi G \rho \sum^{\infty}_{l=0}P_l(cos\theta)\int_0^{\pi}\sin\theta'd\theta'P_l(cos\theta')\times(\int_0^r\frac{(r')^{l+2}}{r^{l+1}}dr'+\int_r^R\frac{r^l}{(r')^{l-1}}dr')$  
当l为奇数的时候积分=0  
取l=0,2项  
当$l\geq4 ,\cos\theta'$抵消  
$\Phi=-2\pi G\rho{   -\frac{1}{3}r^2+ \int_0^1\frac{dx}{ \frac{1}{a^2}+(\frac{1}{c^2}-\frac{1}{a^2})x^2  }  -(3\cos^2\theta-1) \frac{r^2}{4}\int^1_0dx(3x^2-1)\times\log[\frac{1}{a^2}+(\frac{1}{c^2}-\frac{1}{a^2})x^2]}$
其中$x=cos\theta'$  

$e^2=1-\frac{c^2}{a^2}$  
$A_1=A_2=\frac{(1-e^2)^{1/2}}{e^3}\sin^{-1}e-\frac{1-e^2}{e^2}$  
$A_3=\frac{2}{e^2}-\frac{2(1-e^2)^{1/2}}{e^3}\sin^{-1}e$  
$A=\frac{2a^2(1-e^2)^{1/2}}{e^3}\sin^{-1}e$  
流体静力学平衡
$\frac{d\vec{V}}{dt}=-\frac{1}{\rho}\bigtriangledown P-\bigtriangledown\Phi$  
其中 

$\frac{d\vec{V}}{dt}=-\Omega^2(x\vec{e_x}+y\vec{e_y})=\vec{\Omega}\times(\vec{\Omega}\times\vec{r})$

沿着y方向：  
沿着x方向：  
因为$\Phi$是四极函数  
$P=P_3(1-\frac{x^2+y^2}{a^2}-\frac{z^2}{c^2})$  
带入后  
$P_c=\phi G \rho^2c^2A_3$  
$\Omega^2=2\pi G \rho (A_1-\frac{A_3 c^2}{a^2})=2\pi G \rho [\frac{(1-e^2)^{1/2}}{e^3}(3-2e^2)\sin^{-1}e-\frac{3(1-e^2)}{e^2}]$  

转动惯量
$I=\frac{2}{5}Ma^2$  
$M=\frac{4}{3}a^3(1-e^2)^{1/2}\rho$  
角动量$J=I\Omega$  
转动动能$T=\frac{1}{2}I\Omega^2$  
$W=\frac{1}{2}\rho\int\Phi d^3x=-\frac{3}{5}(\frac{4\pi}{3})^2G\rho^2a^5\frac{sin^{-1}e}{e}(1-e^2)$  


$\frac{T}{|w|}=\frac{3}{2e^2}[1-\frac{e(1-e^2)^{1/2}}{sin^{-1}e}]-1$
 
## 四、 转动WD 无磁场 
转动动能
$T\sim M\Omega^2R^2\sim\frac{J^2}{MR^2}$  
J守恒  
$-\alpha_{3/2}\frac{GM^2}{R}+\kappa_{3/2}\frac{J^2}{MR^2}+\beta_{3/2}\frac{M^{5/3}}{R^2}=0$  NRD  
$-\alpha_{3}\frac{GM^2}{R}+\kappa_{3}\frac{J^2}{MR^2}+\beta_{3}\frac{M^{4/3}}{R^2}=0$  ERD  
求解ERD  
$0-\alpha_{3}\frac{GM^2}{R}(1-\frac{2T}{|w|})+\beta_{3}\frac{M^{4/3}}{R^2}$
求借M  
$M=[\frac{\beta_3}{\alpha_3 G(1-2T/|w|)}]=M_0(1+\frac{3T}{|w|})$  
$\frac{T}{|w|}|_{max}=0.0074$  
$M_{ch}=1.02 M_{ch,0}$

$M_{ch,0}$无旋转时的钱德拉塞卡极限

证明：$\frac{T}{|w|}|_{max}\leq0.0074$ (均匀转动，n=3)

1.考虑球形的对称星  
Kepler转动(赤道) Break up

$v^2=\Omega^2 R^2=\frac{GM}{R}$  
$\Omega_{max}=(\frac{GM}{R^3})^{1/2}$  
$W=-\frac{3(\Gamma-1)}{5\Gamma-6}\frac{GM^2}{R}$  
当$\Gamma=\frac{4}{3}, n=3$  
$|w|=\frac{3}{2} \frac{GM^2}{R}$  

$T=\frac{1}{2}IR^2$
$I=\int_0^M\frac{2}{3}r^2dm=\frac{2}{3}M<r^2>$
$I=\frac{2}{3}\frac{MR^2}{\xi_1^4|\theta'(\xi_1)|}\int_0^{\xi_1}\theta^n\xi^4d\xi$  
$\int_0^{\xi_1}\theta^n\xi^4d\xi=0.851$  
$<r^2>=0.11303 R^2$  
$\frac{T}{|w|}|_{max}=\frac{}{}=0.025$    at break up

对于不可压缩流体 $\rho=const$ 

$n=0, \Gamma=\infty$  
$|w|=\frac{3}{5}\frac{GM^2}{R}$ 
$I=\frac{2}{5}MR^2$  
$T=\frac{1}{5}MR^2\Omega^2$  
$\frac{T}{|w|}=\frac{1}{3}$ at break up 

$\frac{T}{|w|}|_{实际}\leq\frac{T}{|w|}|_{不可压缩流体}$

椭球 赤道R_1>R 质量的整体分布不受影响

$\Phi=-\frac{GM}{r}$  
离心势:沿着z轴转动  
$\Phi_c=-\frac{1}{2}\Omega^2(x^2+y^2)=-\frac{1}{2}\Omega^2r^2sin^2\theta$  

$0=\frac{1}{\rho}$
积分后
$h+\Phi+\Phi_c=K$
单位质量的 焓

考虑非转动的情形 $\Omega=0$  
$K=-\frac{GM}{R}$  
$h+\Phi+\Phi_c=K=-\frac{GM}{R}$ 
有效势  
$\Phi_{eff}=\Phi+\Phi_c=-\frac{GM}{r}-\frac{1}{2}\Omega^2r^2sin^2\theta$  
在赤道r=90度
$\Phi_{eff}=-\frac{GM}{r}-\frac{1}{2}\Omega^2r^2$  
当$r=r_c=(GM/\Omega^2)^{1/3}$  
$\Phi_{eff,max}=-\frac{3GM}{2r_c}$
表面$P->0$  
$h=\frac{\Gamma}{\Gamma-1}\frac{P}{\rho}->0$  
$-\frac{3GM}{2r_c}=-\frac{GM}{R_1}$  

$R_{1,max}=\frac{3}{2}R$  
最大的
$\Omega_{max}...$

$\frac{T}{|w|}=[(\frac{2}{3})^{3/2}\times\frac{T}{|w|}|_{球形}]$  
$\frac{T}{|w|}=0.544^2*0.025 =0.0074$ at break up 


$M_{ch}=M_{ch,0}\times1.02$
质量仅增加2% , 均匀转动 刚体

3. differentially rotating 

$\Omega(r)$  
$\frac{T}{|w|}=0.14$  
$M_{ch}=M_{ch,0}\times2.5(\frac{2}{\mu_e})^2M_{\odot}$  
$\frac{T}{|w|}=0.26$  
$M_{ch}=M_{ch,0}\times5.1(\frac{2}{\mu_e})^2M_{\odot}$  