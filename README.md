# LeafCheck

This repository contains the implementation of a Convolutional Neural Network (CNN) model for the prediction of diseases in potato leaves. The project aims to assist farmers and agricultural specialists by facilitating early and accurate disease detection through image analysis, contributing to healthier crops and optimized yields.

## Project Overview

Potato leaf diseases, such as late blight and early blight, can significantly affect crop yield if not detected and treated early. Traditional detection methods require manual inspection and expertise, which can be time-consuming and less accurate. This project employs CNN, a class of deep neural networks, renowned for their efficacy in image recognition tasks, to automate and improve the accuracy of disease detection in potato leaves.

## Dataset

The dataset comprises images of potato leaves categorized into healthy, late blight, and early blight. This project uses [PlantVillage Dataset](https://www.plantvillage.org/), which is publicly available and contains a wide range of agricultural images.

## Model Architecture

The CNN model built for this project consists of convolutional layers, pooling layers, and fully connected layers. It is trained to recognize patterns and features in the leaf images that are indicative of specific diseases.


## Installation

Ensure you have Python 3.6+ installed on your machine. Clone this repository, navigate to the project directory, and install the required dependencies:

```bash
git clone https://github.com/taexj/LeafCheck
cd LeafCheck
pip install -r requirements.txt
```

## Future Work
Currently, this app supports only English language. I am working to integrate the Urdu language to cater to the needs of local farmers in Pakistan. 
