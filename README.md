# Architecture

**体系结构实验**

指导书网址：https://hitsz-lab.gitee.io/computer-arch/lab1/part1/

**实验二PartA，实现一个直接相连的Cache**
=======
**实验二PartA，实现一个直接相连的Cache**

1.Cache总容量为128B

2.每块为16字节

3.包括8个Cache块

**实验二PartB，利用缓存机制优化矩阵加法运算**
=======
**实验二PartB，利用缓存机制优化矩阵加法运算**

1.在partA完成的基础上，对给定的矩阵A[8][8]和矩阵B[8][8]，实现矩阵加法运算，矩阵C=A+B。

要使得Cache的不命中率Miss尽可能少。

2.说明在给的汇编代码中，Cache测试.asm是原来的标准文件；Cache测试(改).asm是采用投机取巧的方法，巧妙利用矩阵A和B的数据特性做的；Cache测试(改改).asm是常规做法，采用了RAM来做。

