# Driver-Drowsiness-Detection-System 😴 🚗
This system can detect your eyes and alert when the user is drowsy.


**Applications** 🎯

This can be used by drivers who tend to drive for a longer period of time that may lead to accidents.


**Code Requirements**

The code will run in Python (Version 2.7 or higher).


**Model**

RaspberryPi3 B+ Model is used in this project


**Dependencies**

1.import face_recognition       
2.import cv2     
3.import numpy as np     
4.import cv2       
5.import eye_game   
6.import RPi.GPIO as GPIO



**Description 📌**

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.


**Algorithm 👨‍🔬**

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It will continously monitor the driver and if Eye Aspect Ratio is less than 0.25, it will alert with an alarm.

![eye1](https://user-images.githubusercontent.com/76579075/128130146-ac83e5d9-7a29-4326-9a18-74007e53b6b4.jpg)


**Formula:**

![eye2](https://user-images.githubusercontent.com/76579075/128130227-78c2a745-d00c-49a2-b008-2a32f7432bfd.jpg)


**Summing up**

![eye3](https://user-images.githubusercontent.com/76579075/128130408-b1132459-e934-42f9-94e4-7baad8f6dc04.jpg)


**Execution**

To run the code, type  
python3 Driver_Drowsiness_Detection.py


