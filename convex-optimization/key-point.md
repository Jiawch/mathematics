

## Exam016(1)

1. 函数：强凸、严格凸、凸、非凸
  - 凸函数定义（3个）
  - 凸函数判定

2. ADMM 解 lasso 问题
  - lasso：是一种采用了L1正则化的线性回归方法
  - ADMM（交替方向乘子法）：用于解决存在**两个优化变量**的**只含等式约束**的优化类问题
    - ![](https://www.zhihu.com/equation?tex=%5Cbegin%7Baligned%7D+%26%5Cmin_%7Bx%2Cz%7D%5C+%5C+f%28x%29%2Bg%28z%29+%5C%5C+%26s.t.+%5C+%5C+Ax+%2B+Bz+%3D+c+%5Cend%7Baligned%7D%5C%5C)
  - 步骤
  - ref
    - [【凸优化笔记7】-交替方向乘子法（ADMM）](https://zhuanlan.zhihu.com/p/106896627)
    
3. Coordinate Descent
