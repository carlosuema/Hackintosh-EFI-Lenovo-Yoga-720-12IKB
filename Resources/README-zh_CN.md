# Hackintosh-EFI-Lenovo-Yoga-720-12IKB

[![Release](https://img.shields.io/github/release/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB.svg)](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/releases)
[![Progress](https://img.shields.io/badge/Progress-Developing-ff69b4.svg)](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/README.md)
[![License](https://img.shields.io/badge/License-GPLv3-lightgrey.svg)](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/LICENSE)

一个 **联想 Yoga 720-12IKB** 的初始 EFI

[ENGLISH](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/tree/master/README.md) | **简体中文**

本 EFI 适用于 [联想 Yoga 720-12IKB](https://www.lenovo.com/us/en/laptops/yoga/700-series/Yoga-720-12/p/88YG7000919)

支持 macOS 10.14.6(18G84) 或更高

## 关于维护本 EFI 的维护

这不是我日常使用的笔记本电脑，我很少使用。制作设个 EFI 纯属假期娱乐。但我之后应该不会有足够的时间来维持。我期待有拥有相同的笔记本电脑并拥有黑苹果技术的人来接管这个 EFI 并继续维护。如果你觉得就是你自己了，那么请打开一个 Issue 并发封邮件给我。

## 已知问题

> 这台黑苹果我只折腾了几天，距离完美还有很长的路要走。

请访问[这里](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/issues/1)来获得更多详细信息

## 实用资源

请访问 [Resources 文件夹](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources)

## 笔记本配置

| 规格   | 详细信息                              |
| ----- | ------------------------------------ |
| 型号   | Lenovo Yoga 720-12IKB                |
| 处理器 | Intel(R) Core(TM) i7 7500U @ 2.70GHz |
| 内存   | 8 GB  2133 MHz 单通道                 |
| 硬盘   | LITEON CV3-8D128 (SATA) 128GB        |
| 显卡   | Intel HD Graphics 620                |
| 声卡   | Conexant CX20751 (LayoutID 21)       |
| 触摸板 | ELAN 0602                            |
| 触摸屏 | Wacom WCOM5126                       |

## 可用的功能

- [x] Intel HD630（亮度可调，重启亮度记忆）
- [x] USB 3.1 Gen 1
- [x] 摄像头
- [x] 电量显示
- [x] 睡眠及唤醒
- [x] 传感器
- [x] 声卡
- [x] HIDPI
- [x] CPU 变频
- [x] 触摸板
- [x] 触摸屏
- [x] Fn + F6 禁用触摸板
- [x] Siri
- [x] 蓝牙
- [x] 原生 NVRAM

## 不可用的功能

- 部分 Fn 键
- 指纹
- 高通 Atheros QCA6174 无线网卡

## 特别感谢

- [Daliansky](https://github.com/daliansky) 的安装 dmg，config 文件和博客上的精彩文章
- [Headkaze](https://github.com/headkaze) 的实用工具 Hackintool
- 联想小新 QQ 群的群友对联想机型特征的指导
- 宪武 在 ACPI 方面的指导

## Credits

- [Acidanthera](https://github.com/acidanthera)
  - [AppleALC](https://github.com/acidanthera/AppleALC)
  - [Lilu](https://github.com/acidanthera/Lilu)
  - [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
  - [VoodooPS2](https://github.com/acidanthera/VoodooPS2)
  - [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [Clover Developer Team](https://sourceforge.net/projects/cloverefiboot)
- [RehabMan](https://github.com/RehabMan)
  - [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet)
- [VoodooI2C Developer Team](https://voodooi2c.github.io/#Credits%20and%20Acknowledgments/Credits%20and%20Acknowledgments)
  - [VoodooI2C](https://github.com/alexandred/VoodooI2C)
  - [VoodooI2CHID](https://github.com/alexandred/VoodooI2C)

## 图库

![Yoga720](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources/img/Yoga720.png)

![About This Mac](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources/img/AboutThisMac.png)

![HIDPI](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources/img/HIDPI.png)

![I2C](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources/img/I2C.png)

![Siri](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/blob/master/Resources/img/Siri.png)
