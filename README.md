# Advance Computer Vision with Python

本仓库代码基于 [Advance Computer Vision with Python](https://www.computervision.zone/courses/advance-computer-vision-with-python/) 进行修改，更加适合中国宝宝体质

本仓库计划用于2024成都理工大学人工智能协会技术培训使用

## 项目依赖

- OpenCV: `4.10.0`
- MediaPipe: `0.10.10`

## Conda创建环境流程

```bash
conda create -n visionpy python=3.8
conda activate visionpy
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
pip install opencv-python==4.10.0
pip install mediapipe==0.10.10
```