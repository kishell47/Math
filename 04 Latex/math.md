$$
\begin{vmatrix}
0 & a & b & 0 \\
a & 0 & 0 & b \\
0 & c & d & 0 \\
c & 0 & 0 & d
\end{vmatrix}\stackrel{r_2\leftrightarrow r3}=-\begin{vmatrix}
0 & a & b & 0 \\
0 & c & d & 0 \\
a & 0 & 0 & b \\
c & 0 & 0 & d
\end{vmatrix}\stackrel{c_2\leftrightarrow c4}=\begin{vmatrix}
0 & 0 & b & a \\
0 & 0 & d & c \\
a & b & 0 & 0 \\
c & d & 0 & 0
\end{vmatrix}
$$

$$
=(-1)^{(2\cdot2)}\begin{vmatrix}
b & a \\
d & c \\
\end{vmatrix}\begin{vmatrix}
a & b\\
c & d
\end{vmatrix}=(bc-ad)(ad-bc)=-(ad-bc)^2
$$

$$

$$

$$
\begin{vmatrix}
A & O\\
O & B
\end{vmatrix}=|A||B|
$$

$$
\begin{vmatrix}
O & A\\
B & O
\end{vmatrix}=(-1)^{mn}|A||B|
$$

$$
整体无关\Rightarrow 部分无关\\
部分无关\nRightarrow 整体无关
$$

$$
\nRightarrow
$$

$$
(\alpha_1+k\alpha_3,\alpha_2+l\alpha_3)=(\alpha_1,\alpha_2,\alpha_3)\begin{pmatrix}
1 & 0 \\
0 & 1 \\
k & l
\end{pmatrix}
$$

$$
\begin{pmatrix}
x & y \\
z & v
\end{pmatrix}
$$

$$
(α_1+kα_3,\alpha_2+lα_3)=(α_1,α_2,α_3)()
$$
$$
EY1=\int_{-\infty}^{+\infty}y{1/2f1(y)+f2()}
$$
![image-20230803203338982](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308032033109.p1ng)
$$
\int_{-\pi}^{\pi}(x-acosx-bsinx)^2dx
$$

$$
\int_{-\pi}^{\pi}\left(x-a_{1} \cos x-b_{1} \sin x\right)^{2} d x=\min _{a, b \in R}\left\{\int_{-\pi}^{\pi}(x-a \cos x-b \sin x)^{2} d x\right\}
$$

$$
对x进行傅里叶级数展开
$$

$$
\int_{-\pi}^{\pi}\cos nx\mathrm{~d}x=\left.\frac{\sin n x}{n}\right|_{x\,=\,-\pi} ^{x\,=\,\pi}=2\cdot\frac{\sin n \pi}{n}=0
\\\int_{-\pi}^{\pi}\sin nx\mathrm{~d}x=0
$$

$$
\begin{array}{l}
\int_{-\pi}^{\pi} 1 \cdot \cos n x \mathrm{~d} x=\left.\frac{\sin n x}{n}\right|_{-\pi} ^{\pi}=0, \\
\int_{-\pi}^{\pi} 1 \cdot \sin n x \mathrm{~d} x=-\left.\frac{\cos n x}{n}\right|_{-\pi} ^{\pi}=0, \\
\int_{-\pi}^{\pi} \cos n x \cdot \sin m x \mathrm{~d} x=\frac{1}{2} \int_{-\pi}^{\pi}[\sin (m+n) x+\sin (m-n) x] \mathrm{d} x=0, \\
\int_{-\pi}^{\pi} \cos n x \cdot \cos m x \mathrm{~d} x=\frac{1}{2} \int_{-\pi}^{\pi}[\cos (n+m) x+\cos (n-m) x] \mathrm{d} x=0, m \neq n, \\
\int_{-\pi}^{\pi} \sin n x \cdot \sin m x \mathrm{~d} x=\frac{1}{2} \int_{-\pi}^{\pi}[\cos (n-m) x-\cos (m+n) x] \mathrm{d} x=0, m \neq n .
\end{array}
$$

$$
\{1,\cos x,\sin x,\cos 2x,\sin\}
$$

$$
\int_{-\pi}^{\pi} \cos n x \cdot \sin m x \mathrm{~d} x=0
$$

![image-20230804101712315](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308041017502.png)


$$

$$
![co](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308041019165.png)
$$
\int\cos^2x\mathrm{~d}x=\frac{x}{2}+\frac{\sin 2x}{4}+C\\(\cos^2x=\frac{1+\cos2x}{2})
$$

$$
\int_{-\pi}^{\pi}\cos^2x\mathrm{~d}x=\left.\frac{x}{2}+\frac{\sin 2x}{4}\right|_{-\pi}^{\pi}=\pi
$$

$$ {\}
\cos\alpha\cos\beta=\frac{\cos(\alpha+\beta)+\cos(\alpha-\beta)}{2}
$$

