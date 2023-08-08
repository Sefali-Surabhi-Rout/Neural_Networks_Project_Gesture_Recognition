# Neural Networks Project: Gesture Recognition
## Problem Statement: 
A model that will be able to predict the 5 gestures correctly is to be built.Each gesture corresponds to a specific command:
- Thumbs up: Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds
- Stop: Pause the movie
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
## General Information
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. 
- The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.
- Each video is a sequence of 30 frames (or images) and they are of two types of dimensions - either 360x360 or 120x160.

## Conclusions
- Models of two types of architectures i.e. 3D convolutional network and CNN+RNN were trained. The Best performing model has training accuracy of 69% and validation accuracy of 61%.
## Technologies Used
- pathlib
- tensorflow 
- matplotlib
- numpy
- pandas
- os
- PIL
- glob
- cv2
- datetime
- random
