# 目录



## 1.1 试题

* P57



## 1.2 解析

* P211



# 题目

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

![image-20230719143340544](https://cvp.oss-cn-shanghai.aliyuncs.com/picgo/202307191433634.png)

# 2 解法二：利用行列式的性质与公式计算行列式