![image-20230804111149724](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308041111801.png)
$$
\int_{-\pi}^{\pi}\cos nx\cos mx\mathrm{~d}x=\frac{1}{2}\int_{-\pi}^{\pi}\cos(n+m)x+\cos(n-m)x\mathrm{~d}x=0(n\ne m)
$$
<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308041123796.png" alt="image-20230804112339706" style="zoom: 80%;" />
$$
\int\sin^2x\mathrm{~d}x=\frac{x}{2}-\frac{\sin2x}{4}+C
\\(\sin^2x=\frac{1-\cos2x}{2})
$$
{}
$$
\sin\alpha\sin\beta=\frac{\cos(\alpha+\beta)-\cos(\alpha-\beta)}{2}
$$

$$
\int_{-\pi}^{\pi}\sin^2nx\mathrm{~d}x=\left.\frac{x}{2}-\frac{\sin2x}{4}\right|_{-\pi}^{\pi}
$$

$$
\int_{-\pi}^{\pi}\cos^2nx\mathrm{~d}x=\frac{1}{n}\int_{-\pi}^{\pi}\cos^2nx\mathrm{~d}(nx)=\left.\frac{1}{n}\cdot(\frac{nx}{2}+\frac{\sin2nx}{4})\right|_{-\pi}^{\pi}=\pi
$$

$$
\int_{-\pi}^{\pi}\sin^2nx\mathrm{~d}x=\left.\frac{1}{n}\cdot(\frac{nx}{2}-\frac{\sin 2nx}{4})\right|_{-\pi}^{\pi}=\pi
$$

$$
\int_{-\pi}^{\pi}\sin nx\sin mx\mathrm{~d}x=\frac{1}{2}\int_{-\pi}^{\pi}\cos[(n+m)x]-\cos[(n-m)x]\mathrm{~d}x=0
$$

$$
φ(t)=A_0+A_1\sin(\omega t+φ_1)+A_2\sin(2\omega t+φ_2)+……+A_n\sin(n\omega t+φ_n)+……=A_0+\sum_{n=1}^{\infty}A_n\sin(n\omega t+φ_n)
$$

$$
f(x)=A_0+\sum_{n=1}^{\infty}(a_n\cos nx+b_n\sin nx)
$$

$$
\int_{-\pi}^{\pi}f(x)\mathrm{~d}x=\int_{-\pi}^{\pi}\left[A_0+\sum_{n=1}^{\infty}(a_n\cos nx+b_n \sin nx)\right]\mathrm{~d}x
\\=2A_0\pi+\sum_{n=1}^{\infty}\left(a_n\int_{-\pi}^{\pi}\cos nx\mathrm{~d}x+b_n\int_{-\pi}^{\pi}\sin nx\mathrm{~d}x\right)=2A_0\pi
$$

$$
A_0=\frac{\int_{-\pi}^{\pi}f(x)\mathrm{~d}x}{2\pi}
$$

$$
\int_{-\pi}^{\pi}f(x)\cos mx\mathrm{~d}x=\int_{-\pi}^{\pi}\left[A_0+\sum_{n=1}^{\infty}\left(a_n\cos nx+b_n\sin nx\right)\right]\cdot\cos mx\mathrm{~d}x
$$

$$
m=n时,\int_{-\pi}^{\pi}f(x)\cos mx\mathrm{~d}x=\sum_{n=1}^{\infty}\left(a_n\int_{-\pi}^{\pi}\cos^2nx\mathrm{~d}x+b_n\int_{-\pi}^{\pi}\sin nx\cdot\cos nx\mathrm{~d}x\right)=\sum_{n=1}^{\infty}a_n\pi\\m\ne n时,\int_{-\pi}^{\pi}f(x)\cos mx\mathrm{~d}x
$$


$$
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}(a_n\cos nx+b_n \sin nx)
$$

$$
a_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\cos nx\mathrm{~d}x,n=0,1,2,……，
\\b_n=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\sin nx\mathrm{~d}x,n=1,2,3,……，
$$

$$
令x=a+b-t,\\\begin{array}{l}\int_a^bf(x)\mathrm{~d}x&=\int_{b}^{a}f(a+b-t)\mathrm{~d}(a+b-t)
\\&=\int_{b}^{a}f(a+b-t)\mathrm{~d}(-t)\\&=\int_{a}^{b}f(a+b-x)\mathrm{~d}x
\end{array}
$$ { }

$$
\begin{array}{l}\int_{-\pi}^{\pi}x\sin x\mathrm{~d}x&=2\int_{0}^{\pi}x\sin x\mathrm{~d}x
\\&=
\end{array}
$$

$$
\Rightarrow 4\int_{0}^{\pi}x\sin x\mathrm{~d}x=2\pi\int_{0}^{\pi}\sin x\mathrm{~d}x
$$

$$
\int_{a}^{b}f(x)\mathrm{~d}x=\int_{a}^{\frac{a+b}{2}}[f(x)+f(a+b-x)]\mathrm{~d}x
$$

$$
\int_{0}^{\pi}x\sin x\mathrm{~d}x=\int_{0}^{\frac{\pi}{2}}\{x\sin x+(\pi-x)\sin[\pi-x]\}\mathrm{~d}x=\pi\int_{0}^\frac{\pi}{2}\sin x\mathrm{~d}x
$$

