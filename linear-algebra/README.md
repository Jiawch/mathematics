## linear algebra

### 基本定义

- 奇异/非奇异：== 不可逆/可逆

> 数学上，“奇异”（singular）一词用来形容破坏了某种优良性质的数学对象。对于矩阵来说，“可逆”是一个好的性质，不可逆的矩阵就称为“奇异”矩阵。

- 正定/半正定：== 对称，特征值全为正数/正数或0

  - 正定矩阵(PD):  给定一个大小为 nXn 的实对称矩阵 A ，若对于任意长度为 n 的非零向量 X，有 ![](https://www.zhihu.com/equation?tex=X%5ETAX%3E0) 恒成立，则矩阵 A 是一个正定矩阵。  
  - 半正定矩阵(PSD)  给定一个大小为 nXn 的实对称矩阵 A ，若对于任意长度为 n 的非零向量 X，有 ![](https://www.zhihu.com/equation?tex=X%5ETAX≥0) 恒成立，则矩阵 A 是一个半正定矩阵。

> 正定/半正定矩阵的二次型（二元齐次式）都是**过原点的**、**开口向上的**超抛物面

- 正交矩阵：== 转置即为逆

### 矩阵求导

- [速查](https://xfdj.github.io/2020/08/16/矩阵微积分公式速查/)

### 矩阵运算律

- 加法交换律
- 乘法结合律、乘法分配律

### [几个常用公式](https://zhuanlan.zhihu.com/p/102361748)

- ![](https://www.zhihu.com/equation?tex=a%5ETb%3Db%5ETa)
- ![](https://www.zhihu.com/equation?tex=%5Cfrac%7B%5Cpartial+y%5ETx%7D%7B%5Cpartial+x%7D%3Dy)
- ![](https://www.zhihu.com/equation?tex=%5Cfrac%7B%5Cpartial+X%5ETAX%7D%7B%5Cpartial+X%7D%3D%28A%2BA%5ET%29X)
- ![](https://www.zhihu.com/equation?tex=%7C%7Ca-b%7C%7C_2%5E2%3D%28a-b%29%5ET%28a-b%29+%3D%7C%7Ca%7C%7C_2%5E2-2a%5ETb%2B%7C%7Cb%7C%7C_2%5E2)
- ![](https://www.zhihu.com/equation?tex=%5Cfrac%7B%5Cpartial+%7C%7CAx%2Bb%7C%7C_2%5E2%7D%7B%5Cpartial+x%7D%3D2A%5ET%28Ax%2Bb%29)


