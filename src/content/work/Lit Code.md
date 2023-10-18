---
title: Translator Web App 🔥🌍
publishDate: 2023-10-15
img: /assets/LangportalMockup.webp
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

Lang Portal App allows users to translate and learn the language at the same time! It accomplishes this with a multi-feature web UI.

#### Features:
- [x] English to Spanish Translation
- [x] Text-to-Speech
- [x] Speech-to-Text
- [x] Highlighted Word Definitions

### Design and Programming with Material UI, React, and AWS Amplify:

The Lang Portal App was designed and programmed using the Material UI component library, the same library that Spotify, Google, and YouTube use to create an easy-to-use user interface. The website is programmed in HTML, JavaScript, and CSS using a React framework for a real-time dynamic interface. We hosted the React front-end application using AWS Amplify for efficient deployment and scaling.

### Cloud Architecture:

We used a series of Amazon web services starting with Amplify where our website is hosted. We then use an HTTP Post method which will send our input to the Amazon API Gateway. This will handle our post-request data and route it to our Lambda function which is staticPythonn code that is hosted inside AWS. That code will call our model via the SageMaker endpoint and it will predict what our input will be in Spanish.

### Transformer Model:
We custom-trained a HuggingFace Transformer model from a KDE4 English and Spanish dataset.

1. We start with an input that goes into our transformer and inside of the Transformer we have an encoder and a decoder. 
2. The encoder will take in the inputs, tokenize them, and send them to the decoder which will then make predictions on what it thinks the phrase should be. 

### Find out more:

1. Link to our custom [Model](https://huggingface.co/zainnaved/marian-finetuned-kde4-en-to-es) hosted on HuggingFace.com

2. Link to [Demo](https://www.youtube.com/live/HAyAWdbnM7g?si=lzKCAhY4GJ7BqgQJ&t=10296) presentation

3. Link to the [WebUI](https://bluestarburst.github.io/LangPortal/)

4. Link to the [GitHub](https://github.com/BlueStarBurst/LangPortal)

***Note:*** Website's functionality is inactive due to the cost associated with using Amazon Web Services.

### Screenshots
![image](https://github.com/BlueStarBurst/LangPortal/assets/78242653/6447b447-1446-453b-9896-f753da7ccb14)