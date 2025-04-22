---
作成日: 2025-04-23 02:04
ID: DEF-1745341470
出典:
  - "[[RFB-工学教程 ベクトル解析]]"
---

# ベクトル空間（Definition）

## 内容（Definition）

[[集合]] $R$ の任意の元 $\boldsymbol{A} , \boldsymbol{B}$ に対して，和 $\boldsymbol{A} + \boldsymbol{B} \in R$ と，[[体]] $\mathbb{K}$ の任意の元 $a \in \mathbb{K}$ によつスカラー倍 $a \boldsymbol{A} \in R$ が定義されていて，以下のような性質を満たすとき，集合 $R$ を $\mathbb{K}$ 上の **ベクトル空間** または **線形空間** という．

1. $\boldsymbol{A} + \boldsymbol{B} = \boldsymbol{B} + \boldsymbol{A}$
2. $(\boldsymbol{A} + \boldsymbol{B}) + \boldsymbol{C} = \boldsymbol{A} + (\boldsymbol{B} + \boldsymbol{C})$
3. $\boldsymbol{0} + \boldsymbol{A} = \boldsymbol{A}$
4. $(-1)\boldsymbol{A} = -\boldsymbol{A}$
5. $a(\boldsymbol{A} + \boldsymbol{B}) = a\boldsymbol{A} + a\boldsymbol{B}$
6. $(a + b)\boldsymbol{A} = a\boldsymbol{A} + b\boldsymbol{B}$
7. $a(b\boldsymbol{A}) = (ab)\boldsymbol{A}$
8. $1\boldsymbol{A} = \boldsymbol{A}$

ただし，上記について $\boldsymbol{A},\boldsymbol{B},\boldsymbol{C} \in R$ ， $a,b \in \mathbb{K}$ ， $\boldsymbol{0} \in R$ は **ゼロベクトル** である．

$R$ の元を普通は太字で書かれ， **ベクトル** と呼ばれる．
$\mathbb{K}$ の元は普通は小文字で書かれ， **スカラー** と呼ばれる．

## 例・補足（Examples / Notes）

- どんなベクトル列 $A_{1},A_{2}, \ldots ,A_{n}$ についても，スカラー列  $\alpha_{1},\alpha_{2},\ldots,\alpha_{n}$ を用いて，$\alpha_{1}A_{1} + \alpha_{2}A_{2} + \cdots +\alpha_{n}A_{n}$ とすることができる．この形の元を **線形結合** または **一次結合** と呼ぶ．
- どんなベクトル空間の元 $\boldsymbol{A} \in R$ についても，必要なだけベクトルを選び，線形結合の形で表すことができる．

## 関連項目（Related Notes）

- [[線形独立・線形従属]]
- [[基底]]
- [[内積]]
- [[数ベクトル空間の内積]]
- [[加群]]
---
#定義 #線形代数 #ベクトル空間