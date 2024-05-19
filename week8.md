# week8

## 3-16

### (a)

$$
f(t)=\frac{2E}TG_T(t)\\
\therefore F(\omega)=j\frac d{d\omega}(2ESa(\frac{\omega T}2))\\
=\frac{2jE}{\omega}(\cos(\frac{\omega T}2)-Sa(\frac{\omega T}{2}))
$$

### (b)

$$
F(\omega)=\int^T_0(E-\frac ETt)e^{-j\omega t}dt\\
=E\int^T_0e^{-j\omega t}dt-\frac ET\int^T_0te^{-j\omega t}dt\\
=\frac E{-\omega^2T}(j\omega T-1+e^{-j\omega T})
$$

### (c)

$$
F(\omega)=\int^T_0\sin(\frac{2\pi}T t)e^{-j\omega t}dt\\
=\frac E{2j}\int^T_0(e^{j(\frac{2\pi}T-\omega)t}-e^{-j(\frac{2\pi}T+\omega)t})\\
=\frac E2(e^{-j\omega T}-1)(\frac1{\omega-\frac{2\pi}T}-\frac1{\omega+\frac{2\pi}T})\\
$$

### (d)

$$
F(\omega)=-F_{上一题}(\omega)e^{j\omega\frac T2}\\
=\frac E2(e^{j\omega \frac T2}-e^{-j\omega\frac T2})(\frac1{\omega-\frac{2\pi}T}-\frac1{\omega+\frac{2\pi}T})\\
$$

## 3-24

$$
f(t)=g(t)\cos(\omega_0t)\\
F(\omega)=\frac1{2\pi}(\frac{E\tau}2Sa^2(\frac{\omega \tau}4)*(j\pi[\delta(\omega+\omega_0)-\delta(\omega-\omega_0)]))\\
=\frac\pi4[Sa^2(\tau\frac{\omega+\omega_0}4)+Sa^2(\tau\frac{\omega-\omega_0}4)]
$$

## 3-25

$$
F(\omega)=\mathcal F(g(t-1))\\
\varphi(\omega)=-\omega\\
F(0)=4\\
\int^{\infty}_{-\infty}F(\omega)d\omega=2\pi f(0)=2\pi\\
$$

![image-20240421211743488](C:\Users\nan\Documents\work\电路\信号与系统\week8\week8.assets\image-20240421211743488-1713705464361-1.png)

## 3-29

### (1)

$$
\mathcal F(f(2t))=\frac12F(\frac\omega2)\\
\therefore \mathcal F(tf(2t))=\frac j4F'(\frac\omega2)
$$

### (2)

$$
\mathcal F((t-2)f(t))=jF'(\omega)-2F(\omega)
$$

### (3)

$$
\mathcal F((t-2)f(-2t))=\mathcal F(tf(-2t)-2f(-2t))=\frac j2F'(-\frac\omega2)-F(-\frac\omega2)
$$

### (4)

$$
\mathcal F(tf'(t))=-F(\omega)-\omega F'(\omega)
$$

### (5)

$$
\mathcal F(f(1-t))=F(-\omega)e^{-j\omega}
$$

### (6)

$$
\mathcal F((1-t)f(1-t))=jF'(-\omega)e^{-j\omega}
$$

### (7)

$$
\mathcal F(f(2t-5))=\frac12F(\frac\omega2)e^{-j\omega\frac52}
$$

