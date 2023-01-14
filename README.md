# Closed eyes detection

## Łukasz Cettler (s20168) oraz Wojciech Mierzejewski (s21617) - grupa 74C

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About The Project](#about-the-project)
* [Technologies Used](#technologies-used)

<!-- ABOUT THE PROJECT -->
## About The Project

 In this program, we check if a person’s eyes have been closed while looking at the screen.
 If the eyes have been closed for an extended period (beyond a certain threshold value), the program will alert the user by playing an alarm sound and showing a message.
 
We used with shape_predictor(). It's a tool that takes in an image region containing some object and outputs a set of point locations that define the pose of the object. It predict 68 points in human faces using dlib’s pre trained model - Shape Predictor 68 dataset.

We also used Haar Cascades - an algorithm that can detect objects in images, irrespective of their scale in image and location. It tries to compute features in every window and classify whether it could be an object. We used Pre-trained Haar Cascades with Human face detection.

[Testing Video](https://www.youtube.com/watch?v=o82xeXoxKVc)

## Technologies Used

* Python
* numpy library
* dlib library
* pygame library
* imutils library
* opencv_python library
* scipy library