$$
\begin{array}{l}\int_{-\pi}^{\pi}x\sin x\mathrm{~d}x&=2\int_{0}^{\pi}x\sin x\mathrm{~d}x
\\&=2\pi\int_{0}^{\frac{\pi}{2}}\sin x\mathrm{~d}x
\\&=2\pi
\end{array}
$$

$$
\int_{0}^{\frac{\pi}{2}}\sin x\mathrm{~d}x=1
$$

$$
\int_{0}^{\pi}xf(\sin x)\mathrm{~d}x=\pi\int_{0}^{\frac{\pi}{2}}f(\sin x)\mathrm{~d}x
\\证明:\int_{0}^{\pi}xf(\sin x)\mathrm{~d}x=\int_{0}^{\frac{\pi}{2}}[xf(\sin x)+(\pi-x)f(\sin(\pi-x)]\mathrm{~d}x=\pi\int_{0}^{\frac{\pi}{2}}f(\sin x)\mathrm{~d}x
$$

$$
f(a_1,b_1)=\int_{-\pi}^{\pi}(x-a_1\cos x-b_1\sin x)^2\mathrm{~d}x=\min\{f(a,b)\}=\min _{a, b \in \mathbf{R}}\left\{\int_{-\pi}^{\pi}(x-a \cos x-b \sin x)^{2} \mathrm{~d} x\right\}
$$

$$
=\min _{a, b \in \mathbf{R}}\left\{\int_{-\pi}^{\pi}(x-a \cos x-b \sin x)^{2} \mathrm{~d} x\right\}
$$ { ,}

$$
a_1=\frac{1}{\pi}\int_{-\pi}^{\pi}x\cos x\mathrm{~d}x=0
$$

$$
b_1=\frac{1}{\pi}\int_{-\pi}^{\pi}x\sin x\mathrm{~d}x=\frac{2}{\pi}\int_{0}^{\pi}x\sin x\mathrm{~d}x=\frac{2}{\pi}\cdot\pi\int_{0}^{\frac{\pi}{2}}\sin x\mathrm{~d}x=
$$

$$
f(x)=x,n=1
$$

$$
a_1\cos x+b_1\sin x=2\sin x
$$

$$
\begin{array}{l}\frac{\partial f(a,b)}{\partial a}
&=\int_{-\pi}^{\pi}2(x-a\cos x-b\sin x)(-\cos x)\mathrm{~d}x
\\&=2\int_{-\pi}^{\pi}(a\cos ^2x+b\sin x\cos x-x\cos x)\mathrm{~d}x
\\&=2a\int_{-\pi}^{\pi}\cos ^2x\mathrm{~d}x
\\&=2a\pi\stackrel{令}=0(驻点)
\\\Rightarrow a=0
\end{array}
$$

$$
\stackrel{1^\infty}=e^A
$$

$$
\begin{array}{l}\frac{\partial f(a,b)}{\partial b}
&=\int_{-\pi}^{\pi}2(x-a\cos x-b\sin x)(-\sin x)\mathrm{~d}x
\\&=2\int_{-\pi}^{\pi}b\sin^2x-x\sin x\mathrm{~d}x
\\&=2b\pi-2\int_{-\pi}^{\pi}x\sin x \mathrm{~d}x
\\&=2b\pi-4\int_{0}^{\pi}x\sin x \mathrm{~d}x
\\&=2b\pi-4\pi\int_{0}^{\frac{\pi}{2}}\sin x \mathrm{~d}x
\\&=2b\pi-4\pi\stackrel{令}=0(驻点)
\\\Rightarrow b=2
\end{array}
$$

$$
(a+b+c)^2=a^2+b^2+c^2+2ab+2ac+2bc
$$ {^}

$$
\begin{array}{l}
f(a,b)=\int_{-\pi}^{\pi}(x-a\cos x-b\sin x)^2\mathrm{~d}x

\end{array}
$$


$$
\begin{array}{l}I&=\int_{-\pi}^{\pi}(x^2+a^2\cos^2x+b^2\sin^2x-2ax\cos x-2bx\sin x+ab\cos x\sin x)\mathrm{~d}x
\\&=\int_{-\pi}^{\pi}(x^2+a^2\cos^2x+b^2\sin^2x-2bx\sin x)\mathrm{~d}x
\\&=\frac{2}{3}\pi^3+a^2\pi+b^2\pi-4b\int_{0}^{\pi}x\sin x\mathrm{~d}x
\\&=\frac{2}{3}\pi^3+a^2\pi+b^2\pi-4b\pi
\\&=\frac{2}{3}\pi^3+(a^2+b^2-4b)\pi
\end{array}
$$

$$
a^2取最小值,a=0
\\b^2-4b取最小值,(b^2-4b)=(b-2)^2-4,b=2取最小值
$$

$$
\begin{array}{l}
\int_{-\pi}^{\pi} \sin m x \sin n x d x=\left\{\begin{array}{ll}
0, & m \neq n \\
\pi, & m=n
\end{array}\right. \\
\int_{-\pi}^{\pi} \cos m x \cos n x d x=\left\{\begin{array}{ll}
0, & m \neq n \\
\pi, & m=n
\end{array}\right. \\
\int_{-\pi}^{\pi} \sin m x \cos n x d x=0 \\
\int_{0}^{\pi} x f(\sin x) d x=\frac{\pi}{2} \int_{0}^{\pi} f(\sin x) d x = \pi \int_{0}^{\frac{\pi}{2}} f(\sin x) d x\\
\end{array}
$$

$$
\int_{0}^{\frac{\pi}{2}}\sin x\mathrm{~d}x=1
$$

$$
(a+b+c)^2=a^2+b^2+c^2+2ab+2ac+2bc
$$

$$
F_x'(x_0,y_0,z_0)(x-x_0)+F_y'(x_0,y_0,z_0)(y-y_0)+F_z'(x_0,y_0,z_0)(z-z_0)=0
$$

$$
f_x'(x_0,y_0)(x-x_0)+f_y'(x_0,y_0)(y-y_0)-(z-z_0)=0
$$

$$
z=f(x,y)=x^2(1-\sin y)+y^2(1-\sin x)
$$

$$
f_x'(x,y)=2x-2x\sin y-y^2\cos x
\\f_y'(x,y)=2y-2y\sin x-x^2\cos y
\\f_x'(1,0)=2
\\f_y'(1,0)=-1
$$

$$
f_x'(1,0)(x-x_0)+f_y'(1,0)(y-y_0)-(z-z_0)=0
\\\Rightarrow2(x-x_0)-(y-y_0)-(z-z_0)=0
\\\Rightarrow2(x-1)-(y-0)-(z-1)=0
\\\Rightarrow2x-y-z-1=0
$$

$$
\left.\int_{a}^{b} f(x) d x \stackrel{F^{\prime}(x)=f(x)}{=} F(x)\right|_{a} ^{b}=F(b)-F(a)
$$

$$
,x\in[0,2]
$$

$$
\left\{\begin{array}{l}
y_{1}=x_{1}+x_{2}+x_{3}, \\
y_{2}=x_{2}+x_{3}, \\
y_{3}=x_{3},
\end{array}\right.
$$

$$
f=x_1^2-x_2^2+2ax_1x_3+4x_2x_3
\\=(x_1+ax_3)^2-a^2x_3^2-x_2^2+4x_2x_3
\\=(x_1+ax_3)^2-(x_2-2x_3)^2-a^2x_3^2+4x_3^2
\\=(x_1+ax_3)^2-(x_2-2x_3)^2+(4-a^2)x_3^2
$$

$$
\left\{\begin{array}{l}
y_{1}=x_1+ax_3, \\
y_{2}=x_2-2x_3, \\
y_{3}=x_3,
\end{array}\right.
$$

$$
f\stackrel{\boldsymbol{x}=\boldsymbol{C y}}{=}y_1^2-y_2^2+(4-a^2)y_3^2
$$

$$
f\left(x_{1}, x_{2}, x_{3}\right) \stackrel{\boldsymbol{x}=\boldsymbol{C y}}{=} y_{1}^{2}-2 y_{2}^{2} .
$$

$$
4-a^2\geq0\Rightarrow-2\le a\le2
$$

$$
A=\begin{pmatrix}
1 & 0 & a\\
0 & -1 & 2 \\
a & 2 & 0
\end{pmatrix}
$$

$$
\lambda_1y_1^2+\lambda_2y_2^2+……+\lambda_ny_n^2
$$

$$
x=Qy\Rightarrow f=\lambda_1y_1^2+\lambda_2y_2^2+\lambda_3y_3^2(\lambda_1,\lambda_2,\lambda_3为特征根)
$$

$$
\sum_{i=1}^n\lambda_i=\sum_{i=1}^na_{ii}=tr(A)(特征值的和=主对角线元素之和)
$$

$$
\prod_{i=1}^n\lambda_i=|A|(特征值的连乘积=矩阵行列式)
$$

$$
\lambda_1+\lambda_2+\lambda_3=1+(-1)+0=0
\\\lambda_1\lambda_2\lambda_3=|A|=a^2-4
$$

$$
不妨设\lambda_1<0,
\\有\left\{\begin{array}{l}
\lambda_2\geq0
\\\lambda_3\geq0
\end{array}\right.
\Leftrightarrow|A|\leq0
$$

$$
a^2-4\leq0\Rightarrow -2\le a\le2
$$

$$
\frac{u^2}{a^2}+\frac{v^2}{b^2}=1
$$

$$
ax^2+bxy+cy^2=1
$$

$$
\left\{\begin{array}{l}
x=k_1u+k_2v\\
y=l_1u+l_2v
\end{array}\right.
$$

$$
f(x_1,x_2,x_3)=x_1^2+3x_2^2+2x_1x_3
$$

$$
f=x^TAx
$$

$$
A=\begin{pmatrix}
0 & -2 & 1\\
-2 & 0 & t \\
1 & t & 0
\end{pmatrix}
$$


$$
f=x^TAx=x_1^2-x_2^2+4x_1x_2+6x_1x_3+6x_2x_3
$$

$$
A=\begin{pmatrix}
1 & 2 & 3\\
2 & -1 & 3 \\
3 & 3 & 0
\end{pmatrix}
$$

$$
从变量x=(x_1,x_2,……,x_n)^T到y=(y_1,y_2,……,y_n)^T的可逆线性变换
$$

$$
x=Cy\Rightarrow y=C^{-1}x
$$

$$
\boldsymbol{Q}^{-1} \boldsymbol{A} \boldsymbol{Q}=\boldsymbol{Q}^{T} \boldsymbol{A} \boldsymbol{Q}=\boldsymbol{\Lambda}=\left(\begin{array}{llll}
\lambda_{1} & & & \\
& \lambda_{2} & & \\
& & \ddots & \\
& & & \lambda_{n}
\end{array}\right) \text {, }
$$

$$
f=x^TAx=(Qy)^TA(Qy)=y^TQ^TAQy=y^T\Lambda y=y^T\left(\begin{array}{llll}
\lambda_{1} & & & \\
& \lambda_{2} & & \\
& & \ddots & \\
& & & \lambda_{n}
\end{array}\right) y
$$

$$
Q^TAQ=\Lambda 
$$

$$
y^T\Lambda y=y^T\left(\begin{array}{llll}
\lambda_{1} & & & \\
& \lambda_{2} & & \\
& & \ddots & \\
& & & \lambda_{n}
\end{array}\right) y=\lambda_1y_1^2+\lambda_2y_2^2+……+\lambda_ny_n^2
$$

$$
例:已知f=x^TAx经正交变换化为标准形y_1^2+2y_2^2-3y_3^2,求|A|
$$

$$
Q^TAQ=\Lambda=Q^{-1}AQ
$$

$$
f(x_1,x_2,x_3)=(x_1+ax_3)^2-a^2x_3^2-(x_2-2x_3)^2+4x_3^2
\\=(x_1+ax_3)^2-(x_2-2x_3)^2+(4-a^2)x_3^2
\\令\left\{\begin{array}{l}
y_{1}=x_1+ax_3 \\
y_{2}=x_2-2x_3 \\
y_{3}=x_{3}
\end{array}\right.
\\f(x_1,x_2,x_3)=y_1^2-y_2^2+(4-a^2)y_3^2
\\4-a^2\ge0\\\Rightarrow-2\le a\le2
$$

$$
A=\begin{pmatrix}
1 & 0 & a\\
0 & -1 & 2\\
a & 2 & 0
\end{pmatrix}
$$

$$
f(x_1,x_2,x_3)=\lambda_1x_1^2+\lambda_2x_2^2+\lambda_3x_3^2
\\\lambda_1,\lambda_2,\lambda_3是二次型矩阵A的特征值
$$

$$
1.\sum_{i=1}^{3}\lambda_i=tr(A)\quad二次型矩阵A的特征值之和=二次型矩阵A的迹=二次型矩阵A的主对角线元素之和
\\2.\prod_{i=1}^{3}\lambda_i=|A|\quad二次型矩阵A的特征值的连乘积=二次型矩阵A的行列式
$$

$$
1.\lambda_1+\lambda_2+\lambda_3=1+(-1)+0=0
\\2.\lambda_1\cdot\lambda_2\cdot\lambda_3=|A|=\begin{vmatrix}
1 & 0 & a\\
0 & -1 & 2\\
a & 2 & 0
\end{vmatrix}=a^2-4
$$

$$
不妨令\lambda_1<0,则\left\{\begin{array}{l}
\lambda_1\ge0\\
\lambda_2\ge0
\end{array}\right.
$$

$$
a^2-4\le0\Rightarrow-2\le a\le 2
$$

$$
c\sum_{i=1}^{n}X_i^2是\theta^2的无偏估计\Rightarrow E\left(c\sum_{i=1}^{n}X_i^2\right)=\theta^2
$$

$$
E\left(c\sum_{i=1}^{n}X_i^2\right)=c\sum_{i=1}^{n}EX_i^2
$$

$$
EX_i^2=\int_{-\infty}^{\infty}x^2f(x,\theta)\mathrm{~d}x
\\=\int_{\theta}^{2\theta}\frac{2x^3}{3\theta^2}\mathrm{~d}x
\\=\frac{x^4}{6\theta^2}\left.\right|_{\theta} ^{2\theta}
\\=\frac{8\theta^2}{3}-\frac{\theta^2}{6}
\\=\frac{5}{2}\theta^2
$$

$$
E\left(c\sum_{i=1}^{n}X_i^2\right)=c\sum_{i=1}^{n}EX_i^2=\frac{5}{2}cn\theta^2
$$

$$
\frac{5}{2}cn=1\Rightarrow c=\frac{2}{5n}
$$

<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308211255247.png" alt="image-20230821125549183" style="zoom:65%;" />
$$
xy'+y(lnx-lny)=0
\\\Rightarrow \frac{\mathrm{~d}y}{\mathrm{~d}x}=\frac{y}{x}ln\frac{y}{x}
\\令u=\frac{y}{x}
\\则y=ux,\frac{\mathrm{~d}y}{\mathrm{~d}x}=u+x\cdot\frac{\mathrm{~d}u}{\mathrm{~d}x}
\\u+x\cdot\frac{\mathrm{~d}u}{\mathrm{~d}x}=ulnu
\\\Rightarrow \int\frac{\mathrm{~d}u}{u(lnu-1)}=\int\frac{\mathrm{~d}x}{x}
\\当x=1时,u=\frac{y}{x}=e^3\Rightarrow lnu=3>0,lnu不用加绝对值
\\\Rightarrow\int\frac{\mathrm{~d}(lnu-1)}{lnu-1}=\int\frac{\mathrm{~d}x}{x}
\\lnu-1=2>0,lnu-1不用加绝对值,x=1>0bu'yong'ji
\\\Rightarrow ln(lnu-1)=lnx+lnC=lnCx
\\\Rightarrow lnu-1=Cx
\\\Rightarrow y=x\cdot e^{Cx+1}
\\y(1)=1\cdot e^{C+1}=e^3
\\\Rightarrow C=2
\\\Rightarrow y=x\cdot e^{2x+1}
$$

$$
\oint_{\Gamma} P d x+Q d y+R d z=\iint_{S}\left|\begin{array}{ccc}
d y d z & d z d x & d x d y \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
P & Q & R
\end{array}\right|
\\=\iint_{S}\left|\begin{array}{ccc}
\cos \alpha & \cos \beta & \cos \gamma \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
z & 0 & y
\end{array}\right| d S
\\=\iint_{S}\left|\begin{array}{ccc}
0 & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{2}} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
z & 0 & y
\end{array}\right| d S
\\=\iint_{S}\frac{1}{\sqrt2}\mathrm{~d}S
\\=\iint_{D_{xy}}\frac{1}{\sqrt2}\cdot\sqrt2\mathrm{~d}x\mathrm{~d}y=



\\\mathrm{~d}S=\sqrt{1+(z_x')^2+(z_y')^2}\mathrm{~d}x\mathrm{~d}y
$$


$$
令\left\{\begin{array}{l}
x=\cos t\\
y=\sin t\\
z=-\sin t
\end{array}\right.
,t:0\to2\pi
$$

$$
I=\int_0^{2\pi}(-\sin t)\cdot(-\sin t)+\sin t\cdot(-\cos t)\mathrm{~d}t
\\=\int_{-\pi}^{\pi}(-\sin t)\cdot(-\sin t)+\sin t\cdot(-\cos t)\mathrm{~d}t
\\=\int_{-\pi}^{\pi}\sin^2t\mathrm{~d}t
\\=\pi
$$

$$
\int_0^{T}f(x)\mathrm{~d}x=\int_{a}^{a+T}f(x)\mathrm{~d}x
$$

$$
I=\oint_{L_1}(-y)\mathrm{~d}x+y\cdot(-1)\mathrm{~d}y
\\\stackrel{Green}{=}
\\\iint_{x^2+y^2\le1}\mathrm{~d}x\mathrm{~d}y=\pi
$$

![image-20230827161119120](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308271611268.png)
$$
\oint_{L} P(x, y) \mathrm{d} x+Q(x, y) \mathrm{d} y=\iint_{D}\left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right) \mathrm{d} \sigma 
$$

$$
\overrightarrow{n}=(0,1,1)
\\\overrightarrow{n}=(0,\frac{1}{\sqrt{2}},\frac{1}{\sqrt{2}})
\\\overrightarrow{n}=(f_x'(x_0,y_0),f_y'(x_0,y_0),-1)
\\\frac{x-x_0}{f_x'(x_0,y_0)}=\frac{y-y_0}{f_y'(x_0,y_0)}=\frac{z-z_0}{-1}
$$

$$
I=\iint_{S}\left|\begin{array}{ccc}
\cos \alpha & \cos \beta & \cos \gamma \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
P & Q & R
\end{array}\right|\mathrm{~d}S
\\=\iint_{S}\left|\begin{array}{ccc}
0 & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{2}}\\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
P & Q & R
\end{array}\right|\mathrm{~d}
$$

$$
方向是向上的, 即它与  z  轴正向所成的角  \gamma  是锐角, 则法向量的方向余弦为

\\\cos \alpha=\frac{-f_{x}^{\prime}}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}}, \quad \cos \beta=\frac{-f_{y}^{\prime}}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}}, \quad \cos \gamma=\frac{1}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}},

\\其中,  f_{x}^{\prime}=f_{x}^{\prime}\left(x_{0}, y_{0}\right), f_{y}^{\prime}=f_{y}^{\prime}\left(x_{0}, y_{0}\right) .方向是向上的, 即它与  z  轴正向所成的角  \gamma  是锐角, 则法向量的方向余弦为

\\\cos \alpha=\frac{-f_{x}^{\prime}}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}}, \quad \cos \beta=\frac{-f_{y}^{\prime}}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}}, \quad \cos \gamma=\frac{1}{\sqrt{1+\left(f_{x}^{\prime}\right)^{2}+\left(f_{y}^{\prime}\right)^{2}}},

