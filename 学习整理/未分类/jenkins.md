# 1 概述

>  [中文官网](https://www.jenkins.io/zh/doc/) 

## 1.1 jenkins是什么

Jenkins是一个开源CI&CD软件，用于自动化任务，包括构建、测试、部署。支持各种运行方式，包括系统包、Docker或独立Java程序



## 1.2 CI/CD是什么

- CI（Continuous Integration，持续集成）：一种软件开发实践，强调提交新代码后，立即进行构建、（单元）测试。根据测试结果来判断新旧分支是否可以正确集成在一起

   ![img](https://upload-images.jianshu.io/upload_images/6464255-1b6e3bfdbece1492.jpg?imageMogr2/auto-orient/strip|imageView2/2/format/webp) 

- CD（Continuous Delivery，持续交付）：在持续集成的基础上，将集成后的代码部署到更贴近真实运行环境（类生产环境）中。

   ![img](https://upload-images.jianshu.io/upload_images/6464255-ba088ec7257062c0.jpg?imageMogr2/auto-orient/strip|imageView2/2/format/webp)  



# 2 前期准备

## 2.1 安装

1. 资源—— [jenkins 安装包下载地址](https://get.jenkins.io/war-stable/2.164.3/) 
2. 教程—— [黑马程序员Java教程自动化部署Jenkins从环境配置到项目开发](https://www.bilibili.com/video/BV1kJ411p7mV?p=13&vd_source=098a4a1f82f9710093952a6c9d3002e2) 


## 2.2 安装插件



# 3 遇到的问题
安装和使用需要open jdk 11，而本机使用的是oracle jdk 1.8，无法安装