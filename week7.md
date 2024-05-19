# week7

## 3-2

$$
T=\frac1f=2\times10^{-4}s\\
a_n=\frac{2E\tau}{T}\text{Sa}(\frac{n\pi\tau}{T})\\
b_n=0\\
\therefore a_0=\frac{E\tau}{T}=1,a_1\approx1.39\\a_2\approx1.32,a_3\approx1.21
$$

## 3-3

### (1) (2)

$$
\begin{array}l
间隔f_1=\frac1{T_1}=1000kHz\\
带宽f_{B1}=\frac1{\tau_1}=2000kHz\\
间隔f_2=\frac1{T_2}=\frac{1000}3kHz\\
带宽f_{B2}=\frac1{\tau_2}=\frac{2000}3kHz\\
\end{array}
$$

### (3) (4)

$$
b_n=0,
a_n=\frac{2E\tau}{T}Sa(\frac{n\pi\tau}T)\\
\therefore \frac{a_1}{a_2}=\frac{E_1\tau_1\sin(\frac{\pi\tau_1}{T_1})T_2^2}{E_2\tau_2\sin(\frac{\pi\tau_2}{T_2})T_1^2}=\frac13\\

\frac{a_{11}}{a_{23}}=\frac{E_1\tau_1\sin(\frac{\pi\tau_1}{T_1})T_2^2}{E_2\tau_2\sin(\frac{3\pi\tau_2}{T_2})T_1^2}=1\\
$$

## 3-4

$$
f(t)=\left\{\begin{array}l
E-\frac{2E}{T}t&-\frac T2<t<0\\
\frac{2E}{T}t&0<t<\frac T2
\end{array}\right.\\
b_n=0,a_n=\frac2T\int^{\frac T2}_{-\frac T2}f(t)\cos(n\frac{2\pi}Tt)dt,a_0=\frac1T\int^{\frac T2}_{-\frac T2}f(t)dt=0\\
\therefore a_n=\frac2T(\int^{\frac T2}_0\frac{2E}{T}t\cos(n\frac{2\pi}Tt)dt-\int^0_{-\frac T2}\frac{2E}{T}t\cos(n\frac{2\pi}Tt)dt+\int^0_{-\frac T2}E\cos(n\frac{2\pi}Tt)dt)\\
=\frac{4E}{n\pi T}\int^{\frac T2}_0td\sin(\frac{2\pi n}Tt)\\
=\frac{4E}{n\pi T}(t\sin(\frac{2\pi n}Tt)|^{\frac T2}_0-\int^{\frac T2}_0\sin(\frac{2\pi n}Tt)dt)\\
=\frac{4E}{n\pi }(\frac 12\sin(\pi n)+\frac 1{2\pi n}\cos(\pi n\frac T2)-\frac 1{2\pi n})
=\left\{\begin{array}l
0&(n=2,4,\cdots)\\
-\frac{4E}{(n\pi)^2}&(n=1,3,\cdots)
\end{array}\right.
$$

## 3-7

$$
\begin{array}l
(a) 不含直流，不含正弦，含余弦\\
(b) 不含直流，含正弦，不含余弦\\
(c) 不含直流，含正弦，不含余弦\\
(d) 不含直流，含正弦，不含余弦\\
(e) 含直流，不含正弦，含余弦\\
(f) 含直流，含正弦，不含余弦
\end{array}
$$

