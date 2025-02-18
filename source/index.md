# 深入浅出PyTorch
PyTorch是利用深度学习进行数据科学研究的重要工具，在灵活性、可读性和性能上都具备相当的优势，近年来已成为学术界实现深度学习算法最常用的框架。

考虑到PyTorch的学习兼具理论储备和动手训练，两手都要抓两手都要硬的特点，我们开发了《深入浅出PyTorch》课程，期望以组队学习的形式，帮助大家从入门到熟练掌握PyTorch工具，进而实现自己的深度学习算法。

我们的愿景是：通过组队学习，大家能够掌握由浅入深地PyTorch的基本知识和内容，经过自己的动手实践加深操作的熟练度。同时通过项目实战，充分锻炼编程能力，掌握PyTorch进行深度学习的基本流程，提升解决实际问题的能力。

学习的先修要求是，会使用Python编程，了解包括神经网络在内的机器学习算法，勤于动手实践。

《深入浅出PyTorch》是一个系列，一共有三个部分。已经上线的是本系列的第一、二部分，后续会不断更新《深入浅出PyTorch》（下），给出更贴合实际应用的实战案例。

```{toctree}
:maxdepth: 2
:caption: 目录
第一章/index
第二章/index
第三章/index
第四章/index
第五章/index
第六章/index
第七章/index
第八章/index
第九章/index
第十章/index
```

## 人员安排
|   成员  |                个人简介               |          个人主页         |
|:-------|:-------------------------------------|:-------------------------:|
|  牛志康 | DataWhale成员，西安电子科技大学本科生 | [个人主页](https://www.zhihu.com/people/obeah-82) |
|  李嘉骐 | DataWhale成员，清华大学研究生         | [个人主页](https://www.zhihu.com/people/li-jia-qi-16-9/posts) |
| 刘洋 | Datawhale成员，中国科学院数学与系统科学研究所研究生  |  [个人主页](https://www.zhihu.com/people/ming-ren-19-34/asks)  |
| 陈安东 | Datawhale成员，中央民族大学研究生  |  [个人主页](https://andongblue.github.io/chenandong.github.io/)  |

- 教程贡献情况（已上线课程内容）：

  - 牛志康：第一章；第三章；第六章；第七章；第八章；第九章；在线内容管理

  - 李嘉骐：第三章；第四章；第五章；第六章；第七章；第八章；内容整合

  - 刘洋 &nbsp;：第二章；第三章

  - 陈安东：第二章；第三章；第七章

## 更新计划
| 内容 | 更新时间 |内容|
| :---- | :---- |:----:|
|模型初始化| &#x2705; |`torch.nn.init`的使用|
|visdom可视化| 2022.4.5 |`Visdom`的使用|
|apex| 2022.5.4 |apex的简介和使用|
|超参数的保存 | &#x2705; |介绍argparse与yaml|
|onnx| &#x2705 |讲述ONNX格式和实战例子|
|模型部署|  |Flask部署PyTorch模型|
|TorchScript|  |TorchScript|
|数据增强| &#x2705;|imgaug的使用|
|并行训练| |并行训练 |
|模型预训练 - torchhub| 2022.4.16  |torchhub的简介和使用方法|
|模型预训练 - timm|  &#x2705;|timm预训练模型的使用方法|
|模型预训练 - openmmlab| 2022.4.27|openmmlab系列的使用|
|目标检测 - yolo系列|  |Yolo系列介绍与trick实现|
|目标检测 - SSD|  |SSD的简介和实现|
|目标检测 - RCNN系列|  |Fast-RCNN & Mask-RCNN|
|目标检测 - DETR|  |DETR的实现|
|图像分类 - GoogLeNet| 2022.5.11 |GoogLeNet的介绍与实现|
|图像分类 - Vision transformer| 2022.5.18 |Vit介绍与实现|
|图像分类 - MobileNet系列|  2022.4月|MobileNet系列介绍与实现|
|图像分类 - GhostNet| 2022.4月 |GhostNet代码讲解|
|生成式对抗网络 - 生成手写数字实战| 2022.5.25 |生成数字并可视化|
|生成式对抗网络 - DCGAN|  ||
|风格迁移 - StyleGAN|  ||
|生成网络 - VAE|  ||
|图像分割 Deeplab系列|  |Deeplab系列代码讲解|
|自然语言处理 LSTM|  |LSTM情感分析实战|
|自然语言处理 RNN|  |RNN名字分类|
|自然语言处理 Transformer|  ||
|自然语言处理 BERT|  ||
|视频| | 待定|
|音频| | 待定|
|自定义CUDA扩展和算子|||
## 课程编排与使用方法

部分章节直播讲解请观看B站回放（持续更新）：[bilibili链接](https://www.bilibili.com/video/BV1L44y1472Z)

- 课程编排：
  深入浅出PyTorch分为三个阶段：PyTorch深度学习基础知识、PyTorch进阶操作、PyTorch案例分析。

- 使用方法:

  我们的课程内容都以markdown格式或Jupyter notebook的形式保存在本仓库内。除了多看加深课程内容的理解外，最重要的还是动手练习、练习、练习

- 组队学习安排:

  第一部分：第一章到第四章，学习周期：10天；

  第二部分：第五章到第八章，学习周期：11天

## 鸣谢与反馈

- 非常感谢DataWhale成员 叶前坤 @[PureBuckwheat](https://github.com/PureBuckwheat) 和 胡锐锋 @[Relph1119](https://github.com/Relph1119) 对文档的细致校对！
- 如果有任何想法可以联系我们DataWhale  

![二维码](./figures/qrcode.jpeg)

