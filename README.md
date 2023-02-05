# openmmalb-task
flower_datasets
第一次作业 基础作业

数据读入：

先要将数据按照8：2划分，数据划分程序：https://blog.csdn.net/qq_42076902/article/details/123915154

然后再根据文件夹生成数据标注文件  .text  数据标注程序：https://blog.csdn.net/imwaters/article/details/128726655

将标注程序main.py的变量val_percent改成1，分别对已经分类好的train和test标注即可

模型精度 2023-02-05 01:11:50,321 - mmcls - INFO - Epoch(val) [30][18]	accuracy_top-1: 95.4225

一开始学习率设太高了，直接卡在60%上下浮动，后来缩小到0.001-0.0001就正常多了
