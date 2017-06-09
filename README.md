# polygonsview

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-polygonsview-green.svg?style=true)](https://android-arsenal.com/details/3/4408)
[![Travis](https://img.shields.io/badge/License-Apache2.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Twitter](https://img.shields.io/badge/Gradle-2.1.0-brightgreen.svg)](https://github.com/jiangzehui/polygonsview)
[![Travis](https://img.shields.io/badge/details-1.0-orange.svg)](http://blog.csdn.net/as7210636/article/details/52692102)

模仿掌上英雄联盟能力分析效果
<br>
正在学习自定义View的同学，可以看看源码，希望对你们有帮助！
<br>
如果你觉得还不错，可以给个star，支持下，谢谢了！
<br>
# 原始图效果
![这里写图片描述](https://github.com/jiangzehui/polygonsview/blob/master/png/p2.png)
<br><br>

# 模仿效果
<br>

## gif

![gif](https://github.com/jiangzehui/polygonsview/blob/master/png/p3.gif)

<br>

## png

![这里写图片描述](https://github.com/jiangzehui/polygonsview/blob/master/png/p1.png)

<br><br>
流程
--




 1. 绘制中心线，用于计算外层多边形各点的坐标
 2. 绘制最外层多边形
 3. 分析原型图算出每个多边形之间的间距
 4. 绘制里三层多边形
 5. 绘制字体
 6. 根据进度值绘制等级进度


    <br>

难点
--



关键在于坐标的计算(三角函数的运用，哈哈)，与旋转角度的掌控。
<br>
<br>
<br>


# Attributes


| name | format | description |
| -----|:----:| ----:|
| setStr | String[] | 设置提示字体（长度必须为7位,从中上开始顺时针方向）|
| setStrColor    | color    |  设置字体颜色   |
| setOneColor    | color    |  设置最外层正多形颜色   |
| setTwoColor    | color    |   设置第二层正多形颜色  |
| setThreeColor    | color    |   设置第三层多边形颜色  |
| setFourColor    | color    |   设置最内层多边形颜色  |
| setCenterColor    | color    |   设置中心线颜色  |
| setRankColor    | color    |   设置rank线颜色  |
| setValue1    | float(0~4)    |   设置rank值1 （从中上开始顺时针方向） |
| setValue2    | float(0~4)    |   设置rank值2 |
| setValue3    | float(0~4)    |   设置rank值3 |
| setValue4    | float(0~4)    |   设置rank值4 |
| setValue5    | float(0~4)    |   设置rank值5 |
| setValue6    | float(0~4)    |   设置rank值6 |
| setValue7    | float(0~4)    |   设置rank值7 |

<br>

# Doc
http://blog.csdn.net/as7210636/article/details/52692102
<br>


# 阅读推荐

1.开源一个自己去年写的基于Xmpp协议的即时通讯社交软件 (客户端+服务端)<br> https://github.com/jiangzehui/xmpp<br><br>

2.此项目基于Retrotfit2.1+Material Design+ijkplayer开发的一个APP。目前已有的功能是 新闻，gif动图，视频播放<br>
https://github.com/jiangzehui/MD<br>


# About me

An android little developer in HeBei.<br>
If you have any suggestions, let me know.<br>
email:jianghui1992@vip.qq.com

<br>

# License

Copyright 2016 jiangzehui

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
