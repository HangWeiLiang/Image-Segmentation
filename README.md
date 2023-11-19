# Image Segmentation Project
## Overview: 
Our project explores the efficacy of various image segmentation techniques (in particular Unet, Segnet, and DeeplabV3) in the context of autonomous driving. We use Unet as the baseline model and compare with Segnet, DeeplabV3 models. We also found another ResNet model to compare with the baseline to ensure that our approach is better, this model has been tested and presented in the conclusion section of our project summary. In the end, the Deeplabv3 model achieved the best training results, with Accuracy reaching 87%.

## File structure
UNet.ipynb：This notebook contains the implementation details of the UNet model, including its architecture, training process, and evaluation methods.

SegNet.ipynb: In this file, you can find the detailed implementation of the SegNet model, including network architecture, data processing, and performance testing.

DeepLabV3.ipynb: This file details the construction and experimental results of the DeepLabV3 model.

Project Summary.pdf: This document summarizes the overall progress of the project, including the key findings for each model and the overall discussion/conclusion of the project.

## Contact Information
Hangwei Liang z5499015@ad.unsw.edu.au

Neil Liao z5187710@ad.unsw.edu.au

Ze Chen z5449848@ad.unsw.edu.au

Jingjie Xu z5442663@ad.unsw.edu.au

Nuo Chen z5451234@ad.unsw.edu.au

## Dataset
The data set used in this project is the Indian driving data set on kaggle, which contains 5966 training data and 1016 validation data. The label image consists of 26 classes, and the pixel value 255 represents "unlabeled/out of roi" data.

Dataset Link: https://www.kaggle.com/datasets/abhishekprajapat/idd-20k/data

![image](https://github.com/HangWeiLiang/Image-Segmentation/assets/106795698/e471d697-bab0-460b-aff9-4902316a056e)
