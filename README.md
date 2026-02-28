# 恶劣天气下的 3D 目标检测论文

## （综述1）论文题目：Object Detection in Autonomous Vehicles under Adverse Weather: A Review of Traditional and Deep Learning Approaches1
--------
### 发表日期：2024年2月26日
### 发表期刊/会议：《Algorithms》
### DOI
### 作者团队/机构：
### 开源代码链接：

### 针对什么问题：
### 以前怎么做的：
### 本文解决方法：
### 实验（对比试验和消融实验）：
### 对我写恶劣天气下的3D目标检测论文有什么用：



## （）论文题目：Benchmarking and Improving Bird’s Eye View Perception Robustness in Autonomous Driving
--------
### 发表日期：2025年5月
### 发表期刊/会议：《IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE》（IEEE TPAMI）
### DOI10.1109/TPAMI.2025.3535960
### 作者团队/机构：
### 开源代码链接：https://github.com/Daniel-xsy/RoboBEV

### 针对什么问题：
现有的 BEV 模型在“干净”的标准数据集（如 nuScenes）上对于4大感知任务：3D目标检测、地图分割、深度估计、语义占用预测表现极好。但在现实世界中，遇见以下八种特殊情况，如何评估模型对于4大感知任务的鲁棒性：
| 类型               | 情况描述                          | 英文描述                     |
|--------------------|-----------------------------------|-----------------------------|
| 外部环境           | 亮度过高、过暗、雾、雪            | Bright, Dark, Fog, Snow     |
| 内部传感器故障     | 运动模糊、色彩量化/压缩失真        | Motion Blur, Color Quant    |
| 时间连续性故障（首创） | 相机死机（持续几帧丢失）、丢帧    | Camera Crash, Frame Lost    |
### 以前怎么做的：
### 本文解决方法：
0.Abstract
1.INTRODUCTION
2.RELATED WORKS
    2.1   基于相机的BEV感知
    2.2   基于LiDAR的3D感知

3.BEV PERCEPTION PRELIMINARIES
4.BENCHMARK DESIGN
5.BENCHMARK EXPERIMENTS
6.ANALYSIS AND DISCUSSION
7.CONCLUSION
### 实验（对比试验和消融实验）：

### 对我写恶劣天气下的3D目标检测论文有什么用：