\\其中,  f_{x}^{\prime}=f_{x}^{\prime}\left(x_{0}, y_{0}\right), f_{y}^{\prime}=f_{y}^{\prime}\left(x_{0}, y_{0}\right)
$$



$$
\lim_{x\to+\infty}x^2ln(1+\frac{1}{x})=\lim_{x\to+\infty}x^2\cdot\frac{1}{x}=\lim_{x\to+\infty}x=+\infty

\\ln(1+\frac{1}{x})\sim\frac{1}{x},x\to+\infty
$$

$$
\lim_{x\to+\infty}[x^2(e^{\frac{1}{x}}-1)-x]=\lim_{x\to+\infty}\{{x^2[1+\frac{1}{x}+\frac{1}{2x^2}+o(\frac{1}{x^2})-1]}-x\}=\frac{1}{2}
$$

$$
\lim _{x \rightarrow+\infty} \frac{\int_{1}^{x}\left[t^{2}\left(\mathrm{e}^{\frac{1}{t}}-1\right)-t\right] \mathrm{d} t}{x^{2} \ln \left(1+\frac{1}{x}\right)}=\lim _{x \rightarrow+\infty} \frac{\int_{1}^{x}\left[t^{2}\left(\mathrm{e}^{\frac{1}{t}}-1\right)-t\right] \mathrm{d} t}{x}
\\=\lim_{x\to+\infty}[x^2(e^{\frac{1}{x}}-1)-x]
\\\stackrel{令x=\frac{1}{t}}=\lim_{t\to0^+}\frac{e^t-1-t}{t^2}
\\\stackrel{\frac{0}{0}}=\lim_{t\to0^+}\frac{e^t-1}{2t}
\\\stackrel{\frac{0}{0}}=\lim_{t\to0^+}\frac{e^t}{2}
\\=\frac{1}{2}
\\
\frac{0}{0}
$$


