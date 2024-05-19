**2-4**

(1)
$$
特征方程：p^2+2p+2=0\\
得：p=-1\pm i\\
\therefore r_h(t)=(A_1\cos(t)+A_2\sin(t))e^{-t}\\
\therefore\left\{\begin{array}l
r(0_+)=A_1=1\\
r'(0_+)=-A_1+A_2=2
 \end{array}\right.\to\left\{\begin{array}l
 A_1=1\\
 A_2=3\\
  \end{array}\right.\\
即r_{zi}(t)=(\cos(t)+3\sin(t))e^{-t}
$$
(2)
$$
特征方程：p^2+2p+1=0\\
得：p=-1(重根)\\
\therefore r_h(t)=(A_1t+A_2)e^{-t}\\
\therefore\left\{\begin{array}l
r(0_+)=A_2=1\\
r'(0_+)=A_1-A_2=2
 \end{array}\right.\to\left\{\begin{array}l
 A_1=3\\
 A_2=1\\
  \end{array}\right.\\
即r_{zi}(t)=(3t+1)e^{-t}
$$
(3)
$$
特征方程：p^3+2p^2+p=0\\
得：p=-1(重根), 0\\
\therefore r_h(t)=(A_1t+A_2)e^{-t}+A_3\\
\therefore\left\{\begin{array}l
r(0_+)=A_2+A_3=0\\
r'(0_+)=A_1-A_2=0\\
r''(0_+)=A_2=1
 \end{array}\right.\to\left\{\begin{array}l
 A_1=-1\\
 A_2=-1\\
 A_3=1
  \end{array}\right.\\
即r_{zi}(t)=-(t+1)e^{-t}+1
$$
**2-6**
$$
对于全响应：e(t)=u(t)\to 激励侧奇异函数最高项为\delta(t)\\
\therefore r(t)不含u(t)及其导数\\
\int^{0_+}_{0_-}(r''(t)+3r'(2)+2r(t))dt = \int^{0_+}_{0_-}(\delta(t)+3u(t))dt=1\\
解得：r'(0_+)=r'(0_-)+1=3\\
特征方程：p^2+3p+2=0\to p = -1,-2\\
\therefore r(t)=A_1e^{-t}+A_2e^{-2t}+B(t)\\
当 t\to+\infty, B(t)''+3B(t)'+2B(t) = 3\to B(t) = \frac32\\
\therefore\left\{\begin{array}l
 r(0_+)=r(0_-)=A_1+A_2+\frac32=1\\
 r'(0_+)=-A_1-2A_2=3
\end{array}\right.\to\left\{\begin{array}l
 A_1=2\\
 A_2=-\frac52
\end{array}\right.\\
即全响应\,r(t)=\underbrace{2e^{-t}-\frac52e^{-2t}}_{自由响应}+\underbrace{\frac32}_{强迫响应}\\
$$

-------

$$
对于零输入响应：r_{zi}(0)=1, r_{zi}'(0)=2\\
\therefore\left\{\begin{array}l
r_{zi}(0)=A_1+A_2=1\\
r_{zi}'(0_-)=-A_1-2A_2=2
\end{array}\right.\to\left\{\begin{array}l
A_1=4\\
A_2=-3
\end{array}\right.\\
\therefore \left\{\begin{array}lr_{zi}(t)=4e^{-t}-3e^{-2t}\\
r_{zs}(t)=r(t)-r_{zi}(t)=-2e^{-t}+\frac12e^{-2t}+\frac32\end{array}\right.
$$



**2-7**
$$
由题意得v_0(0_-)=r(0_-)=E, e(t)=I_Su(t)\\
Cr'(t)+\frac1Rr(t)=e(t)\\
特征方程Cp+\frac1R=0\to p = -\frac1{RC}\\
易得r(t)不含u(t)及其导数\\
\therefore r(t)=Ae^{-\frac1{RC}t}+B(t)\\
当 t\to+\infty, CB'(t)+\frac1RB(t)=I_S\to B(t)=RI_S\\
\therefore r(0_+)=r(0_-)=A+RI_S = E\to A = E-RI_S\\
\therefore全响应\,r(t)=\underbrace{(E-RI_S)e^{-\frac1{RC}t}}_{自由响应}+\underbrace{RI_S}_{强迫响应}
$$

-----

$$
对于零输入响应：r(0)=E, B(t)=0\\
\therefore r(0)=A=E\\
\therefore \left\{\begin{array}lr_{zi}(t)=Ee^{-\frac1{RC}t}\\
r_{zs}(t)=r(t)-r_{zi}(t)=-RI_Se^{-\frac1{RC}t}+RI_S\end{array}\right.
$$

