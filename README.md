# Image classification: Classify food image using TensorFlow
### Table of Contents 
1. [Project Motivation](#Project-Motivation)
2. [Description](#Description)
3. [Installation](#Installation)
4. [Libraries](#Libraries)
5. [File Descriptions](#File-Descriptions)
6. [Result](#Result)
7. [Resources](#Resources)

## Project Motivation
To Learn TensorFlow image classification

## Description
Classify image dataset from kaggle food101 by Tensorflow 

## Installation

The Tensorflow need to be installed.

```conda install -c conda-forge tensorflow```

The pillow library need to be installed to read image files correctly.

```conda install -c conda-forge pillow``` 

And the project code should run with no issues using Anaconda versions 4.9.x, python versions 3.x., seaborn versions 0.11.x and numpy <= 1.19 </br>

The food101 dataset are not in the github repository becaue of the large file size. So you need to download from here:
https://www.kaggle.com/kmader/food41?select=images </br>
After downloaded the food101 dataset, put it in the folder food101: </br>

Only 10 food classes are classify due to computation time so the image directories should only have 10 classs in alphabet order </br>
- Copy 10 class directories to sub_images directory

## Libraries
* numpy
* matplotlib
* os
* pathlib
* PIL
* seaborn
* keras_tuner
* tensorflow

## File Description
```food101/```: The folder that contains entire image dataset including meta data. <br/>
```food101/subimages```: The folder that contains sub_images for classification. <br/>
```food101/meta/```: The folder that contains image meta data. <br/>
```food101/meta/sub_classes.txt```: the sub_classes name data. <br/>
```readme.md```: README file. <br/>
```Food image classification.ipynb```: The jupyter notebook file where the code and visualization are presented. <br/>

## Result

The project predicts food image at around 60.0% and can be increased by adding additional epochs <br/>

## Resource
* Food Images (Food-101) dataset <br/>
https://www.kaggle.com/kmader/food41?select=images
