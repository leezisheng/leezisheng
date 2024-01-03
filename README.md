# Freak嵌入式工作室&工训A413实验室介绍
  Freak嵌入式工作室位于中北大学工程训练中心A座413，负责工训A413实验室相关技术成果转化，以嵌入式电子套件及相关教程、成品电子模块开发、个人DIY电子作品为主要产品，致力于嵌入式教育和大学生创新创业比赛、电子计算机类比赛培训。
![实验室概览](https://github.com/leezisheng/leezisheng/blob/main/111.png)
# 个人信息
<table border="0">
  <tr>
    <td width="75%">
      <h1>李清水</h1>
      <p><b>本科生</b></p>
      <p><b>男</b></p>
      <p><b>汉族</b></p>
      <p><b>127岁</b></p>
      <p><b>电子DIY爱好者</b></p>
      <p><b>Freak嵌入式工作室创始人</b></p>
      <p><b>中北大学信息与通信工程学院</b></p>
      <p><b>邮箱：1069653183@qq.com</b></p>
    </td>
    <td width="50%">
      <img src="/6c2cb8b88dd6c158fcfbca3181094fa.png" width="100%">      
    </td>
  </tr>
</table>

## 研究方向
  嵌入式MCU、图像处理、机器学习、TinyML、数字信号处理
## 个人技术栈
### MCU软件开发
  1. 熟练掌握STM32、NXP、Ti等各系列32位、16位、8位单片机的运用，可以利用GCC、STM32CUBE IDE、MDK等软件对单片机进行基本外设操作，包括：GPIO使用，工作模式，通信速率，外部中断，ADC模数转换，定时器，dma数据传输 通信协议（IIC,IIIC,SPI,串行总线（rs485，rs232，rs422，全双工，半双工，单工，智能卡，can总线），单走线通信，usb，usb2.0，usb3.0，网络协议接口）；
  2. 对嵌入式实时操作系统有一定了解以及应用，可以实现基本任务创建，任务调度，消息队列，信号量，互斥组，任务同步，内存管理，Tracealyzer调试追踪。
  3. 理解代码规范，掌握基本的调试技巧，包括断点调试、单步执行、逐行执行、外设寄存器状态查看、变量监测、内存查看、逻辑分析、系统分析、时序分析、汇编调试、GDB调试。
### 图像处理
  对图像处理有一定了解以及应用，可以利用Opencv库和Keras框架完成常见神经网络模型在边缘端的部署和基本图像处理操作。 
### 上位机开发
  可以利用pyqt gui框架和ndas、Scikit-learn、Matplotlib等数据处理框架，完成和下位机的基于串口/USB的数据交互、数据展示的界面制作，或者Kivy在手机端或电脑端完成界面UI制作。 
### 嵌入式硬件设计
  1. 掌握基本原器件的作用及简单应用。初步掌握常用阻抗元件主要工作参数含义和选型。能够阅读常用器件数据手册，并根据相关参数正确设计电路。熟悉常用器件封装，能够根据需要选择合适的封装设计印刷电路板（PCB)初步掌握 PCB 设计的基本原则，包括元器件布局策略、线宽、线距及过孔、焊盘尺寸选择；熟悉 PCB 设计流程；能够使用现成的 PCB 工程查阅线路连接及其位置。
  2. 掌握最小系统的基本概念和常用的外围电路设计。能够根据最小系统要求，选择元器件，完成电路设计；
  3. 能够阅读嵌入式系统电路图，能够分析常见电路模块工作原理和参数计算。熟悉常见电路符合、标识和电路连接方法。
# 仓库介绍&相关成果
## ESP32开发板晋中理工培训版本v1.0
https://github.com/leezisheng/ESP32-EDU-BOARD-V0.1

开发板以ESP32 WROOM最小系统板为核心，板载5V降压稳压模块和供电指示电路、RS485通信模块、摇杆模块、OLED显示模块、气体传感器接口、DTH11温湿度传感器模块、18650电池盒、蜂鸣器驱动电路和按键及LED驱动电路组成。

