**2-11**
$$
r(t)=Ce^{-t}u(t)\\
r'(t)=-Ce^{-t}u(t)+Ce^{-t}\delta(t)\to-r(t)+C\\
r''(t)=-r'(t)-Ce^{-t}\delta(t)+Ce^{-t}\delta'(t)\to-r'(t)\\
带入方程得：2Ce^{-t}u(t)+4C=e^{-t}u(t)\to C=\frac12\\
r(0_-)=\frac12e^{-0_-}=\frac12\\
r'(0_-)=-\frac12e^{-0_-}=-\frac12\\
$$
**2-12**
$$
\left\{\begin{array}l
h(t)*u(t)+r_{zi}(t)=2e^{-t}u(t)\\
h(t)*\delta(t)+r_{zi}(t)=\delta(t)
\end{array}\right.\\
\to h'(t)-h(t)=\delta'(t)-2\delta(t)+2e^{-t}u(t)\\
\to h(t)=\delta(t)-e^{-t}u(t)\\
\therefore r_{zi}(t)=\delta(t)-h(t)=e^{-t}u(t)\\
当e(t)=e^{-t}u(t)\\
r_3(t)=e^{-t}u(t)*h(t)+r_{zi}(t)\\
=e^{-t}u(t)-e^{-t}u(t)*e^{-t}u(t)+e^{-t}u(t)\\
即r_3(t)=2e^{-t}u(t)-te^{-t}u(t)
$$


**2-17**
$$
r_{zs}(t)=\int^\infty_{t-2}e^{t-\tau}e(\tau-1)d\tau\\
=\int^\infty_\infty e^{t-\tau}e(\tau-1)u(\tau-t+2)d\tau\\
=\int^\infty_\infty e^{t-\tau}u(-(t-\tau)+2)\cdot e(\tau-1)d\tau\\
=e(t-1)*e^{t}u(-t+2)=e(t)*e^{t-1}u(3-t)\\
即：h(t)=e^{t-1}u(3-t)
$$
**2-18**
$$
\left\{\begin{array}l
h(t)*e(t)+r_{zi}(t)=r(t)\\
h(t)*e'(t)+r_{zi}(t)=-3r(t)+e^{-2t}u(t)
\end{array}\right.\\
\to h(t)*(e'(t)+3e(t))=e^{-2t}u(t)\\
\to h(t)*(2e^{-3t}\delta(t-1))=e^{-2t}u(t)\\
\to h(t)*(2e^{-3}\delta(t))=e^{-2(t+1)}u(t+1)\\
\to h(t)=\frac12e^{-2t+1}u(t+1)
$$
