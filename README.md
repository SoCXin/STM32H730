# [Cortex](https://github.com/mcuyun/Cortex) 

包括Cortex M和Cortex A主流处理器

[![sites](mcuyun/mcuyun.png)](http://www.mcuyun.com)

#### 更多MCU：[mcuyun](https://github.com/mcuyun/whyme)可访问 www.mcuyun.com

--- 

## 简介 Cortex M


MCU（微控制器处理器）通常设计成面积很小和能效比很高，这些处理器的流水线很短，最高时钟频率很低（但也有此类的处理器时钟频率可以运行在200Mhz之上）。 

Cortex-M处理器家族更多的集中在低性能端，但是这些处理器相比于许多微控制器使用的传统处理器性能仍然很强大。

例如Cortex-M4和Cortex-M7处理器应用在许多高性能的微控制器产品中，最大的时钟频率可以达到400Mhz。

并且，新的Cortex-M处理器家族设计的非常容易使用。

### Cortex-M0/M0+/M1

### Cortex-M3

### Cortex-M4

### Cortex-M7

### Cortex-M23

### Cortex-M33

--- 

## 特性

- 所有的Crotex-M处理器都支持R0到R15，PSR, CONTROL 和 PRIMASK

- 两个特殊的寄存器— FAULTMASK 和 BASEPRI—只有Cortex-M3, Cortex-M4, Cortex-M7 和 Cortex-M33支持

- 浮点寄存器组和FPSCR（浮点状态和控制寄存器）寄存器，是Cortex-M4/M7/M33可选的浮点运算单元使用的

- 所有的Cortex-M 处理器都支持Thumb指令集，已扩展到同时支持16位和32位指令Thumb-2版本

- 内置的嵌套向量中断控制负责中断处理，自动处理中断优先级，中断屏蔽，中断嵌套和系统异常处理

- 中断处理函数可以使用标准的C语言编程，嵌套中断处理机制避免了使用软件判断哪一个中断需要响应处理。同时，中断响应速度是确定性的，低延迟的

- 向量表从跳转指令变为中断和系统异常处理函数的起始地址


#### 低功耗是Cortex-M处理器的一个关键优点

- WFI和WFE指令

- 架构级的休眠模式定义

- 休眠和深度休眠模式：架构级支持的特性，通过设备特定的功耗管理寄存器可以进一步扩展。

- Sleep-on-exit模式：中断驱动的应用的低功耗技术。开启设置后，当异常处理程序结束并且没有其他等待处理的异常中断时，处理器自动进入到休眠模式。

- 唤醒中断控制器（WIC）:一个可选的特性，在特定的低功耗状态，由一个独立于处理器的小模块侦测中断情况。例如，在状态保留功耗管理（SRPG）设计中，当处理器被关电的设计。

- 时钟关闭和架构级时钟关闭：通过关闭处理器的寄存器或者子模块的时钟输入来省电


---

## STM32F0

https://github.com/mcuyun/STM32F0.git

## STM32F1

https://github.com/mcuyun/STM32F1.git

## GD32

https://github.com/mcuyun/GD32.git


---

###  www.mcuyun.com   |    qitas@qitas.cn