![ESP32开发板晋中理工培训版本](https://github.com/leezisheng/leezisheng/blob/main/000.png)

## 声源定位装置及声光融合定位算法v1.0
https://github.com/leezisheng/Sound-source-location

### 声源定位装置

以K210微控制器为核心控制单元，设计一个基于TDOA算法的声源定位系统。利用麦克风阵列采集声源信号，通过时间差到达（TDOA）算法进行信息处理，借助卡尔曼滤波优化数据变量，从而实现声源方向的高精度定位。实验结果表明，该声源定位跟踪系统在定位精度、数据处理频率和定位范围方面均表现出优异的性能，定位精度可达到10厘米以内，数据处理频率为100Hz，定位范围可覆盖方圆10米。这一研究成果为实时声源定位和跟踪领域提供了一种高效可靠的解决方案，有望在多种应用场景中发挥关键作用。

### 基于声光数据融合的电力巡检机器人室内定位方法

传统的巡检机器人定位方法往往是使用基于射频技术的蓝牙定位、UWB定位方法，然而在变电站的室内巡检场景中，如信息机房、配电室、主控室、高压开闭室等，由于存在工频噪声、大功率电力设备运行使得电磁干扰较大，同时电磁信号本身具有多径效应，导致基于射频技术的定位方法误差极大；而基于激光点云和计算机视觉的定位方法计算量较大，同时由于变电站室内环境复杂，导致使用基于激光点云和计算机视觉的定位方法的巡检机器人往往无法实现精确的室内定位。

因此，本方法提出一种基于白光LED定位技术和声源定位相结合的方法，其中白光LED定位技术利用对搭载在电力巡检机器人车体上的光电探测器接收不同位置白光LED光强度的比值进行计算实现室内定位，这里考虑到室内光照受到遮挡的情况，使用基于到达时延差的声源定位方法作为补偿，利用BP神经网络模型实现两种方法的融合，在保证定位实时性的情况下，实现高精度的室内电力巡检机器人定位。

![声源定位装置及声光融合定位算法](https://github.com/leezisheng/leezisheng/blob/main/001.png)

## 尺寸测量装置v1.0

https://github.com/leezisheng/Non_contact_object_size_measurement

基于机器视觉的尺寸测量已广泛应用到工业生产的各个场合，本次电赛题目以基于机器视觉的尺寸测量技术为基础，要求对简化后的待测量模型（圆形、三角形、矩形进行识别）。
本设计基于OpenMV机器视觉模块的无接触尺寸测量系统采用霍夫变换和颜色阈值检测的方法实现对摄像头中心点直线上待测量模型的尺寸计算，并且将测量得到的尺寸数据显示于OLED屏幕上，同时利用多项式拟合方法求得直径像素数目、物体距离和物体尺寸的关系。经测试，尺寸及距离测量误差保持在1%以下，可以满足精准性和实时性的需求。

![尺寸测量装置](https://github.com/leezisheng/leezisheng/blob/main/002.png)

## 身份识别和体温测量装置v1.0

本系统以K210单片机为控制核心，以MLX90614红外测温传感器模块、LCD显示模块为主要工作模块，附加了稳压及其他用电器模块等集成为了该温度测量与身份识别装置的主体。该装置在获取到相机所捕捉到的图像后，通过提前设定好的并烧录成功的模型，K210主控单元会对获取到的图像进行逐步处理，再将处理后的结果输出在LCD显示屏上。K210单片机负责照片采集和识别判断，并将采集的照片处理，得到对应的特征数据，将这些特征数据组合成特征数据库。在识别模式下，主控单元会根据摄像头实时捕捉到的图像的变化来识别图像中相应的特征。温度测量以红外测温模块为主，红外测温传感器通过I2C通讯将采集到的信息传输到K210单片机，K210单片机将信息进行处理转化成摄氏温度，然后将该摄氏温度实时输出到LCD屏上，若该摄氏温度超过提前设定好的温度阈值，则会在LCD屏上显示出警告语句。本装置基本能够实现题目要求，测试正常。

![身份识别和体温测量装置](https://github.com/leezisheng/leezisheng/blob/main/003.png)

## CO2红外式传感器温度补偿算法v1.0

https://github.com/leezisheng/Gas-sensor-voltage-concentration-curve-fitting

https://github.com/leezisheng/NDIR_CO2

双通道热释电红外二氧化碳传感器拟合算法程序，多项式拟合算法，使用Python编写，包括txt文件读取、数据拟合、数据预测和MSE误差计算模块。

![CO2红外式传感器温度补偿算法](https://github.com/leezisheng/leezisheng/blob/main/005.png)

## 猪场环境监测系统v1.0

https://github.com/leezisheng/Farm-environment-monitoring-device---stand-alone-version

针对现有规模性生猪养殖场环境监测系统中普遍存在的监测有害气体种类单一、缺乏对环境风险的整体评估的缺点，本文设计了一种基于阿里云的养殖场多组分有害气体及温湿度监测系统，设备主机端在采集计算当前区域中多种有害气体浓度后使用轻量级物联网MQTT协议将数据回传到物联网平台端，物联网平台端进行实时数据展示、数据存储并结合综合环境评估体系对环境进行评分，经测试系统可以满足规模性生猪养殖场对于环境监测系统可靠性、实时性和稳健性的需求。

![猪场环境监测系统v1.0](https://github.com/leezisheng/leezisheng/blob/main/004.png)

![猪场环境监测系统v1.0](https://github.com/leezisheng/leezisheng/blob/main/006.png)

![猪场环境监测系统v1.0](https://github.com/leezisheng/leezisheng/blob/main/007.png)

















<div align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=leezisheng&theme=xcode" /> </div>
<div align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=leezisheng" /> </div>

[![Readme Card](https://github-readme-stats.vercel.app/api?username=leezisheng&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=leezisheng&layout=compact&exclude_repo=leezisheng.github.io&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515)](https://github.com/anuraghazra/github-readme-stats)

+ ![leezisheng](https://komarev.com/ghpvc/?username=leezisheng)
