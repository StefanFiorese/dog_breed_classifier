# A dog breed classifier based on convolutional neural networks

## About this project

![alt text](https://github.com/StefanFiorese/dog_breed_classifier/blob/master/images_for_post/cnn.jpg?raw=true)

This project focuses on classifying 133 dog breeds using convolutional neural networks. One fully custom CNN will be trained and its performance compared to a transfer learning approach. VGG-16 will be used as the base model for transfer learning.  
Moreover, a face detection algorithm based on openCV will identify human faces.

## Goal

The goal is to develop a complete pipeline that takes in images to be calssified. If a human face is discovered, the image will also be put through the dog breed classifier. The most resembling dog breed will be returned. If a dog is identified, the dog breed will be retured. If neither a human nor a dog is detected, an error message will be returned.

## Data

All data was provided by udacity. Please refer to this repository for all contents:  
[https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

## Libraries used

General/  data processing:  

- numpy
- pandas
- time
- pickle

Visualization:

- matplotlib
- PIL
- torchsummary
- tqdm

Face recognition:

- openCV

Neural networks and image processing:

- pytorch



## Results

- A 25% accuracy on the custom CNN could be achieved (with a 0.75% baseline)
- A 87% accuracy could be achieved using transfer learning

![Performance of 4 layer custom CNN](https://github.com/StefanFiorese/dog_breed_classifier/blob/master/images_for_post/4_layer_custom_cnn.JPG?raw=true)
![Performance of 4 layer custom CNN](https://github.com/StefanFiorese/dog_breed_classifier/blob/master/images_for_post/transfere_cnn_performance.JPG?raw=true)
