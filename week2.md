**(a)**
$$
f(t)=(\frac12t-u(t)\cdot t)\cdot(u(t+2)-u(t-2))
$$

**(b)**
$$
f(t)=u(t)+u(t-1)+u(t-2)
$$
**(c)**
$$
f(t)=E\sin(\frac\pi Tt)\cdot(u(t)-u(t-T))
$$
**(1)**
$$
F(t)=f(-t_0)
$$
**(2)**
$$
F(t)=f(t_0)
$$
**(3)**
$$
F(t)=u(\frac{t_0}2)
$$
**(4)**
$$
F(t)=u(-t_0)
$$
**(5)**
$$
F(t)=e^2-2
$$
**(6)**
$$
F(t)=\frac{\pi}6+\frac12
$$
**(7)**
$$
F(t)=1-e^{-j\omega t_0}
$$
**(1)**
$$
f_D=\frac{2\omega}\pi(\int^{\frac\pi\omega}_0\sin(\omega t)dt)=\frac2\pi
$$
**(2)**
$$
f_D=\frac\omega{2\pi}\int^{\frac\pi\omega}_{\frac\pi\omega}sin^2(\omega t)dt=\frac12
$$
**(3)**
$$
\because\sin(\omega t)和\cos(\omega t)都无直流分量
\\\therefore两者的线性组合也无直流分量\\
f_D=0
$$
**(4)**
$$
\because \cos(\omega t)无直流分量\\
\therefore f_D = K
$$
**(5)**
$$
C = \frac{C_1C_2}{C_1+C_2}\\
i(t)=C\frac{dEu(t)}{dt} = CE\delta(t)\\
又\because i(t)=C_1\frac{dv_{C1}}{dt}=C_2\frac{dv_{C2}}{dt}\\
\therefore v_{C1}=\int\frac{C_2}{C_1+C_2}E\delta(t)dt=\frac{C_2}{C_1+C_2}Eu(t)
\\v_{C2}=\int\frac{C_1}{C_1+C_2}E\delta(t)dt=\frac{C_1}{C_1+C_2}Eu(t)
$$
