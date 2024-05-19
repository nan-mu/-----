**1-3 分别求下列各周期信号的周期T**

1. $\cos(10t) - \cos(30t)$

$$
\frac{T_1}{T_2}=\frac{\frac\pi5}{\frac{\pi}{15}}=\frac31=\frac{N_1}{N_2}\\
\therefore T = \text{LCM}(T_1, T_2)=\frac\pi5
$$

2. $e^{j10t}$

$$
T=\frac{2\pi}{\arg(f)}=\frac{2\pi}{10}=\frac\pi5
$$

3. $[5\sin(8t)]^2$​

$$
f=25\cdot\frac{1-\cos(16t)}{2}\\
\therefore T=\frac{2\pi}{16}=\frac\pi8
$$

4. $\sum^\infty_{n=0}(-1)^n[u(t-nT)-u(t-nT-T)](\text{n为正整数})$

$$
f=\sum^\infty_{n=0}[u(t-2nT)-u(t-2nT-T)]-\sum^\infty_{n=0}[u(t-(2n+1)T)-u(t-(2n+1)T-T)]\\
=\sum^\infty_{n=0}u(t-2nT)-2\sum^\infty_{n=0}u(t-2nT-T)+\sum^\infty_{n=0}u(t-2nT-2T)\\
我认为这里存在歧义，推到这一步可以发现假如将t替换成t-2T时，可以得到：\\
\sum^\infty_{n=1}u(t-2nT)-2\sum^\infty_{n=1}u(t-2nT-T)+\sum^\infty_{n=1}u(t-2nT-2T)\\
根据数列的性质可以说两个式子是相等的（当然对u(t)也有要求），可将t替换成t+2T时得到：\\
\sum^\infty_{n=-1}u(t-2nT)-2\sum^\infty_{n=-1}u(t-2nT-T)+\sum^\infty_{n=-1}u(t-2nT-2T)\\
违背了题目注明的n为正整数（也无法原上之前对(-1)^n的处理）。\\
但根据习题解答，似乎这题是有一定缺陷的，应该在n\to\infty和t\to\infty处讨论周期性。\\
在这个条件下就有周期T=2T
$$

**1-5 已知 $f(t)$，为求 $f(t_0-at)$ 应按下列哪种运算求得正确结果（式中 $t_0,a$都为正值）?**

1. $f(-at)$ 左移 $t_0$：得到 $f(-at-at_0)$ ❌
2. $f(at)$ 右移 $t_0$：得到 $f(at-t_0)$​ ❌
3. $f(at)$ 左移 $\frac{t_0}a$：得到 $f(at-t_0)$ ❌
4. $f(-at)$ 右移 $\frac{t_0}a$：得到 $f(t_0-at)$ ✔

**1-4 判断以下各序列是否周期性的，如果是周期性的，试确定其周期。**

1. $x(n)=A\cos(\frac{3\pi}7n-\frac\pi8)$

$$
N=\frac{2\pi}{\frac{3\pi}7}=\frac{14}3\sim14
$$

2. $x(n)=e^{j(\frac n8-\pi)}$

$$
N=\frac{2\pi}{\frac 18}为无理数，故无周期
$$

