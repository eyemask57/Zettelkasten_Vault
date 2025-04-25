---
作成日: 2025-04-26 02:26
ID: NOTE-1745602012
出典:
---

# Lagrange式時間微分

## 直交座標系のLagrange時間微分

[[Lagrange式時間微分]] は $\dfrac{D}{Dt}$ と表し，[[Euler式時間微分]]を用いて $\dfrac{D}{Dt} \coloneqq \boldsymbol{u} \cdot \nabla + \dfrac{\partial}{\partial t}$ となる．[[変数]]の組は $(x_{0},t)$ である．

$A = A(\boldsymbol{x},t) = A(\boldsymbol{x}(\boldsymbol{x}_{0},t),t) = A(\boldsymbol{x}_{0},t)$ として，[[全微分]]を考えると以下のようになる．
$$
\begin{align}
\frac{D}{Dt} A(\boldsymbol{x}_{0},t)
&= \frac{\partial A}{\partial t}(\boldsymbol{x},t) + \frac{D x_{i}}{D t} \frac{\partial A}{\partial x_{i}}(\boldsymbol{x},t)\\
&= \left(\frac{\partial}{\partial t} + u_{i}\frac{D}{Dt} \right)A(\boldsymbol{x},t)\\
&= \left\{ \frac{\partial}{\partial t} + (\boldsymbol{u} \cdot \mathrm{grad})\right\}A(\boldsymbol{x},t)\\
&= \left(\boldsymbol{u} \cdot \nabla + \dfrac{\partial}{\partial t}\right)A(\boldsymbol{x},t)
\end{align}
$$

### ベクトル

対象がベクトル量 $\boldsymbol{A}$ でも同様に当てはまる．
$$
\frac{D}{Dt}\boldsymbol{A}(\boldsymbol{x}_{0},t)
= (\boldsymbol{u} \cdot \nabla)\boldsymbol{A}(\boldsymbol{x},t) + \dfrac{\partial}{\partial t}\boldsymbol{A}(\boldsymbol{x},t)
$$

各成分について書くと，$\boldsymbol{A} = A_{i}\boldsymbol{e}_{i}$ と書くことができ，
$$
\frac{D}{Dt}A_{i}(\boldsymbol{x}_{0},t)
= \left(\boldsymbol{u} \cdot \nabla + \dfrac{\partial}{\partial t}\right)A_{i}(\boldsymbol{x},t)
$$

## 直交曲座標系のLagrange時間微分



## 関連項目（Related Notes）

- [[流体運動の記述]]

---
#Note #物理学 #流体力学 