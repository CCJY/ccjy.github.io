---
title: Geometric series
layout: single
not_pagination: true
toc: true
toc_label: "Geometric series"
sidebar: 
  nav: algebra2
---

## Geometric Series Intro

>$$
\sum_{n=1}^{\infty} \frac{1}{2}^{n-1}= 1+ \frac{1}{2} +\frac{1}{4} +\frac{1}{8}..
$$

## Geometric series with sigma notation

### Example

>$$
\begin{aligned}
\sum_{k=0}^{n} ar^{k} &= a+ ar + ar^3 + ar^3 + .. ar^n \\
s_n &= \frac{a(1-r^n)}{1-r} \\
\sum_{k=0}^{99} 2(3^k) &= 2*3^0 + 2*3^1 + ... + 2*3^{99} \\
s_{100} &= \frac {2(1-3^{100})}{1-3} = 3^{101}-1 \\
\end{aligned}$$

## Finite geometric series

### Example

1. **Sum of first 50 terms**

>$$
\begin{aligned}
1 + \frac{10}{11} + \frac{100}{121} ... \\
s_{50} = \frac{1(1-(\frac{10}{11})^{50})}{1-\frac{10}{11}}  \\
\end{aligned}
$$

2. $$ 1-0.99 + 0.99^2 - 0.99^3 + ...- 0.99^{79}  $$  
> $$
\begin{aligned}
s_{80} = \frac {1(1-(-0.99)^{80})}{1-(-0.99)} \\
\end{aligned}
$$

3. **Sum of 30 first terms**
> $$\begin{aligned}
    a_1 &= 10 \\
    a_i &= a_{i_1} * \frac{9}{10} \\
    a_2 &= a_1 * \frac{9}{10} \\ 
\\ 0+ 10* \frac{9}{10} +... + 10* (\frac{9}{10})^{29} \\
    s_{30} = \frac {10(1-(\frac{9}{10}^{30}))} {1 - \frac{9}{10}})) = 100(1-(\frac{9}{10})^{30}) \\ 
\end{aligned}$$

## Finite geometric series formula justification

$$
\begin{aligned}
a &= first term \\
r &= common ratio \\
n &= \text{ \# of terms} \\
s_n &= \text{sum of first n terms} \\
s_n &= a+ ar + ar^2 +....+ ar^{n-1} \\
-rs_n &= -ar -ar^2 -...-ar^{n-1}-ar^n \\
s_n-rsn_n &= a-ar^n \\
s_n(1-r) &= a(1-r^n) \\
s_n &= \frac{a(1-r^n)}{(1-r)} 
\end{aligned}
$$
## Reference  
[Khan academy](https://www.khanacademy.org/math/algebra-home/algebra2/sequences-and-series/alg2-geometric-sequence-series/v/series-as-sum-of-sequence)

