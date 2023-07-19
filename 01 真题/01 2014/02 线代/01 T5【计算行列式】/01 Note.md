# 目录



## 1.1 试题

* P57



## 1.2 解析

* P211



# 题目 计算行列式

<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202307151725362.png" style="zoom:67%;" />



# 1 解法一：按某一行（列）展开定理计算行列式

$$
\left|\begin{array}{llll}
0 & a & b & 0 \\
a & 0 & 0 & b \\
0 & c & d & 0 \\
c & 0 & 0 & d
\end{array}\right|=a*(-1)^{(1+2)}\left|\begin{array}{llll}
a & 0 & b \\
0 & d & 0 \\
c & 0 & d
\end{array}\right|+b*(-1)^{(1+3)}\left|\begin{array}{llll}
a & 0 & b \\
0 & c & 0 \\
c & 0 & d
\end{array}\right|=\\-a*[(ad^2)-bcd]+b(acd-bc^2)=abcd-a^2d^2+abcd+b^2c^2=-(ad-bc)^2\\
选B
$$



## 1.1 三阶行列式——|×|的计算公式

<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202307151821056.png" alt="image-20230715182109011" style="zoom:50%;" />



# 2 解法二：利用行列式的性质与公式计算行列式


$$
\left|\begin{array}{llll}
0 & a & b & 0 \\
a & 0 & 0 & b \\
0 & c & d & 0 \\
c & 0 & 0 & d
\end{array}\right| \stackrel{r_{1} \leftrightarrow r_{4}}{=}-\left|\begin{array}{llll}
c & 0 & 0 & d \\
a & 0 & 0 & b \\
0 & c & d & 0 \\
0 & a & b & 0
\end{array}\right| \stackrel{c_{2} \leftrightarrow c_{4}}{=}\left|\begin{array}{llll}
c & d & 0 & 0 \\
a & b & 0 & 0 \\
0 & 0 & d & c \\
0 & 0 & b & a
\end{array}\right|=(b c-a d)(a d-b c)=-(a d-b c)^{2} .
$$



## 2.1 拉普拉斯展开式

$$
如果  \boldsymbol{A}  与  \boldsymbol{B}  分别是  m  阶和  n  阶矩阵, \\则

\left|\begin{array}{cc}
\boldsymbol{A} & * \\
\boldsymbol{O} & \boldsymbol{B}
\end{array}\right|=\left|\begin{array}{cc}
\boldsymbol{A} & \boldsymbol{O} \\
* & \boldsymbol{B}
\end{array}\right|=|\boldsymbol{A}||\boldsymbol{B}|,\\\left|\begin{array}{cc}
\boldsymbol{O} & \boldsymbol{A} \\
\boldsymbol{B} & *
\end{array}\right|=\left|\begin{array}{cc}
* & \boldsymbol{A} \\
\boldsymbol{B} & \boldsymbol{O}
\end{array}\right|=(-1)^{m n}|\boldsymbol{A}||\boldsymbol{B}| .
$$



## 2.2 行列式两行（列）互换，行列式添负号

<img src="https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202307191459309.png" alt="image-20230719145922230" style="zoom:50%;" />
