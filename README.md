<h1 align="center">Object-Detection-With-Tensorflow-Using-VGG16</h1>

<p align="center">
  <img width="460" height="300" src="https://github.com/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16/blob/main/Image/Detect_image.png">
</p>


[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=for-the-badge&logo=appveyor)](#)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[![GitHub Forks](https://img.shields.io/github/forks/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16/fork)
[![GitHub Issues](https://img.shields.io/github/issues/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16.svg?style=flat&label=Issues&maxAge=2592000)](https://github.com/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16/issues)
# VGG16 Architecture
The input to the Convolutional Network is a fixed-size 224 X 224 X 3 image. The preprocessing step subtracts the mean RGB value from each pixel. The image is passed
through a stack of convolutional layers with 3 X 3 receptive fields (smallest size that
accommodates a pixel shift). In one of the layers, a 1 X 1 convolutional filter linearly
transforms the input channels. The stride is fixed to 1 pixel and padding is such that the
spatial resolution is preserved after convolution. 5 max-pooling layers are performed over
a 2 X 2 pixel window, with stride 2. I have used the pre-trained weights for VGG16 trained
model on ImageNet dataset to extract features. The feature for each image is a tensor of 7
X 7 X 512 dimension. Fig 1 represents the architecture of the convolutional layers in
VGG16.
# Description
Object detection in one of the fundamental problems in the field of artificial intelligence
with applications in robotics, automation, and human-computer interaction. The aim is to
track an arbitrary object in consecutive frames of a video segment by localizing it inside
bounding boxes. The most common representation of these bounding boxes is in terms of
the top-left and bottom-right coordinates in the frame with respect to the origin of each
imaginary image grid.
The VGG16 model secured the first position in ILSRVC for object localization and its accuracy
for predicting the location of these boxes is unquestionably high Nevertheless, tradeoffs between accuracy 
and computation-intensity is obvious and raises the need for faster
approaches. In this project, the VGG16 model has been trained on pre-trained weights on
ImageNet for feature extraction. This transfer learning model is advantageous as it escapes
the necessity to train the model on a large-scale dataset like ImageNet
# Run it now
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15tA57gXnWprZjc5J_V7591AUdSQWrTF6?usp=sharing)

# Dataset
https://drive.google.com/drive/folders/1NxnVWN-aJuHdTibSOPstzZcFiIHEgx6Y?usp=sharing

# Requirements

Type below command in cmd to get up and running with the dependencies of the file.
```
pip install -r requirement.txt
```
 git clone https://github.com/zubairsamo/Object-Detection-With-Tensorflow-Using-VGG16
.git

# Usage
Object-Detection-With-Tensorflow-Using-VGG16
.ipynb

## Author
You can get in touch with me on my LinkedIn Profile:

#### Zubair Samo
[![LinkedIn Link](https://img.shields.io/badge/Connect-ZubairSamo-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://linkedin.com/in/zubair-samo-3a2764197)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-zubairsamo-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/zubairsamo)

If you liked the repo then kindly support it by giving it a star ⭐!

## Contributions Welcome
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)

If you find any bug in the code or have any improvements in mind then feel free to generate a pull request.

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2020 Zubair Samo
