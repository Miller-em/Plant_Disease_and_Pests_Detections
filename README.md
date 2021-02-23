# 基于人工智能的植物病害检测系统



## 项目背景

当前AI技术快速发展，特别是深度学习技术在CV领域的突出表现。我们目前很多技术都可以用到深度学习的技术进行改进，对于目标检测领域来说， 传统的方法是对图像本身特征进行设定，注重的是特征提取，而深度学习则靠的是计算机自己理解特征，这样来看就能够充分的提高目标检测的效率同时还少去了对检测目标的特征的描述。有了这样的以深度学习支持的目标检测，我们就可以做一些能够解决生活中的实际问题的事情。本项目就是本着这样的想法，能够利用人工智能技术解决生活中的实际问题。

本项目解决的是，农业中对于植物病虫害的检测问题，我们目前对于病虫害还是基本属于人为检测，所以我们正在考虑向人工智能技术靠拢，能够让一些计算设备帮我们完成这么一个病虫害的检测推理，从而帮助农民实现一个足不出户就能够得到植物的健康信息。于是就想到了利用pytorch训练检测模型，部署在Jetson Nano上面进行推理预测，最后能够通过手机随时查看植物的健康信息（是否遭受病害，虫害）。



## 项目平台及环境

- **Ubuntu 16.04LTS**
- **pytorch 1.7.0**
- **CUDA 10.0**



## 数据集介绍



