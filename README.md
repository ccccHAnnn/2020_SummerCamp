# 2020_SummerCamp
Project of 2020 Xilinx Summer Camp


AD_DA_LPF 2020年新工科联盟-Xilinx暑期学校（Summer School）项目。

项⽬概要：

本项目实现了在FPGA内部进行的FIR低通滤波器设计，可以滤除100KHz以外的带外噪声信号。并对使用Xilinx FIR IP核与自行设计的FIR滤波器算法进行使用资源对比分析，结论是：自行设计的FIR低通滤波器算法可以利用LUT资源换取DSP资源的消耗，从而大大节省片上的DSP资源。

工具版本：Vivado 2018.3

FPGA板卡：SEA-S7
