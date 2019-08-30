# 一些数学的计算公式与实现
整理最近一个项目使用到的数学工具公式
1. 复数的加、减、乘、除、模
2. 离散傅里叶变换（DFT）。快速离散傅里叶变换（FFT）
    1. DFT可以输入任意长度的数据进行变换
    2. 但是FFT的数学原理使其只能输入2的幂次方长度的数组，不足补零。
    3. DFT主要用于验证FFT的计算结果，生产过程中会使用FFT，因为DFT计算量太大计算时间太长。
3. 矩阵的加、减、乘、左除、右除、转置、逆矩阵、单位矩阵
4. 3维空间变换
    1. 沿x,y,z轴平移
    2. 绕x,y,z轴旋转
5. 直线
    1. 点到直线的距离
    2. 最小二乘法直线拟合
6. 平面
    1. 点到平面的距离
    2. 最小二乘法平面拟合


