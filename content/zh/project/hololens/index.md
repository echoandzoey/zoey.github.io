---
title: Holo Chaoshan!
summary: Write about your project here...
tags:
  - HCI
date: 2022-01-01
---

## **Introduction**

Holo, Chaoshan 是一个 MR 虚拟空间交互项目，设想了虚拟剧本杀的互动交互。在这个项目中，我实现了 Hololens（MR 设备）和 Arduino 的相互联动。第一阶段：Hololens-->Arduino 通过用手势控制虚拟环境中的物体，从而带动现实空间的移动.第二阶段：Arduino--> Hololens 通过硬件交互，导致虚拟环境中场景发生改变。
这个项目和潮汕当地企业潮聚文化合作，尝试了商业落地。

<!-- ### <span style="color: #fed494;">_Recognition_</span>

2022 IEEE Conference on Games (CoG) doi: 10.1109/CoG51982.2022.9893555。 -->

## **Reserach**

### <span style="color: #fed494;">_Definition_</span>

虚拟人产业因元宇宙概念的兴起而被推向前沿。根据行业服务平台量子比特发布的《虚拟数字人深度行业报告》，到 2030 年，中国虚拟数字人的整体市场规模将达到 2700 亿元人民币。可以预见，虚拟数字人将渗透到各个行业中。同时，直播行业的兴起催生了 Vtuber（视频 YouTuber）这一新身份，即虚拟主播。

<img src="intro.png" alt="图片描述" style="width: 100%; height: auto;">

### <span style="color: #fed494;">_Contrast_</span>

为了更好地了解当前直播的状态，我对顶级真人主持人和虚拟主持人进行了研究，并在各个方面进行了比较。结果如下：

<img src="contrast.png" alt="图片描述" style="width: 100%; height: auto;">

### <span style="color: #fed494;">_Reference_</span>

受到“堡垒之夜”虚拟音乐会《天文》和《格列佛游记》的启发，我们认为主持人和观众之间可以存在巨大的大小差异。

<div style="display: flex; width: 100%;">
  <div style="flex: 1;">
    <img src="fortnite.png" alt="堡垒之夜" style="width: 100%; height: auto;">
  </div>
  <div style="flex: 1;">
    <img src="gulliver.png" alt="格列佛游记" style="width: 100%; height: auto;">
  </div>
</div>

## **Concept**

### <span style="color: #fed494;">_About MVEAG_</span>

我们最终设计了**MVEAG**模型，目标是与我们的观众建立更深入的参与。它特别针对喜欢观看游戏直播的年轻人。

观众不再是直播的旁观者，而是可以与 Vtuber 互动并参与互动游戏。由于直播通常包含一个主播和多个观众，因此游戏被设计为一种一对多的非对称游戏。同时，为了形象地描述这种非对称性，我们将项目命名为“格列佛的世界”。

<img src="MVEAG.png" alt="MVEAG" style="width: 100%; height: auto;">

### <span style="color: #fed494;">_About the Gulliver’s World_</span>

在格列佛的世界中，主播扮演格列佛的角色，观众扮演矮人的角色。两个 Vtuber 同时出现在地图上进行 PK。格列佛不能在地图上移动，因此需要与自己的矮人合作攻击另一个格列佛。Vtuber 与观众之间的互动策略可以非常多样化。

为了更好地引导观众，我们设计了几种适合不同场景的基本类型的矮人，其中矮人寻找水晶，收集它们并与敌人战斗。

<img src="concept.png" alt="概念" style="width: 100%; height: auto;">

## **GamePlay**

游戏玩法的工作流程如下：

<img src="gameplay.png" alt="游戏玩法" style="width: 100%; height: auto;">

## **Technical Path**

然后我们进行动作捕捉。我们首先尝试了光学动作捕捉，捕捉到的动作很好，但不能实时计算，所以我们改变了方案。

<img src="motionCapture.png" alt="动作捕捉" style="width: 100%; height: auto;">
<img src="Kinectconnection.png" alt="Kinect" style="width: 100%; height: auto;">

## **Game shots**

<img src="screenshot2.png" alt="游戏截图" style="width: 100%; height: auto;">

## **Vedio**

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe src="https://www.youtube.com/embed/KB9zi9uHsMg?si=je0Zxrw0ZHwKtVPJ&#34;" frameborder="0" style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" allowfullscreen></iframe>
</div>

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/KB9zi9uHsMg?si=je0Zxrw0ZHwKtVPJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> -->
