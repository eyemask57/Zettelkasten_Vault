---
作成日: 2025-04-20 10:59
ID: LAW-1745114373
出典:
---

# 非圧縮性流れのNavier-Stokes方程式（Definition）

## 内容（Statement / Expression）

流体の密度 $\rho$ と運動粘性率 $\nu$ は定数，$p$ は未知関数，外力 $\boldsymbol{F}$ ，速度 $\boldsymbol{v}$ とするとき，以下の方程式
$$
\begin{aligned}
\nabla \cdot \boldsymbol{v} = 0\quad,\quad
\frac{\partial \rho}{\partial t} = \nabla \cdot(\rho \boldsymbol{v})\quad,\quad
\nu = \frac{\mu}{\rho} \\

\frac{\partial \boldsymbol{v}}{\partial t} + (\boldsymbol{v} \cdot \nabla)\boldsymbol{v}
 = - \frac{1}{\rho}\nabla p + \nu \nabla^{2} \boldsymbol{v} + \boldsymbol{F}
\end{aligned}
$$

が成り立つ．
## 解説・背景（Explanation / Context）

- 水などの基本的な物質は大抵の場合は非圧縮性流れとしてよい．
- 気体とか？
## 適用条件・制限（Scope / Assumptions）

- もちろん，本来のNavier-Stokes方程式はさらに複雑である．
- 非圧縮性流体のみに適応できる．
## 関連項目（Related Notes）

- [[HUB-流体力学]]
- [[PRB-円座標系の非圧縮性流体]]
- [[Bessel関数]]
---
#法則 #流体力学 #基礎方程式 #Navier-Stokes方程式 #非圧縮性流体