# XDU——Micro control project

由于我当时负责了FPGA与STM32部分，故分享这两个部分的代码，有需要的同学可以参考。

**关键字**：STM32，TCS34725，VL6180x，FPGA，stm32cubemx

 本项目是西电通院大二下学期的一门课程。曾经刚开始在使用STM32配置TCS34725颜色传感器和VL6180x距离传感器时，对于这两个传感器的驱动包的查找与编写花了很多时间，所以想直接分享出来，为需要的同学节约时间和减少经历。

### MCU代码编写方式（$KEIL$）

本人使用的基于$STM32CUBEMX$的图像化编程方式，由于使用这个需要自己找库，而且找的库可能很有问题，我当时画了很多时间找库和花时间改代码。（所以供有需要的同学，想提升对stm32了解的同学参考。

#### FPGA

FPGA部分比较简单相信大二上做过数电大作业的同学应该清楚
