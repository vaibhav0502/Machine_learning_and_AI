# Machine_learning_and_AI


# Gesture Recognition

## Problem statement

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

| Gesture | Command |
| --- | --- |
| Thumbs up | Increase the volume |
| Thumbs down | Decrease the volume |
| Left swipe | Jump backwards 10 seconds |
| Right swipe | Jump forward 10 seconds |
| Stop | Pause the movie |


## Understanding the Dataset
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 
Two CSV files for the 'train' and a 'val' folder.

Specifically, videos have two types of dimensions - either 360x360 or 120x160
