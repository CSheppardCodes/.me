---
title: Fracture Diagnostics YOLOv7-8 🤖
publishDate: 2023-10-13
img: /assets/TransparentFracture.webp
img_alt: Model vs true values Xray
description: |
  Developed a custom trained object detection model with PyTorch that analyzed over 20,000 X-Ray images. Awarded 1st place by a panel of machine learning experts amongst 10 research teams.

tags:
  - Python
  - Pytorch
  - VOLOv7-8
  - Artificial Intelligence
---
### Using computer vision for X-Rays

I came up with the idea of using Computer Vision to detect X-Rays when I broke my arm and the fracture went undetected by several doctors. I wanted to research if we could incorporate AI to assist doctors make less mistakes.

As a Research Lead for ACM Research at UTD, I lead a team of 4 to develop AI-based pediatric wrist trauma diagnostics using Python.

### YOLOv7-8 📋

YOLO(You Only Look Once) is an efficient and accurate object detection algorithm that uses deep
convolutional neural networks to recognize and localize objects in an image. Unlike traditional
object detection algorithms that require multiple passes through an image, YOLO divides the
image into a grid and predicts the bounding boxes and class probabilities for each grid cell in a
single pass. We used 2 models for comparison.


1. YOLOv7 is one of the latest releases of YOLO, around 120% faster than previous
iterations held at the same accuracy.
2. YOLOv8 was released very recently, with 5 versions being available of different sizes, we use the smallest model ’yolov8n’ due to larger ones requiring
greater computational power + longer training times.


### Results 🚀

We achieved remarkable precision where
90% of fractures were identified, the rest unclassified. The model also found metal objects with great accuracy. This model often outperformed Doctors in an night ER setting where human error is increased. 

After presenting our results in the ACM Research Symposium our research project was awarded 1st place by a panel of machine learning experts amongst 10 research teams.

Here is the link to the [repository](https://github.com/CShepppardCodes)

## Screenshots 📸

<img src="https://i.imgur.com/4MkQP7d.png" alt="Results Screenshot" width="400" height="800" />
