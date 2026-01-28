# HymDrone 四旋翼无人机数据集

## 一、数据集简介

HymDrone 是一个基于工程实际应用背景构建的四旋翼无人机数据集。
本数据集基于 AirSim 仿真平台生成，面向无人机目标检测与目标跟踪等计算机视觉任务，
具有规模大、场景多样、条件复杂等特点。

数据集中系统性地整理了四旋翼无人机在不同场景、不同天气条件下采集到的高质量图像数据及其对应标注文件，
适用于无人机视觉感知相关科研与教学研究。

## 二、数据集生成方式

本数据集使用 AirSim 作为仿真平台进行数据生成，
通过构建多种复杂环境与飞行条件，模拟真实工程应用中的无人机场景。

数据集共生成 55 个视频序列，包含 59,138 张高质量图像，
所有图像分辨率均为 1920 × 1080，并为每一张图像提供了精确的无人机目标边界框标注。

## 三、场景与天气设置

### （一）场景类型（共 9 类）

数据集包含以下九种典型场景：

- Park
- ![Park](images/图片1.jpg)
- Nighttime
- ![Nighttime](images/图片2.jpg)
- Hilly areas with trees
- ![Hilly areas with trees](images/图片3.jpg)
- Terrain with trees
- ![Terrain with trees](images/图片4.jpg)
- Beach
- ![Beach](images/图片5.jpg)
- Jungle
- ![Jungle](images/图片6.jpg)
- Mountains
- ![Mountains](images/图片7.jpg)
- Highways
- ![Highways](images/图片8.jpg)
- Sunset
- ![Sunset](images/图片9.jpg)

上述场景均具有复杂背景结构与不同程度的遮挡情况，
有效提升了数据集的多样性与挑战性。

### （二）天气条件（共 5 类）

在同一场景条件下，数据集进一步引入了五种不同天气情况：

- Sunny
- ![Sunny](images/图片10.jpg)
- Fog
- ![Fog](images/图片11.jpg)
- Haze
- ![Haze](images/图片12.jpg)
- Falling leaves
- ![Falling leaves](images/图片13.jpg)
- Heavy rain / snow
- ![Heavy rain / snow](images/图片14.jpg)

通过场景与天气条件的组合，显著增强了数据集的泛化能力。

## 四、数据用途

本数据集可用于以下研究方向：

- 无人机目标检测
- 无人机目标跟踪
- 复杂环境下的无人机视觉感知研究
- 仿真数据到真实场景的泛化分析

## 五、版权与使用说明

本数据集仅供学术研究与教学使用，禁止用于任何商业用途。
如在论文、报告或项目中使用本数据集，请注明数据来源。
