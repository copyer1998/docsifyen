# Divide and conquer - 分治法

在计算机科学中，分治法是一种很重要的算法。分治法即『分而治之』，把一个复杂的问题分成两个或更多的相同或相似的子问题，再把子问题分成更小的子问题……直到最后子问题可以简单的直接求解，原问题的解即子问题的解的合并。这个思想是很多高效算法的基础，如排序算法（快速排序，归并排序）等。

## 分治法思想

分治法所能解决的问题一般具有以下几个特征：

1. 问题的规模缩小到一定的程度就可以容易地解决。
2. 问题可以分解为若干个规模较小的相同问题，即该问题具有**最优子结构**性质。
3. 利用该问题分解出的子问题的解可以合并为该问题的解。
4. 该问题所分解出的各个子问题是相互独立的，即子问题之间不包含公共的子问题。

分治法的三个步骤是：

1. 分解（Divide）：将原问题分解为若干子问题，这些子问题都是原问题规模较小的实例。
2. 解决（conquer）：递归地求解各子问题。如果子问题规模足够小，则直接求解。
3. 合并（combine）：将所有子问题的解合并为原问题的解。

分治法的经典题目：

1. 二分搜索
2. 大整数乘法
3. Strassen矩阵乘法
4. 棋盘覆盖
5. 归并排序
6. 快速排序
7. 循环赛日程表
8. 汉诺塔
