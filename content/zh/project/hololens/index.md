---
title: Holo Chaoshan!
summary: Write about your project here...
tags:
  - HCI
date: 2022-01-01
---

## **Introduction**

Holo, Chaoshan 是一个 MR 虚拟空间交互项目，设想了现实空间和虚拟场景的互动交互。在这个项目中，我实现了 Hololens（MR 设备）和 Arduino 的相互联动。第一阶段：Hololens-->Arduino 通过用手势控制虚拟环境中的物体，从而带动现实空间的移动.第二阶段：Arduino--> Hololens 通过硬件交互，导致虚拟环境中场景发生改变。
这个项目和潮汕当地企业合作，尝试了商业落地。

<!-- ### <span style="color: #fed494;">_Recognition_</span>

2022 IEEE Conference on Games (CoG) doi: 10.1109/CoG51982.2022.9893555。 -->

## **Reserach**

### <span style="color: #fed494;">_situation&Concept_</span>

在我们参观古建筑的时候，历史的痕迹让这些建筑只留下断垣残壁，很难想象到昔日的景象。另一方面，MR技术的发展让在现实空间中和虚拟物体进行交互成为可能，因此本项目希望使用MR技术，让游客在参观景象的时候，可以通过虚拟空间和现实空间交互的方式，以一种全新的方式发现历史的美。并且设计了一些互动游戏的方式，增加游客的沉浸体验。

<img src="SITUATION.png" alt="图片描述" style="width: 100%; height: auto;">


## **Installation**
我们首先搭建了一个木头装置，来简单示意我们的现实场景。

<img src="installation.png" alt="MVEAG" style="width: 100%; height: auto;">

### <span style="color: #fed494;">_Period1：Hololens->Arduino_</span>
首先我们实现了通过Hololens控制虚拟场景从而影响现实空间(Arduino硬件实现)的功能。如图所示，图1展示了我们在Hololens里面看到的内容，虚拟的钢琴出现在现实的场景当中。图2-4展示了我们的使用场景。通过用手势控制虚拟场景里面的东西从而引发现实空间中的移动

<img src="period1.png" alt="Period1" style="width: 100%; height: auto;">
完整的演示视频可以在这里看到。
<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <video controls style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;">
    <source src="Holo,Chaoshan.mp4;" type="video/mp4">
  </video>
</div>

### <span style="color: #fed494;">_Period2_</span>

为了能够让参观者可以在参观的时候更加沉浸的和虚拟空间交互，我们实现了通过控制RFID卡片从而影响Hololens中虚拟场景的功能。
实现**技术框架**如下：
<div style="display: flex; width: 100%;">
  <div style="flex: 1;">
    <img src="framework.png" alt="framework" style="width: 100%; height: auto;">
  </div>
  <div style="flex: 1;">
    <img src="hardware.png" alt="hardware" style="width: 100%; height: auto;">
  </div>
</div>


## **Achievement**

最终实际场景测试如下：

<img src="expriment.png" alt="实地搭建" style="width: 100%; height: auto;">
<img src="user.png" alt="用户测试" style="width: 100%; height: auto;">

