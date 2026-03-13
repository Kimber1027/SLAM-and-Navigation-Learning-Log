Paper: RoNIN: Robust Neural Inertial Navigation in the Wild  
Conference: ICRA 2020  

## 1 项目简介

RoNIN 是一个基于深度学习的惯性导航方法，
利用 IMU 数据预测位移轨迹。

该项目使用：

- ResNet
- LSTM / TCN

从 IMU 数据估计二维位移。

## 2 参考资料

Paper:
https://arxiv.org/abs/1905.12853

Code:
https://github.com/Sachini/ronin

## 3 主要思路

输入：

IMU 数据

输出：

位移轨迹

模型结构：

IMU sequence → neural network → displacement