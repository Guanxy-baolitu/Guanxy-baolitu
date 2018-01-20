---
title: opencv习作---计算机视觉+视频关键帧
date: 2017-01-25 11:44:50
tags: [opencv,C++]
categories: 程序
---

# 计算机视觉课程习作

<img src="http://ovbvzzha4.bkt.clouddn.com/17-8-27/61502389.jpg" alt="">
<p><img src="http://ovbvzzha4.bkt.clouddn.com/17-8-27/3348562.jpg" alt=""><br><img src="http://ovbvzzha4.bkt.clouddn.com/17-8-27/77359446.jpg" alt=""><br><img src="http://ovbvzzha4.bkt.clouddn.com/17-8-27/30942795.jpg" alt=""></p>

### 描述
* 角点检测：对输入的一张彩色图像，实现Harris Corner检测算法:
* 人脸识别：实现三个程序（三个执行文件），分别对应人脸训练、识别、重构；显示训练时能量百分比对应的维数并计算用时；
* 相机标定：输入一组关于棋盘的图像文件，标定相机后，输出摄像机标定后的参数；输入同一相机拍摄图像的俯瞰视角变换，显示并保存输出俯瞰视角变换后的图像。
* CNN手写识别：调用深度学习开发工具TensorFlow， 用MNIST手写数字数据集（0-9一共十个数字）6万样本实现对LeNet-5 的训练。对输入的一个序号所代表的MNIST数据集的样本，能用自己训练完成的LeNet-5输出识别结果。对MNIST的1万测试样本进行测试，获得识别率是多少

# 视频关键帧提取工具
<img src="http://ovbvzzha4.bkt.clouddn.com/17-8-27/72360167.jpg" alt="">
### 描述
* 以三种模式，从文件对话框选取视频文件，提取关键帧后将其保存为图片序列
* 三种算法为：颜色直方图+特征转变法；运动矢量+双阈值渐变镜头边界法；图象矩+聚类