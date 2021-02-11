# 天文调谐软件（Astrochron2）
![language](https://img.shields.io/github/languages/top/swsoyee/2019-ncov-japan?style=flat-square&logo=r)
![last commit](https://img.shields.io/github/last-commit/swsoyee/2019-ncov-japan?style=flat-square)

`🇨🇳 中文` | [`🇺🇸 English`](https://github.com/swsoyee/2019-ncov-japan/blob/master/README.en.md)

该项目主要使用`R`语言与`shiny`以及其他的开源软件包开发的用于处理古气候数据处理、分析及可视化。主要功能包括根据控制点锚定时间、周期分析、天文调谐效果检测以及常用的数据处理，同时提供各种形式的日照量参数等多种功能供中外登录用户使用，推荐用户使用火狐浏览器访问该网页。
## 在线访问链接

1. [🇨🇳 中文版](https://pengxz.shinyapps.io/Astrochron2/)
2. [🇺🇸 English Version](https://pengxz.shinyapps.io/Astrochron2/)

###### `利用右侧栏可实现中英文界面互换`
## 网站截屏

![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/login.png)

## 关于本站的数据

本站所用数据需要用户提供，主要分为以下三类：

1. 深度—指标列数据和时间锚定点数据结合使用将深度列转换为时间列，或者是将时间—指标列数据和时间锚定点数据结合使用将原始时间转换为需校正的时间点，本网站提供了[范例数据](https://github.com/Pengxz-tm/Astrochron2)供用户测试使用(包括[深度-指标数据](https://github.com/Pengxz-tm/Astrochron2/blob/main/%E9%80%9A%E7%94%A8%E6%95%B0%E6%8D%AE.xlsx)和[时间锚定点数据](https://github.com/Pengxz-tm/Astrochron2/blob/main/%E6%97%B6%E9%97%B4%E9%94%9A%E5%AE%9A%E6%95%B0%E6%8D%AE.xlsx))；
2. [深海氧同位素数据](https://github.com/Pengxz-tm/Astrochron2/blob/main/LR04_Stack_0_5320ka.xlsx)和[黄土高原不同剖面磁化率数据](https://github.com/Pengxz-tm/Astrochron2/blob/main/%E8%8C%83%E4%BE%8B%E6%95%B0%E6%8D%AE.xlsx)(时间-指标)也可被使用；
3. 用户可根据自己的需要在右侧栏上传自己需处理的文件，深度适宜以`厘米(cm)`为单位，时间适宜以`千年(ka)`为单位。

由于用户上传数据可能种类多样，因此可参考本站提供的范例数据适当调整格式修改。此外，对于本站所发表内容和资料等进行的二次使用所产生的各项问题，本站以及运营团队概不负责，敬请知悉。

## 开发人员

### 项目主创

- 数据搜集、基于 `shiny` 的可视化开发：[@Pengxz_tm](https://github.com/Pengxz-tm)  
- 作者简介：[彭贤哲](http://www.jiaobu365.com/Free/5d8aedcfa4c2c.html)  
- 灵感来源：田少华

## 功能简介

### 1. 探究数据分布情况(原始数据概况栏)
#### <1> `取样间距分布` | `原始数据交互式绘图`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/strats1.png)
#### <2> `根据时间锚定点将深度转换为时间` | `根据时间锚定点校正原始时间`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/strats2.png)

### 2. 常用周期分析预处理功能
#### `滤波` | `趋势去除与提取` | `频谱分析`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/prewhite.png)

### 3. 常用数据处理方法
#### `峰谷提取` | `归一化` | `根据x、y值分段提取数据`

### 4. 演化谱和小波分析
#### <1> `振幅演化谱` | `能量演化谱` | `特定频带能量提取`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/evolution.png)
#### <2> `小波分析` | `相干性分析` | `相位差分析`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/wavelet.png)

### 5. 调谐效果检测
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/effect.png)

### 6. 包络线提取
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/envolope.png)


### 7. 天文参数
#### <1> `天文参数` | `单日日照量` | `期间日照量` | `特定阈值日照量`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/inso1.png)
#### <2> `日照量梯度` | `日照量时空分布`
![index](https://github.com/Pengxz-tm/Astrochron-app/blob/main/inso2.png)
#### <3> `全年日照量分布`
[范例](http://www.jiaobu365.com/Free/5d8aedcfa4c2c.html)  
