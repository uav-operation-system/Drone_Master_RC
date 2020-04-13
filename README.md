# Drone_Master_RC

## Overview

This is the source code of flight control terminal for XDU Aero Association micro quadcopter.

This is the [Keil5](http://www.keil.com/) project.So you could import to Keil5 and run from source code easily.

The main control chip is stm32f1, and the wireless transfer module currently use is NRF24L01.

When modifying the code, please create a new feature branch under the master branch, modify the code under the feature branch, and then perform the pull request operation through the branch. Confirm and merge to the main branch.

For bug related and suggestions, please move to the issue column

By phillweston

## 概要说明

这是西电航协微型四轴飞行器PID版本遥控器代码

这是一个[Keil5](http://www.keil.com/)工程，直接导入到Keil5中就可以编译运行。

主控芯片为STM32F1，数传模块目前采用NRF24L01

目前该遥控器尚未制作完成，后期会考虑制作

通信方式采用的是SPI而非目前使用的蓝牙串口，后期会考虑修改为串口形式

修改代码的时候，请在master分支下面新建一个特性分支，在该特性分支下进行代码的修改然后通过该分支执行pull request操作。确认无误后再合并至主分支。

bug相关和建议请移步至issue栏目

作者：Phillweston