$$
3y^2y'+y^2+x2yy'+2xy+x^2y'=0\quad(*)
$$

$$
y^2+2xy=y(y+2x)=0
\\-6x^3+6=0
\\\Rightarrow x=1,y=-2
$$

$$
6y(y')^2+3y^2y''+2yy'+2yy'+2x(y')^2+2xyy''+2y+2xy'+2xy'+x^2y''=0
\\\Rightarrow(3y^2+2xy+x^2)y''+(6y+2x)(y')^2+(4y+4x)y'+2y=0
\\将x=1,y=-2,y'=0代入
\\\Rightarrow y''=\frac{4}{9}>0
$$

<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202308282150141.png" alt="image-20230828215023018" style="zoom: 60%;" />
$$
\frac{\partial z}{\partial x}=f'e^x\cos y
\\\frac{\partial^2z}{\partial x^2}=f''(e^x\cos y)^2+f'e^x\cos y
\\=f''e^{2x}\cos^2y+f'e^x\cos y
\\\frac{\partial z}{\partial y}=f'e^x\cdot(-\sin y)
\\\frac{\partial^2z}{\partial y^2}=f''[e^x\cdot(-\sin y)]^2+f'e^x(-\cos y)
\\=f''e^{2x}\sin^2y-f'e^x\cos y
\\\frac{\partial^2z}{\partial x^2}+\frac{\partial^2z}{\partial y^2}=f''e^{2x}=(4z+e^x\cos y)e^{2x}
\\\Rightarrow f''=4z+e^x\cos y
\\令u=e^x\cos y
\\f''(u)=4f(u)+u
\\\Rightarrow f''(u)-4f(u)=u\quad(*)
\\\lambda^2-4=0\Rightarrow\lambda=\pm2
\\∴对应齐次方程通解:Y=C_1e^{2u}+C_2e^{-2u}
$$

$$
自由项:f(x)=P_n(x)e^{\alpha x},
\\特解要设为:y^*=e^{\alpha x}Q_n(x)x^k
\\其中\left\{\begin{array}{l}
e^{\alpha x}照抄,\\
Q_n(x)为x的n次多项式\\
k=\left\{\begin{array}{l}
0,\alpha不是特征根
\\1,\alpha是单特征根
\\2,\alpha是二重特征根
\end{array}\right.
\end{array}\right.
$$

$$
设非齐次方程特解为:y^*=AU+B代入\quad(*)
\\-4(AU+B)=U
\\\Rightarrow A=-\frac{1}{4},B=0
\\(*)通解为:f(u)=C_1e^{2u}+C_2e^{-2u}-\frac{1}{4}u
\\将f(0)=0,f'(0)=0代入
\\\left\{\begin{array}{l}
C_1+C_2=0
\\2C_1-2C_2-\frac{1}{4}=0
\end{array}\right.
\\得C_1=\frac{1}{16},C_2=-\frac{1}{16}
\\∴f(u)=\frac{1}{16}e^{2u}-\frac{1}{16}e^{-2u}-\frac{1}{4}u
$$

$$
z=x^2+y^2(z\leq1)
$$


$$
补\Sigma_1:\left\{\begin{array}{l}
x^2+y^2\leq1
\\z=1
\end{array}\right.
\\方向取下侧，\Omega与\Sigma与\Sigma_1围成
\\\unicode{x222F}_{\Sigma+\Sigma_1}(x-1)^3\mathrm{~d}y\mathrm{~d}z+(y-1)^3\mathrm{~d}z\mathrm{~d}x+(z-1)\mathrm{~d}x\mathrm{~d}y\\\stackrel{Gauss}{=}-\iiint_{\Omega}\left[3(x-1)^{2}+3(y-1)^{2}+1\right] d x d y d z
\\=-\int_0^1\mathrm{~d}z\iint_{D_z}(3x^2+3y^2\cancel{-6x}\cancel{-6y}+7)\mathrm{~d}x\mathrm{~d}y
\\=-\int_{0}^{1}\mathrm{~d}z\int_0^{2\pi}\mathrm{~d}\theta\int_{0}^{\sqrt z}(3r^2+7)r\mathrm{~d}r=-4\pi
\\
$$

$$
\iint_{\Sigma_1}\cancel{(x-1)^3\mathrm{~d}y\mathrm{~d}z}+\cancel{(y-1)^3\mathrm{~d}z\mathrm{~d}x}+(z-1)\mathrm{~d}x\mathrm{~d}y=\iint_{\Sigma_1}(z-1)\mathrm{~d}x\mathrm{~d}y
\\把z=1代入,得\iint_{\Sigma_1}(z-1)\mathrm{~d}x\mathrm{~d}y=0
\\∴I=\unicode{x222F}_{\Sigma+\Sigma_1}-\iint_{\Sigma_1}=-4\pi
$$


$$
\lim_{n\to\infty}a_n=0
$$

$$
\sum_{n=1}^{\infty}\frac{a_n}{b_n}
$$

$$
\lim_{n\to\infty}a_n=0
$$

$$
\cos a_n - a_n=\cos b_n\Rightarrow a_n=\cos a_n -\cos b_n>0
$$

$$
\sum_{n=1}^{\infty}bn收敛
$$

$$
\therefore\lim_{n\to\infty}b_n=0
$$

$$
\text { 若 } \sum_{n=1}^{\infty} v_{n} \text { 收敛, 则 } \sum_{n=1}^{\infty} u_{n} \text { 收敛; 若 } \sum_{n=1}^{\infty} u_{n} \text { 发散, 则 } \sum_{n=1}^{\infty} v_{n} \text { 发散 }
$$

$$
\lim _{n \rightarrow \infty} \frac{u_{n}}{v_{n}}=\left\{\begin{array}{l}
0, \sum_{n=1}^{\infty} v_{n} \text { 收敛 } \Rightarrow \sum_{n=1}^{\infty} u_{n} \text { 收敛 } \\
\infty, \sum_{n=1}^{\infty} v_{n} \text { 发散 } \Rightarrow \sum_{n=1}^{\infty} u_{n} \text { 发散 } \\
A \neq 0, \sum_{n=1}^{\infty} v_{n} \text { 和 } \sum_{n=1}^{\infty} u_{n} \text { 敛散性同 }
\end{array}\right.
$$

$$
0, \sum_{n=1}^{\infty} v_{n} \text { 收敛 } \Rightarrow \sum_{n=1}^{\infty} u_{n} \text { 收敛 }\\
\infty, \sum_{n=1}^{\infty} v_{n} \text { 发散 } \Rightarrow \sum_{n=1}^{\infty} u_{n} \text { 发散 } \\
A \neq 0, \sum_{n=1}^{\infty} v_{n} \text { 和 } \sum_{n=1}^{\infty} u_{n} \text { 敛散性同 }
$$

$$
\frac{a_n}{b_n}\le M\cdot b_n\quad (M>0)
$$

$$
\frac{a_n}{b_n}=\frac{\cos a_n-\cos b_n}{b_n}=
$$

$$
\lim_{n\to\infty}\frac{\frac{a_n}{b_n}}{b_n}=A(存在)
$$

$$
\sum_{n=1}^{\infty}b_n\\
\sum_{n=1}^{\infty}a_n
$$

$$
\lim_{n\to\infty}b_n=0\\\lim_{n\to\infty}a_n=0
$$

$$
\lim_{n\to\infty}\frac{\frac{a_n}{b_n}}{b_n}=A(存在)
$$

$$
\sum_{n=1}^{\infty}\frac{a_n}{b_n}
$$

$$
\frac{a_n}{b_n}=\frac{\cos a_n-\cos b_n}{b_n}=-\frac{\sin \xi_{n}\left(a_{n}-b_{n}\right)}{b_{n}}=\frac{\sin \xi_{n}\left(b_{n}-a_{n}\right)}{b_{n}}<\sin\xi_n<\xi_n<b_n
$$

$$ {\}
\exists \xi_{n} \in\left(a_{n}, b_{n}\right) \subset\left(0, \frac{\pi}{2}\right) .
$$

$$
-\frac{\sin \xi_{n}\left(a_{n}-b_{n}\right)}{b_{n}}
$$

$$
\sin \xi_{n}<\xi_{n}
$$

$$

$$

$$
=\frac{2 \sin \left(\frac{a_{n}+b_{n}}{2}\right) \sin \left(\frac{b_{n}-a_{n}}{2}\right)}{b_{n}}\leq M\cdot b_n
$$

