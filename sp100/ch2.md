# 第2章 線形代数の基礎

1. 連立方程式

    1. 

    
    $$\mathrm{A}=\left( \begin{array}{rrr} -2 & -4 & -3 \\ 3 & 3 & -4 \\ -5 & 2 & 3 \end{array} \right), b=\left( \begin{array}{r} -29 \\ 12 \\ -17 \end{array} \right), x \in \mathbb{R}^3$$
    とします．
    このとき，方程式 $$\mathrm{A}x-b=0$$ を解いてください．
2. （連立方程式，優決定）
    $$\mathrm{A}=\left( \begin{array}{rrr} 1 & 1 \\ 1 & -1 \\ 0 & 1 \end{array} \right), b=\left( \begin{array}{r} 1 \\ 1 \\ 2 \end{array} \right), x \in \mathbb{R}^2$$
    とします．
    - このとき，方程式 $$\mathrm{A}x-b=0$$ を解いてください．
    - $$n$$ 次元ベクトル $$v$$ のノルム $$\|v\|$$ を $$\|v\| = \sqrt{\sum_{i=1}^n v_i^2}$$ とします．$$\|\mathrm{A}x-b\|$$ が最小となる $$x$$ を求めてください．
3. （連立方程式，劣決定）
    $$\mathrm{A}=\left( \begin{array}{rrr} 2 & 4 & 1 &-1 \\ 1 & 2 & -1 & 1 \\ 2 & 1 & 1 & 2 \\ 1 & 3 & 2 & -3 \end{array} \right), b=\left( \begin{array}{r} 1 \\ 2 \\ -2 \\ 0 \end{array} \right), x \in \mathbb{R}^4$$
    とします．
    - このとき，方程式 $$\mathrm{A}x-b=0$$ を解いてください．
    - $$n$$ 次元ベクトル $$v$$ のノルムを $$\|v\| = \sqrt{\sum_{i=1}^n v_i^2}$$ とします．$$\mathrm{A}x-b=0$$ の解 $$x$$ のうち， $$\|x\|$$ が最小となるものを求めてください．
4. （連立方程式，ランク落ち）
5. （逆行列）
    $$\mathrm{A}=\left( \begin{array}{rrr} -2 & -4 & -3 \\ 3 & 3 & -4 \\ -5 & 2 & 3 \end{array} \right), b=\left( \begin{array}{r} -29 \\ 12 \\ -17 \end{array} \right), x \in \mathbb{R}^3$$
    とします．
    - $$\mathrm{A}$$の逆行列$$\mathrm{A}^{-1}$$を計算してください．
    - $$\mathrm{A}^{-1}b$$ を計算し，$$\mathrm{A}x-b=0$$ の解 $$x$$ と比較してください．
6. （行列式と逆行列の存在条件）
    $$i, j \in \mathbb{N}, a_{ij} \in \mathbb{C}$$ のとき，
    行列 $$\mathrm{A}= \left( \begin{array}{rrrr} a_{11} & a_{12} & \cdots & a_{1n} \\ a_{21} & a_{22} & \cdots & a_{2n} \\ \vdots & \vdots & & \vdots \\ a_{n1} & a_{n2} & \cdots & a_{nn} \end{array} \right)$$ の行列式を $$\det{(\mathrm{A})}$$
    または $$\left| \begin{array}{rrrr} a_{11} & a_{12} & \cdots & a_{1n} \\ a_{21} & a_{22} & \cdots & a_{2n} \\ \vdots & \vdots & & \vdots \\ a_{n1} & a_{n2} & \cdots & a_{nn} \end{array} \right|$$ と表します．
    - $$i \in \mathbb{N}, x_i \in \mathbb{C}, \mathrm{V}= \left( \begin{array}{rrrr} 1 & 1 & 1 & 1 \\ x_1 & x_2 & x_3 & x_4 \\ x_1^2 & x_2^2 & x_3^2 & x_4^2 \\ x_1^3 & x_2^3 & x_3^3 & x_4^3 \end{array} \right)$$ のとき，
        $$\det{(\mathrm{V})}$$を計算してください．
    - $$\mathrm{V}$$の逆行列が存在するための条件を示してください．
7. （対角行列，三角行列の行列式）
    - 対角行列，上三角行列，下三角行列の行列式を計算してください．
