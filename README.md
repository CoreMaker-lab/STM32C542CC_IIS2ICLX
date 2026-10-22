# STM32C542CC_IIS2ICLX



# Overview
- **Name**: IIS2ICLX-V1.0
- **MCU**: STM32C542CCT6
- **IDE**: STM32CUBEMX2+STM32CUBEIDE


# Buy Link
[https://shop192352884.taobao.com/](https://shop192352884.taobao.com/)


# Contact Information

- **Name**: Billy
- **交流群**: 925643491
- **Email**: a845656974@outlook.com
- **Phone**: +86 15622736378
- **CSDN Blog**: [Blog](https://blog.csdn.net/qq_24312945)
- **Video**: [Video](https://space.bilibili.com/26152390)



# Project Introduction
- **STM32C5_IIS2ICLX_Project1**:STM32C5开发IIS2ICLX(1)----SPI获取加速度计数据
- **CSDN Blog**:[https://blog.csdn.net/qq_24312945/article/details/166257152](https://blog.csdn.net/qq_24312945/article/details/166257152)

IIS2ICLX是一款采用数字输出的高精度（超低噪声、高度稳定性和可靠性）型低功耗2轴线性加速度计。
IIS2ICLX的可选满量程为±0.5/±1/±2/±3 g，它能够通过I²C或SPI数字接口为应用提供测得的加速度。
IIS2ICLX能够在极端温度和重复使用环境下保持高精度和可靠性，特别适合倾角测量应用（测斜仪）。
传感单元使用意法半导体开发的专用微加工工艺进行制造，在硅片上生产惯性传感器和执行器。
IC接口使用CMOS工艺进行制造，可实现高度集成，从而设计出更加匹配传感单元特性的专用电路。
IIS2ICLX内嵌一组独特的功能（可编程FSM、机器学习 内核、传感器集线器、FIFO、事件解码和中断)，这是实现智能和复杂传感器节点的使能器，以非常低的功耗提供高精度和高性能。
IIS2ICLX采用高性能（低应力）陶瓷腔焊盘栅格阵列(CC LGA)封装，可在-40°C至+ +105 °C的温度范围内工作。

The IIS2ICLX is a high-precision, low-power, two-axis linear accelerometer with digital output, featuring ultralow noise, high stability, and excellent reliability.

The IIS2ICLX offers selectable full-scale ranges of ±0.5/±1/±2/±3 g and provides measured acceleration data through an I²C or SPI digital interface.

The device maintains high accuracy and reliability under extreme temperatures and repeated use, making it particularly well suited to inclination measurement applications (inclinometers).

The sensing element is manufactured using a proprietary micromachining process developed by STMicroelectronics to produce inertial sensors and actuators on silicon wafers.

The interface IC is manufactured using a CMOS process, enabling a high level of integration and the implementation of dedicated circuits tailored to the characteristics of the sensing element.

The IIS2ICLX integrates a unique set of features, including a programmable finite state machine (FSM), a machine learning core, a sensor hub, a FIFO buffer, event decoding, and interrupts. These features enable intelligent, sophisticated sensor nodes that deliver high accuracy and performance with very low power consumption.

The IIS2ICLX is available in a high-performance, low-stress ceramic cavity land grid array (CC LGA) package and operates over a temperature range of −40°C to +105°C.


- **STM32C5_IIS2ICLX_Project2**:STM32C5开发IIS2ICLX(2)----IIC获取震动计数据
- **CSDN Blog**:[https://blog.csdn.net/qq_24312945/article/details/166257298](https://blog.csdn.net/qq_24312945/article/details/166257298)

IIS2ICLX 是意法半导体推出的一款高精度 、低功耗双轴数字加速度传感器，特别适用于倾角测量。该器件具有低噪声、良好的温度稳定性和重复性，支持 ±0.5/±1/±2/±3 g 可选量程，并提供 IIC（I²C）和 SPI 数字通信接口，可应用于设备调平、结构健康监测及工业自动化等领域。
本章介绍如何通过 IIC 接口驱动 IIS2ICLX，实现器件识别、初始化 配置以及 X、Y 两轴加速度和温度数据的读取。程序通过轮询数据就绪标志获取原始数据，完成单位换算后通过串口输出，为后续的倾角计算、零偏校准和滤波处理奠定基础。
The IIS2ICLX is a high-precision, low-power, dual-axis digital accelerometer from STMicroelectronics, particularly well suited to inclination measurement. It features low noise, good temperature stability, and repeatability, with selectable full-scale ranges of ±0.5/±1/±2/±3 g. It supports I²C and SPI digital communication interfaces and can be used in applications such as equipment leveling, structural health monitoring, and industrial automation.

This chapter describes how to interface with the IIS2ICLX via I²C, covering device identification, initialization and configuration, and the acquisition of X- and Y-axis acceleration and temperature data. The program polls the data-ready flags to retrieve raw measurements, converts them into physical units, and outputs the results through a serial port, providing a foundation for subsequent inclination calculations, zero-offset calibration, and filtering.

# Image

<img width="1280" height="1814" alt="image" src="https://github.com/user-attachments/assets/87c97c9f-d723-4609-b3c9-11c1be7ffe52" />

<img width="1280" height="1799" alt="image" src="https://github.com/user-attachments/assets/03c9cfa7-0f98-4240-bee7-8cd88cdf56dd" />

<img width="1274" height="1804" alt="image" src="https://github.com/user-attachments/assets/fc12a9ee-9b78-490a-9e38-611ec03663cd" />

<img width="1268" height="1806" alt="image" src="https://github.com/user-attachments/assets/adf60d7c-8199-4032-bdfd-1dcea58e4959" />

<img width="1280" height="1805" alt="image" src="https://github.com/user-attachments/assets/b0e291dd-f8d2-453b-836d-ec723e5a5281" />





