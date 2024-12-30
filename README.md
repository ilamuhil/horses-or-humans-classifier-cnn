 # Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) that classifies images into two categories: **Horses** and **Humans**. The model is designed to accurately identify and differentiate between these two classes based on the images provided in the training and test datasets.

## Project Overview

This project utilizes a CNN architecture to classify images. The model is trained on a dataset of images, which is organized into two main categories. The notebook includes 2 models. 1st is a custom nueral network . The 2nd is a network built on top of Googles image classifier Inception V3 model.

## Dataset

The dataset used for training the model can be found at the following link:

-  [Download Dataset](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/rps.zip)

### Directory Structure

After extracting the dataset, it should follow this directory structure:
```
project_root/
│
├── train_images/
│   ├── horses/
│   │   ├── image1.png
│   │   ├── image2.jpeg
│   │   └── ...
│   └── humans/
│       ├── image1.png
│       ├── image2.jpeg
│       └── ...
│
└── test_images/
├── horse/
│   ├── image1.png
│   ├── image2.jpeg
│   └── ...
└── human/
├── image1.png
├── image2.jpeg
└── ...
```
