# week 6

**7-补充**
$$
x(n)+\frac56y(n)-\frac16y(n-1)=y(n+1)\\
得到差分方程：6y(n+1)-5y(n)+y(n-1)=6x(n)\\
得到特征方程：6q^2-5q+1=(2q-1)(3q-1)=6\\
\therefore H(q)/q = \frac6q+\frac{12}{p-\frac12}-\frac{18}{p-\frac13}\\
\to h(k)=6\delta(k)+12(\frac12)^ku(k)-18(\frac13)^ku(k)\\
\because 特征根都小于1 \therefore 系统是稳定的\\
y_{zs}=u(n)*h(n)=3u(n)-12(\frac12)^nu(n)+9(\frac13)^nu(n)\\
易得y_{zi}(n)=C_1(\frac12)^nu(n)+C_2(\frac13)^nu(n)\\
代入得\left\{\begin{array}l
C_1+C_2=5\\
\frac12C_1+\frac13C_2=2
\end{array}\right.\to \left\{\begin{array}l
C_1=2\\
C_2=3
\end{array}\right.\\
\therefore y(n)=\underbrace{3u(n)}_{强迫响应}+\underbrace{(-10(\frac12)^nu(n)+12(\frac13)^nu(n))}_{自由响应}\\
$$
 **7-9**
$$
a_0x(n)+a_1x(n-1)+b_1y(n-1)+b_2y(n-2)=y(n)\\
\to y(n)-b_1y(n-1)-b_2y(n-2)=a_0x(n)+a_1x(n-1)\\
\therefore 系统为2阶
$$
**7-33**

（1）
$$
x(n)*h_1(n)=\delta(n)*u(n)-\delta(n-3)*u(n)\\
\to u(n)-u(n-3)=\left\{\begin{array}l1&n=0,1,2\\0&other\end{array}\right.\\
[x(n)*h_1(n)]*h_2(n)=h_2(n)+h_2(n-1)+h_2(n-2)\\
\to (u(n)+1.25u(n-1)+1.5625u(n-2))0.8^n
$$
（2）
$$
h_1(n)*h_2(n)=(u(n)-0.8^{-3}u(n-3))0.8^n\\
x(n)*[h_1(n)*h_2(n)]=(0.8^n*u(n))\cdot(u(n)-0.8^{-3}u(n-3))\\
\to (u(n)+1.25u(n-1)+1.5625u(n-2))0.8^n
$$
**7-32**

（1）
$$
u(n)-u(n-4)=\left\{\begin{array}l1&n=0,1,2,3\\0&other\end{array}\right.\\
h(n)*x(n)=h(n)+h(n-1)+h(n-2)+h(n-3)\\=\left\{\begin{array}ln+1&n=0,1,2,3\\7-n&n=4,5,6\\0&other\end{array}\right.
$$

<img src="./week%206.assets/image-20240404132446330.png" alt="image-20240404132446330" style="zoom:50%;" />

（2）
$$
h(n)=\left\{\begin{array}l2^n&n=0,1,2,3\\0&other\end{array}\right.\\
h(n-2)=\left\{\begin{array}l2^{n-2}&n=2,3,4,5\\0&other\end{array}\right.\\
h(n)*x(n)=h(n)-h(n-2)=\left\{\begin{array}l
2^n&n=0,1\\
2^n-2^{n-2}&n=2,3\\
-2^{n-2}&n=4,5\\
0&other
\end{array}\right.\\
$$
<img src="./week%206.assets/image-20240404134339635.png" alt="image-20240404134339635" style="zoom:50%;" />

（3）
$$
u(n)-u(n-5)=\left\{\begin{array}l1&n=0,1,2,3,4\\0&other\end{array}\right.\\
h(n)*x(n)=\sum^5_{m=0}h(n-m)\\=\left\{\begin{array}l(2^{n+1}-1)(\frac12)^n&n=0,1,2,3,4\\31(\frac12)^n&n\ge5\\0&other\end{array}\right.\\
$$
<img src="./week%206.assets/image-20240404135248581.png" alt="image-20240404135248581" style="zoom:50%;" />
