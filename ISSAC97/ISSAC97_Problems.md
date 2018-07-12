# ISSAC '97 Challenge Problem (Translated in Japanese)

## 問1：
256次のヒルベルト行列の2ノルムの条件数を、有効数字4桁で求めよ。
  
## 問2：
$$
P = \int_{1}^{6} x^{x^x} dx
$$
の値を、有効数字7桁で求めよ。

## 問3：
$$
\sum_{k=1}^{\infty} \, (n^\pi + n^2 + n^{\sqrt{2}} +1 )^{-1/3}
$$
の値を、有効数字14桁で求めよ。

## 問4：
$$
(x+1)^{2000} (x^2 + x + 1)^{1000} (x^4+x^3+x^2+x+1)^{500}
$$
を展開して得られる多項式について、$x^{3000}$
の係数を有効数字13桁で求めよ。

## 問5：  
1000次のラゲール多項式の最大の零点を、有効数字12桁で求めよ。  
ここでラゲール多項式とは、
$$
\begin{aligned}
& L_{0}(x) = 1, \, L_{1}(x) = -x+1 \\
& L_{n}(x) = \frac{2n-1-x}{n} L_{n-1}(x) - \frac{n-1}{n} L_{n-2}(x) （n>1）
\end{aligned}
$$
を満足する多項式である。

## 問6：
以下の4つの多項式から成る多項式の集合について、そのグレブナー基底を計算せよ。
$$
8w^2 + 5wz - 4wy + 2wz + 3w + 5x^2 + 2xy - 7xz - 7x + 7y^2 - 8yz - 7y + 7z^2 - 8z + 8 \, ;\\
3w^2 - 5wx - 3wy - 6wz + 9w + 4x^2 + 2xy - 2xz + 7x + 9y^2 + 6yz + 5y + 7z^2 + 7z + 5 \, ;\\
-2w^2 + 9wx + 9wy - 7wz - 4w + 8x^2 + 9xy - 3xz + 8x + 6y^2 - 7yz + 4y - 6z^2 + 8z + 2 \, ;\\
7w^2 + 5wx + 3wy - 5wz - 5w + 2x^2 + 9xy - 7xz + 4x - 4y^2 - 5yz + 6y - 4z^2 - 9z + 2
$$

## 問7：
$$
\int_{0}^{1} x^2 \, Li_{3}(\frac{1}{x+1}) \, dx
$$
を求めよ。
なお、$Li_{n}(z)$は、以下の式で定義される多重対数関数である。
$$
Li_{n}(z) = \sum_{k=1}^{\infty} \, \frac{z^k}{k^n}
$$

## 問8：
$$
\begin{aligned}
f(x) &=  \tan(\tanh(\sin(x))) + \tanh(\sin(\tan(x))) + \sin(\tan(\tanh(x))) − \tan(\sin(\tanh(x))) \\
&− \sin(\tanh(\tan(x))) − \tanh(\tan(\sin(x))) − \tan(\sinh(\tanh(x))) − \sinh(\tanh(\tan(x))) \\
&− \tanh(\tan(\sinh(x))) + \tan(\tanh(\sinh(x))) + \tanh(\sinh(\tan(x))) + \sinh(\tan(\tanh(x)))
\end{aligned}
$$
$$
\begin{aligned}
g(x) &= \sinh(\tanh(\sin(x))) + \tanh(\sin(\sinh(x))) +\ sin(\sinh(\tanh(x))) − \sinh(\sin(\tanh(x))) \\
&− \sin(\tanh(\sinh(x))) − \tanh(\sinh(\sin(x))) − \tan(\sinh(\sin(x))) − \sinh(\sin(\tan(x))) \\
&− \sin(\tan(\sinh(x))) + \tan(\sin(\sinh(x))) + \sin(\sinh(\tan(x))) + \sinh(\tan(\sin(x)))
\end{aligned}
$$
以上のように$f(x), \, g(x)$をおくとき、
$$
\lim_{x \to 0} \frac{f(g(x))}{g(f(x))}
$$
の値を有効数字9桁で求めよ。

## 問9：
次の積分方程式
$$
\int_{0}^{1} \, \exp(x+y+x^2+xy+y^2+x^2 y^2) \, \lambda f(y) \, dy = \lambda f(x)
$$
を満たす最大の固有値$\lambda$を、有効数字13桁で求めよ。

## 問10：
以下の初期値問題を考える。
$$
\frac{d^2y}{dx^2} = x^3+y^3+(\frac{dy}{dx})^3, \, y(0)=0, \, y'(0)=0
$$
この初期値問題が$x=r$に特異点を持つような、最小の実数$r$の最小値を求めよ。  
また、$y(r)$が発散するか特定の値をとるか答えよ。  
特定の値をとる場合、その値を有効数字13桁で求めよ。