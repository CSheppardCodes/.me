---
title: Emotion Detection 🍩
publishDate: 2023-10-17
img: /assets/MockupEmotion7.webp
img_alt: Emotion Detection UI
description: |
    Developed a Real time Emotion Detection Web App using Convolutional Neural Networks
tags:
  - AWS Sagemaker
  - ReactJS
  - TensorFlow
  - JavaScript
---

### Purpose of the Emotion Detection

Analyzing the emotions of crowds with thousands of people is close to impossible because of the sheer amount of people. The purpose of this project is to train a model that will be able to tackle this problem. This project could be extremely useful during a Zoom call to track engagement, concerts, and events to track fan enjoyment and much more.

### Data

We got our data from the "Face expression recognition dataset" on Kaggle. This dataset contains 35,900 different images classified into 7 different emotions [Happy, Sad, Angry, Neutral, Suprise, Disgust, Fear].

### Hyper Parameter Tuning

We chose to use the Keras-Tuner Python Library to tune our hyperparameters.
The main parameters that we chose to tune are:
* Dropouts percents
* Number of Filters of the third and fourth Conv2d Layer 
* Number of Units on all the Dense Layers


### Accuracy

The accuracy of our model came out to total accuracy ***65%*** which is impressive compared to humans who can correctly assess emotion ***72%*** of the time.

### Screenshots

In progress
