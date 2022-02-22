# 🔥基于PaddleDetection的医疗显微图像-结核杆菌识别
&emsp;&emsp;此项目使用PP-yolov2检测痰液中的结合杆菌，从而实现异常检测。

**相信你看完这篇项目一定会有所收获的**
>先看后赞，养成习惯

>folk收藏，人生辉煌

![](https://ai-studio-static-online.cdn.bcebos.com/f907ebf2dec34f81945f0479f0cc89fbc9789653df6a4d8f9af5e322e05eeb95)
# 一、项目背景
>结核病（Tuberculosis，TB)是由结核分枝杆菌（Mycobacterium tuberculosis) 引起的一种慢性人畜共患病，它不受年龄、性别、种族、职业、地区的影响，人体许多器官、系统均可患结核病，其中以肺结核最为常见。结核病既是一个公共卫生问题，也是一个社会经济问题，对人类的公共健康构成很大威胁，因此对其快速诊断检测就至关重要。

1.虽然染色处理可以使得结核杆菌在显微镜拍摄的医学图像中显现，医生则可以通过检测图像中的结核杆菌辅助诊断患者是否有结核病。🎯<br>2.但是通过构建准确率的目标检测模型可实现由智能系统辅助医生进行检测工作，应用于目前的医疗检测产品中能够满足真实的结核病检测需求。🎯<br>3.实现AI+医疗,为产业赋能。🎯

![](https://ai-studio-static-online.cdn.bcebos.com/ddcd43c947c84101bded5b6730f55d8d93448a90e0804e08854976cd59fa8b52)

# 二、数据简介

数据说明<br>
&emsp;&emsp;该数据集全部与结核有关，取自痰液样本。它包含1265个痰液图像以及3734个细菌的边界框。XML文件包含图像的边界框详细信息。
>数据来源 AI Research and Automated Laboratory Diagnostics
