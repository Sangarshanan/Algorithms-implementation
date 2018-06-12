# Implementing Basic concepts and algorithms

Implementation of the some interesting concepts and algorithms to help understand them better

## K- means algorithm ##

K means is an unsupervised machine learning algorithm that clusters similar points that are close in an n dimensional space

This is one of the very first algorithms that I was able to comprehend and appreciate, It is incredibly simple and also effective in nature. In My implementation I have first used a library to get the answer in a single step and then implement the algorithm from scratch to verify the correctness.
* Input: The points in the plane inside a txt file
* Output: Centroids of K clusters are saved in the txt file



## Convolutions ##

A convolution is very useful for signal processing in general. There is a lot of complex mathematical theory available for convolutions. 

http://machinelearninguru.com/computer_vision/basics/convolution/image_convolution_1.html

You can use a simple matrix as an image convolution kernel and do some interesting things!

## Deep Dream ##

A base image is used, which is fed to the pre-trained CNN. Then, forward pass is done till a particular layer. Now, to get a sense of what that layer has learned, we need to maximize the activations through that layer.

https://hackernoon.com/dl06-deepdream-with-code-5f735052e21f


The gradients of that layer are set equal to the activations from that layer, and then gradient ascent is done on the input image. This maximizes the activations of that layer


However, doing just this much does not produce good images. Various techniques are used to make the resulting image better. Gaussian blurring can be done to make the image smoother.
One main concept in making images better is the use of octaves. Input image is repeatedly downscaled, and gradient ascent is applied to all the images, and then the result is merged into a single output image.
![alt text](https://camo.githubusercontent.com/c45620849e3c05fc1cbf6f4f4786f89c98153159/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f626f6f6b2e6b657261732e696f2f696d672f6368382f64656570647265616d5f70726f636573732e706e67)

## Open AI Gym ##

A toolkit for developing and comparing reinforcement learning algorithms.

#### Problem:

A car is on a one-dimensional track, positioned between two "mountains". The goal is to drive up the mountain on the right; however, the car's engine is not strong enough to scale the mountain in a single pass. Therefore, the only way to succeed is to drive back and forth to build up momentum.




