---
title: Translator Web App 🔥
publishDate: 2023-10-15
img: /assets/langportalUI.webp
img_alt: NLP WebUI
description: |
  Easy to use translator for learning
tags:
  - AWS
  - PyTorch
  - Transformers
  - Javascript
---
### Lang Portal App: English-Spanish Translator:

Lang Portal App allows users to translate and also learn the language at the same time! It accomplishes this with a multifeature web UI.

#### Features:
- [x] English to Spanish Translation
- [x] Text-to-Speech
- [x] Speech-to-Text
- [x] Highlighted Word Definitions

By highlighting words you can see their definition in the section below the translator.

### Design and Programming with Material UI, React, and AWS Amplify:

The Lang Portal App was designed and programmed using the Material UI component library, the same library that Spotify, Google, and YouTube use to create an easy to use user interface. The website is programmed in HTML, JavaScript, and CSS using a React framework for a real time dynamic interface. We hosted the React front end application using AWS Amplify for efficient deployment and scaling.

### Cloud Architecture:

We used a series of Amazon web services starting with Amplify where our website is hosted. We then use an HTTP Post method which will send our input to the Amazon API Gateway. This will handle our Post request data and route it to our Lambda function which is static python code that is hosted inside AWS. That code will call our model via the SageMaker endpoint and it will predict what our input will be in Spanish.

### Transformer Model:
We custom trained a HuggingFace Transformer model from on a KDE4 english and spanish dateset. 

1. We start with an input that goes into our transformer and inside of the Transformer we have an encoder and a decoder. 
2. The encoder will take in the inputs, tokenize them, and send them to the decoder which will then make predictions on what it thinks the phrase should be. 

### Find out more:

Here is the link to the [WebUI](https://bluestarburst.github.io/LangPortal/)

***Note:*** The website used Amazon Web Services (aka cost money). This is a link to the UI.

A recording of the demo is available [Here](https://www.youtube.com/live/HAyAWdbnM7g?feature=share&t=10355)


### Screenshots
(https://img.youtube.com/vi/HAyAWdbnM7g/maxresdefault.jpg)
![image](https://github.com/BlueStarBurst/LangPortal/assets/78242653/6447b447-1446-453b-9896-f753da7ccb14)

| Dark Theme                                         | Light Theme                                        |
| -------------------------------------------------- | -------------------------------------------------- |
| ![App Screenshot](https://i.imgur.com/668wAGk.png) | ![App Screenshot](https://i.imgur.com/Swmw9Q6.png) |
| ![App Screenshot](https://i.imgur.com/R5vegHT.png) | ![App Screenshot](https://i.imgur.com/c12HsSL.png) |
| ![App Screenshot](https://i.imgur.com/PhdSYng.png) | ![App Screenshot](https://i.imgur.com/FRwotIL.png) |
