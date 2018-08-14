---
title: Finite arithmetic series
layout: single
not_pagination: true
toc: true
toc_label: "Finite arithmetic series"
sidebar: 
  nav: algebra2
---

## reference :
[Khanacademy algebra_ll_series](https://www.khanacademy.org/math/algebra2/sequences-and-series/alg2-seq-and-series/a/evaluating-arithmetic-series-guided-practice)

## Summation notation 

### sigma notation
$$
\sum 
$$

### example

$$
\sum_{i=1}^{10} i = 1+2+3+...+9+10 
$$

$$
\sum_{i=1}^{100} i = 1+2+3+...+99+100 
$$

$$
\sum_{i=0}^{50} \pi i^2 =\pi 0^2 + \pi 1^2 + \pi 2^2+... + \pi 49^2+\pi 50^2 
$$


## Arithmetic series
$$
\begin{align*}
\left\{1,2,3,....,n\right\} \\
s_n &= 1+2+3+...+ n \\
s_n &= n + (n-1) + (n-2) + ... + 1 \\
s_n+s_n &= 2s_n = (n+1)+(n+1) + (n+1)+...+(n+1) \\
s_n &=\frac{n(n+1)}{2}
\end{align*}
$$
 
## arithmetic sequence
$$
 \left\{a, a+d, a+2d, ..., a+(n-1)d \right\}
$$

## arithmetic series formula
$$
\begin{align*}
s_n &= a+a+d + a+2d +.. +a+(n-1)d \\
s_n &=a+n(-1)d+a+(n-2)d + a+(n-3)d+ ... +a  \\
2s_n &= 2a+(n-1)d + 2a+(n-1)d + 2a+(n-1)d +...+ 2a+ (n-1)d \\
2s_n &= n(2a + (n-1)d) \\
s_n &= \frac{n(2a+(n-1)d)}{2} \\
s_n &= n* (\frac{ a+a+(n-1)d }{2})
\end{align*}
$$

### the sum of an arithmetic series
$$
\begin{align*}
s_n= \frac{(a_1+a_n)}{2}*n
\end{align*}
$$


### Find the value of n for this series and Find the sum
$$
\begin{align*}
3+5+7+..+401= \\
n &= \frac{(401-3)}{2}+1 \\
n &=200 \\
\frac{3+401}{2}*n &= 40400 \\
\\
11+20+29+...+4052= \\
n &= \frac{(4042-11)}{9}+1 \\
n &=450 \\
\frac{4052+11}{9}*n &= 914175 \\
\end{align*}
$$

## Work Example

### base
 $$
\begin{align*}
\sum_{k=1}^{550}(2k+50) &= 2(1)+50+ 2(2)+50 + ... + 2(550)+50 \\
\\
s_{550} &= 52 + 54 + 56 + ...+ 1150 \\
s_{550} &= 1150 + 1148+ 1146 +...+ 52 \\
2s_{550} &= 1202 + 1202 +...+ 1202 = 1202 * 550 \\
s_{550} &= \frac{1202*550 }{2} \\
s_{550} &= \frac{52 + 1150}{2}*550
\end{align*}
$$

### sum expression

$$
-50+(-44)+(-38)+...+ 2038+ 2044
$$

**Find the value of n for this series**

$$
\begin{align*}
n &= \frac{2044-(-50)}{6}+1 \\
n &= 350 \\
s_{350} &= \frac{-50+2044}{2}*350 \\
s_{350} &= 348,950 \\
Sum expression \\
& \sum_{k=1}^{350} (6(k-1)-50)
\end{align*}
$$



### Recursive formula

$$
\begin{align*}
a_i &= a_i-1 + 11 \\
a_1 &= 4 \\
\end{align*}
$$
**Find sum of first 650 terms of sequence!**
$$
\left\{ 4 + 15 + 26 + ..+ (4+11(n-1))\right\} \\
$$

$$
\begin{align*}
4+11(650-1) &=  7143 \\
\\
s_{650} &= \frac{ 4+7143 }{2} * 650 = 2,322,775 \\
\end{align*}
$$


## Proof of finite arithmetic series formula
[Proof of finite arithmetic series formula](https://www.khanacademy.org/math/algebra2/sequences-and-series/alg2-seq-and-series/v/alternate-proof-to-induction-for-integer-sum)
