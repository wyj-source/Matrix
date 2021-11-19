# Matrix

## 简介

- 使用TCL_Matrix.h，可以方便地对矩阵进行运算。

- 本程序更强调算法的准确性，可用于小规模问题的测试。

  对于大规模问题，程序中可能有大量对动态内存的申请、释放等操作，因此不保证程序有最高的效率。

- 目前，TCL_Matrix.h中实现了矩阵的操作包括：

  - 基本运算：
    - 矩阵加法
    - 矩阵乘法
    - 矩阵转置
  - 高级运算：
    - 矩阵求逆
    - 矩阵高斯消元
    - 求矩阵秩
    - 求行列式
    - 矩阵快速幂
    - 求解线性方程组
    - 求矩阵零空间
    - 求对称非不定矩阵的所有特征值
    - 求矩阵所有奇异值

## 可能的BUG

- 用程序对矩阵处理，往往要考虑诸多情况，难以保证绝对正确。目前已上传的代码，在本地测试样例上是通过的。
- 鉴于本人能力有限，程序中仍然可能存在bug。在使用过程中如果发现bug，欢迎提pr，或直接联系我。
- 欢迎各位向该矩阵类添加更多功能。