8. （固有値，固有ベクトル）
    ４次元ベクトル $$x = \left( \begin{array}{r} a \\ b \\ c \\ d \end{array} \right)$$ に対し，要素を巡回的にシフトした $$y = \left( \begin{array}{r} b \\ c \\ d \\ a \end{array} \right)$$を考えます．
    - $$y = \mathrm{P}x$$ となるような，4x4の行列 $$\mathrm{P}$$ を求めてください．
    - $$\mathrm{P}v = \lambda v$$ ($$\lambda$$はスカラー) となるようなベクトル $$v$$，すなわち，$$\mathrm{P}$$ の固有ベクトルをすべて求めてください．
9. （擬似逆行列）
    行列$$\mathrm{A}$$について，以下の4条件
    $$\mathrm{A}\mathrm{A}^{\dagger}\mathrm{A}=\mathrm{A},$$
    $$\mathrm{A}^{\dagger}\mathrm{A}\mathrm{A}^{\dagger}=\mathrm{A}^{\dagger},$$
    $$(\mathrm{A}\mathrm{A}^{\dagger})^*=\mathrm{A}\mathrm{A}^{\dagger},$$
    $$(\mathrm{A}^{\dagger}\mathrm{A})^*=\mathrm{A}^{\dagger}\mathrm{A}$$
    を満たす行列$$\mathrm{A}^{\dagger}$$をムーア・ペンローズの擬似逆行列といいます．ここで，$$\mathrm{A}$$が正則行列ならば，$$\mathrm{A}^{\dagger}=\mathrm{A}^{-1}$$を満たします．また，$$\mathrm{A}$$の特異値分解が$$\mathrm{A}=\mathrm{U}\mathrm{\Sigma}\mathrm{V}$$として与えられるとき，$$\mathrm{A}^{\dagger}$$は$$\mathrm{A}^{\dagger}=\mathrm{U}\mathrm{\Sigma}^{\dagger}\mathrm{V}$$として与えられます．
    - $$\mathrm{A}=\left( \begin{array}{rrr} -2 & -4 & -3 \\ 3 & 3 & -4 \end{array} \right), b=\left( \begin{array}{r} -29 \\ 12 \end{array} \right), x \in \mathbb{R}^3$$
        のとき，$$\mathrm{A}^{\dagger}b$$を計算し，$$\mathrm{A}x-b=0$$ の解 $$x$$ と比較してください．
    - $$\mathrm{A}=\left( \begin{array}{rrr} -2 & -4 \\ 3 & 3 \\ -5 & 2 \end{array} \right), b=\left( \begin{array}{r} -29 \\ 12 \\ -17 \end{array} \right), x \in \mathbb{R}^2$$
        のとき，$$\mathrm{A}^{\dagger}b$$を計算し，$$\mathrm{A}x-b=0$$ の解 $$x$$ と比較してください．
10. （行列の定値性）
11. 行列の対角化
12. 特異値分解
13. 線形独立と基底
14. 内積と正規直交基底
15. 線形変換とユニタリ変換
16. 離散フーリエ変換
17. 実・複素ベクトル空間以外のベクトル空間（ヒルベルト空間）。特にL2
    自乗可積分関数の集合$$L^2=\{f:\mathbb{R} \rightarrow \mathbb{C} | \int_{-\infty}^{\infty} |f(x)|^2 dx < \infty \}$$を考える．
    - $$L^2$$ がベクトル空間となるように加法とスカラー乗法を定義せよ．また，定義した2つの演算を用いて，$$L^2$$がベクトル空間の公理を満たすことを確かめよ．
    - $$L^2$$が計量ベクトル空間となるように内積を定義せよ．
    - $$L^2$$
18. 線形作用素
19. フーリエ変換
20. カーネルトリック

解析

1. 微分
2. テイラー展開を用いたオイラーの公式の証明
3. 偏微分
4. （勾配ベクトル）
    関数 $$f: \mathbb{R}^n \rightarrow \mathbb{R}$$ のベクトル $$x \in \mathbb{R}^n$$ での微分（勾配）を，
    $$\frac{\partial f}{\partial x} = \left( \frac{\partial f}{\partial x_1} \frac{\partial f}{\partial x_2} \cdots \frac{\partial f}{\partial x_n} \right)^\top$$
    と定義します．
    また，関数 $$g: \mathbb{R}^n \rightarrow \mathbb{R}^m$$ のベクトル $$x \in \mathbb{R}^n$$ での微分（勾配）を，
    $$\frac{\partial g}{\partial x} = \left( \begin{array}{rrrr} \frac{\partial g_1}{\partial x_1} & \frac{\partial g_2}{\partial x_1} & \cdots & \frac{\partial g_m}{\partial x_1} \\ \frac{\partial g_1}{\partial x_2} & \ddots & & \vdots \\ \vdots & & \ddots & \vdots \\ \frac{\partial g_1}{\partial x_n} & \cdots & \cdots & \frac{\partial g_m}{\partial x_n} \end{array} \right)^\top$$
    と定義します．
    ベクトル $$a, x \in \mathbb{R}^n$$ を縦ベクトル，行列 $$\mathrm{A}, \mathrm{E} \in \mathbb{R}^{n \times n}$$ をそれぞれ対称行列，単位行列とするとき，以下の等式を証明してください．
    - $$\frac{\partial}{\partial x} x^\top = \mathrm{E}$$
    - $$\frac{\partial}{\partial x} x^\top a = a$$
    - $$\frac{\partial}{\partial x} a^\top x = a$$
    - $$\frac{\partial}{\partial x} x^\top \mathrm{A} x = 2 \mathrm{A} x$$
