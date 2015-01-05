FastColonyCounting 
==================

A simple Software running on Matlab 7.0 GUI environment to automatic count  colony number in Image. Use Matlab library and algorithm to realize almost all the function of this software. Only one image can be deal onece now.<br />
一个在Matlab 7.0 下编写的GUI应用软件，用来自动统计图片中的菌落个数。几乎所有功能实现都是基于Matlab本身的库。目前只支持一次处理一张图片。

项目说明
------------------
测试图片在[fastcolonycounting/fig0.jpg](fastcolonycounting/fig0.jpg)<br /> 
![fig0.jpg](fastcolonycounting/fig0.jpg)<br /> 

项目截图
------------------
### 项目主页
![im_1.jpg](fastcolonycounting/im_01_main.png)<br />
### 打开待处理的图片
![im_2.jpg](fastcolonycounting/im_02_open.png)<br /> 

### 边缘检测
![im_3.jpg](fastcolonycounting/im_03_edge.png)<br /> 
### 自动补洞
![im_4.jpg](fastcolonycounting/im_04_fillhole.png)<br /> 
### 腐蚀图像
![im_5.jpg](fastcolonycounting/im_05_corrosion.png)<br /> 
### 膨胀图像
![im_6.jpg](fastcolonycounting/im_06_expand.png)<br /> 
### 分割图像
![im_7.jpg](fastcolonycounting/im_07_split.png)<br /> 
### 保存图像
![im_8.jpg](fastcolonycounting/im_08_save.png)<br /> 
### 一键处理数据
* 注意
    需要首先打开图像才能进行处理！
![im_9.jpg](fastcolonycounting/im_09_onekey.png)<br /> 
### 手动选择菌斑进行处理
* 处理方法为：
    鼠标左键选择需要统计的菌斑，可以多选。
    双击鼠标则选择结束。
![im_10.jpg](fastcolonycounting/im_10_sigle_area.png)<br /> 


License
-------
 Copyright 2015 csulennon

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
