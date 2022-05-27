# AI_Trash_System

This documentation is about an upcoming research-work publication. 

## Introduction

Countries around the world struggle with the problem of waste recycling and management. This repository outlines an approach for a computer vision-based system which detects and classifies waste into various recyclable and non-recyclable categories.

As living standards around the globe improve, the waste produced by countries all over the world is increasing exponentially. Given this rise in waste generation, waste management and recycling are rapidly becoming a very important aspect for sustainable living. However, many countries, including India are lagging behind.

This repository highlights an approach for a computer vision-based system which detects and classifies waste into various recyclable and non-recyclable categoriesd. It detects the objects present in an image frame and classifies them in their correct category- plastic, paper, metal, glass or trash (non-recyclable) with an accuracy of 61%. The system is designed as a highly portable system which can be used in almost all domestic or office settings. The detection is done through images captured by a Raspberry Pi 4 camera module with the help of a Raspberry Pi. The architectural model used for this task is the EfficientDet-Lite0 object detection model.

## Methodology 

![image](https://user-images.githubusercontent.com/80118039/170722429-64dbd679-02f4-41d2-9386-13f2c854452f.png)

## Hardware Implementation 

![20220512_230145](https://user-images.githubusercontent.com/80118039/170724519-8d221bbe-6dee-4048-b766-2cf4bb31601d.jpg|width = 100)

## Results

The system works with an 61% accuracy, which is a good accuracy for object detection models. 

![image](https://user-images.githubusercontent.com/80118039/170724627-e868e19a-7df3-4400-928a-0a2f266b1992.png|width=75)
Detecting metal in the image frame

![image](https://user-images.githubusercontent.com/80118039/170724674-281d0e52-4b01-4d4f-801f-00a1228aa2cc.png|width=75)
Detecting plastic in the image frame

## References

1. https://tfhub.dev/tensorflow/efficientdet/lite0/detection/
2. https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/raspberry_pi