5. （勾配，行列）
    実数のスカラー関数 $$g(\mathbf X)$$ の行列 $$\mathbf X$$ についての偏微分が
    $$\frac{\partial g}{\partial \mathbf X}=     \begin{bmatrix}     \displaystyle      \frac{\partial g}{\partial x_{11}}&\cdots&\displaystyle \frac{\partial g}{\partial x_{1N}}\\     \vdots& &\vdots\\     \displaystyle \frac{\partial g}{\partial x_{M1}}&\cdots&\displaystyle \frac{\partial g}{\partial x_{MN}}\end{bmatrix}$$
    で定義されるとき，以下の等式を証明せよ．
    - $$\frac{\partial}{\partial \mathbf{X}}{\mathrm{tr}}(\mathbf{X})={\mathbf{I}}$$
    - $$\frac{\partial}{\partial \mathbf{X}}{\mathrm{tr}}({\mathbf{A}}{\mathbf{X}})={\mathbf{A}}^{\top}$$
    - $$\frac{\partial}{\partial \mathrm{X}}{\mathrm{tr}}({\mathbf{A}}{\mathbf{X}}^{\top})={\mathbf{A}}$$
    - $$\frac{\partial}{\partial \mathbf{X}}{\mathrm{tr}}({\mathbf{A}}{\mathbf{X}}{\mathbf{B}})={\mathbf{A}}^{\top}{\mathbf{B}}^{\top}$$
    ただし，$$\mathbf{A}$$は各行列積が定義できるサイズとする．
6. （微分の連鎖律）
    $$f = f_2(\mathrm{W}_2 f_1(\mathrm{W}_1 x + b_1) + b_2)$$ とします．
    - $$\frac{\partial f}{\partial A_2}, \frac{\partial f}{\partial b_2}$$ を計算してください．
    - $$\frac{\partial f}{\partial A_1}, \frac{\partial f}{\partial b_1}$$ を計算してください．
    - $$\frac{\partial f}{\partial x}$$ を計算してください
7. 極値の計算
    関数 $$z=f(x, y)=x^{3}+y^{3}-3 x y$$ の極値をすべて求めよ
8. ヘッセ行列？
9. ラグランジュの未定乗数法
10. 常微分方程式
11. ラプラス変換
12. 偏微分方程式
13. 積分
14. 重積分
15. ヤコビ行列
16. たたみ込み積分

代数

1. 群・環・体の定義を述べ，それぞれの例を挙げてください．

確率統計

1. （確率モーメント）
    確率変数 $$X$$ が，それぞれ1/6 の確率で，$$-3, -2, -1, 1, 2, 3$$ のいずれかの値をとるものとします．
    - 期待値 $$E[X], E[X^2]$$をそれぞれ求めてください．
2. （期待値の線形性）
    $$E[aX+b] = aE[X] + b$$ であることを示してください．
3. （分散）
    確率変数 $$X$$ の分散は $$\mathrm{Var}(X) = E[X^2] - E[X]^2$$  であることを証明してください．
4. 確率分布
5. 最小二乗法
6. 最尤推定
7. 最大事後確率推定
8. ベイズ推定
9. 変分ベイズ推定
10. 分散共分散行列
11. 主成分分析
12. マハラノビス距離
13. p値と有意差

信号処理

1. 理想サンプリングとインパルス列
2. 線形時不変システムと畳み込み
3. 周期関数
4. 離散時間フーリエ変換
5. 離散フーリエ変換
6. フーリエ級数，フーリエ変換，離散時間フーリエ変換，離散フーリエ変換
7. z変換と離散フーリエ変換，ラプラス変換
8. 差分方程式

