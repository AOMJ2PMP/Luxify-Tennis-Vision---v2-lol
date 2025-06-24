# Luxify Tennis Vision

## Introduction

本项目通过分析视频中的网球运动员来测量他们的移动速度、击球速度和击球次数。项目使用 YOLO 检测球员和网球，并利用 CNN 提取球场关键点。

## Models

- YOLO v8 用于球员检测
- 微调后的 YOLO 用于网球检测
- 球场关键点提取模型

- 训练好的 YOLOV5 模型：https://pan.baidu.com/s/1iQmQxIo09jwOiTbjS0CVTQ?pwd=6v6j
- 训练好的网球场关键点模型：https://pan.baidu.com/s/1ZwgkRNasZk_vKoRYXei7HA?pwd=nagy

## Training

- 使用 YOLO 的网球检测器：training/tennis_ball_detector_training.ipynb
- 使用 PyTorch 的网球场关键点：training/tennis_court_keypoints_training.ipynb

## Dependencies

- python3.8
- ultralytics
- pytorch
- pandas
- numpy
- opencv