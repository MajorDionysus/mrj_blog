---
title: ECG signal acquisition and processing
published: 2024-10-12
description: dasd

image: https://img.mrj.today/images/blogs/2024ECGLab/cover.jpg
tags:
  - Healthcare
  - ECG
category: CourseProject
draft: false
---

### 前言
心电图（Electrocardiogram，ECG）是检测心脏电活动的重要医疗工具。心脏的每次跳动都伴随着有规律的电信号传导，这些电信号在人体表面产生微弱的电位变化。心电图仪通过放置在人体不同部位的电极捕捉这些细微的电位波动，并将其转化为可视图形。

心电图的波形包含丰富的信息。例如，P 波代表心房的去极化过程，反映心房的电活动；QRS 波群对应心室的去极化，其形状、时限等特征可以表明心室是否存在异常；T 波与心室的复极化有关。通过仔细分析心电图的每个波段、间期和波形形状，医生可以诊断多种心脏疾病，如心律失常、心肌缺血、心肌梗死等。在临床实践中，无论是日常健康检查还是心脏病患者的诊断、治疗效果评估和病情监测，心电图都发挥着不可替代的关键作用，为保护人类心脏健康提供了至关重要的依据。

在南方科技大学智能医学工程专业（SUSTech IME）的BMEB328课程模块二的课程中，我们采用了National Instruments公司的USB - 6009数据采集模块进行生物电信号的采集工作。借助MATLAB软件平台，对所采集的信号实施处理与分析操作，并基于MATLAB的图形用户界面（GUI）开发功能，构建了用于控制信号采集流程、实时显示测量结果的交互式操作界面。该系统具备心电图测量、心电图绘制以及心跳速度计算等功能。当检测到心跳频率超出正常范围（过快或过慢）时，软件会自动触发警报机制。测量流程结束后，系统将按照特定的数据结构格式，将测量结果导出为数据文件。此数据文件格式经专门设计，与后续开发的专家数据共享网页完全兼容，旨在为医疗专家提供便捷的数据访问途径，使其能够通过网络远程实时掌握病人的身体状况，进而为远程医疗诊断等应用场景提供有力的数据支持 。 

### 设计
![](https://img.mrj.today/images/blogs/2024ECGLab/Workflow.png)

### 结果

![](https://img.mrj.today/images/blogs/2024ECGLab/Integrated.png)


[查看课程实验报告](https://img.mrj.today/images/blogs/2024ECGLab/report.pdf)