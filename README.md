# 2020-Huamu-Cup-Line-Recognition-Problem
2020华录杯 车道线识别问题

排名: 18/576

本赛题是源于百度地图真实场景数据的车道线检测赛题，是一个图像的语义分割问题，给出了19种车道线进行识别，加上背景可以看成是20类的分类问题。这是本人第一次参加cv竞赛，了解的模型不多，最后选择了DeepLabv3p单模进行训练，根据图像特点，裁剪了无车道的上半部分以减小训练时间，训练使用多尺度的图像进行训练，先训练缩小后的图像，然后使用得到的模型在训练原始大小的图像，针对图像模糊问题进行了图像的过和滤锐化。

开源地址：https://aistudio.baidu.com/aistudio/projectdetail/1050598
