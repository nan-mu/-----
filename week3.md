## 1-23

$$
\because u(t)\to e^{-at}u(t)\\
\therefore \delta(t)\to(e^{-at}u(t))'=e^{-at}\cdot\delta(t)-ae^{-at}u(t)
$$

## 1-补充题1

$$
\because
\begin{bmatrix}
1&1&0\\
2&1&0\\
1&3&u(t)
\end{bmatrix}\to
\begin{bmatrix}
3e^{-2t}\\
e^{-t}+4e^{-2t}\\
1-e^{-t}+4e^{-2t}
\end{bmatrix}\\
设\begin{bmatrix}
3e^{-2t}\\
e^{-t}+4e^{-2t}\\
1-e^{-t}+4e^{-2t}
\end{bmatrix}=\begin{bmatrix}
a\\
b\\
c
\end{bmatrix}\\
则经过变换：\\
\begin{bmatrix}
1&1&0&a\\
2&1&0&b\\
1&3&u(t)&c
\end{bmatrix}\to
\begin{pmatrix}1&2&2u(t)&-7a+3b+2c\end{pmatrix}\\
\therefore所求y(t)=2+e^{-t}-e^{-2t}
$$

## 2-1

### (a)

$$
由\begin{bmatrix}
2+p+p^{-1}&-p^{-1}\\
-p^{-1}&p^{-1}+1+2p
\end{bmatrix}
\begin{bmatrix}
i_1(t)\\i_2(t)
\end{bmatrix}=
\begin{bmatrix}
e(t)\\0
\end{bmatrix}变换得\\
\begin{bmatrix}0&2p\end{bmatrix}\begin{bmatrix}
i_1(t)\\i_2(t)
\end{bmatrix}=v_o(t)=
\begin{bmatrix}
e(t)\frac{2p}{2p^3+5p^2+5p+3}\\0
\end{bmatrix}\\
即\,\,\,\,2v_0'''(t)+5v_o''(t)+5v_o'(t)+3v_o(t)=2e'(t)
$$

### (b)

$$
由\begin{bmatrix}
R+Cp^{-1}+Lp&Mp\\
-Mp&Lp+Cp^{-1}+R
\end{bmatrix}\begin{bmatrix}
i_1(t)\\i_2(t)
\end{bmatrix}=\begin{bmatrix}
e(t)\\0
\end{bmatrix}变换得\\
\begin{bmatrix}0&R\end{bmatrix}\begin{bmatrix}
i_1(t)\\i_2(t)
\end{bmatrix}=v_o(t)=
\begin{bmatrix}
R\frac{R\cdot\frac{e(t)Mp^2}{Lp^2+Rp+C}}{\frac{M^2p^4}{Lp^2+Rp+C}+Lp^2+Rp+C}\\0
\end{bmatrix}\\=\begin{bmatrix}
\frac{R^2Mp^2e(t)}{(L^2+M^2)p^4+2LRp^3+(R^2+2LC)p^2+2RCp+C^2}\\0
\end{bmatrix}\\
即\,\,\,(L^2+M^2)v''''_o(t)+2LRv'''_o(t)+(R^2+2LC)v''_o(t)+2RCv'_o(t)+C^2v_o(t)=R^2Me''(t)
$$

### (c)

$$
由\begin{bmatrix}
R^{-1}+Cp&0\\
-\frac\mu{R_1}&L_1p^{-1}+C_1p
\end{bmatrix}\begin{bmatrix}
v_1(t)\\v_o(t)
\end{bmatrix}=\begin{bmatrix}
i(t)\\0
\end{bmatrix}变换得\\
\begin{bmatrix}
0&1
\end{bmatrix}\begin{bmatrix}
v_1(t)\\v_o(t)
\end{bmatrix}=\frac{\frac{\mu Rp}{R_1L_1+R_1C_1p^2}}{1+CRp}i(t)=v_o(t)\\
即\,\,\,CC_1RR_1v'''_o(t)+R_1C_1v''_o(t)+L_1CRR_1v'_o(t)+R_1L_1v_o(t)=\mu Ri'(t)
$$

### (d)

$$
由\begin{bmatrix}
R^{-1}&-Cp\\
\mu&-1
\end{bmatrix}\begin{bmatrix}
v_1(t)\\v_o(t)
\end{bmatrix}=\begin{bmatrix}
\frac{e(t)}R\\0
\end{bmatrix}变换得\\
\begin{bmatrix}
0&1
\end{bmatrix}\begin{bmatrix}
v_1(t)\\v_o(t)
\end{bmatrix}=\frac{\frac{e(t)}R}{\frac1{R\mu}-Cp}\\
即v_o(t)-CR\mu v_o'(t)=\mu e(t)
$$

