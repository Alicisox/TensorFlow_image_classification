# Image classification: Classify image using TensorFlow
### Table of Contents 
1. [Project Motivation](#Project-Motivation)
2. [Description](#Description)
3. [Installation](#Installation)
4. [Libraries](#Libraries)
5. [File Descriptions](#File-Descriptions)
6. [Result](#Result)

## Project Motivation
To Learn TensorFlow image classification

## Description
Classify image dataset from kaggle food101 by Tensorflow 

## Installation

The Tensorflow need to be installed.

```conda install -c conda-forge tensorflow```

The pillow library need to be installed to read image files correctly.

```conda install -c conda-forge pillow``` 

And the project code should run with no issues using Anaconda versions 4.9.x, python versions 3.x., seaborn versions 0.11.x and numpy <= 1.19</br>

## Libraries
* numpy
* matplotlib
* os
* pathlib
* PIL
* seaborn
* keras_tuner
* tensorflow

## File Descriptions
```food101/```: The folder that contains entire image dataset. <br/>
```food101/subimages```: The folder that contains sub_images for classification. <br/>
```readme.md```: README file. <br/>
```Food image classification.ipynb```: The jupyter notebook file where the code and visualization are presented. <br/>

## Result

The project can prediction food image at around 60.0% and can be increased by adding more additional epochs <br/>
