# Drowsiness-Detection-System
Driver drowsiness detection system

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


### Description 📌

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye1.jpg">


#### Relationship

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye2.png">

#### Summing up

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye3.jpg">


For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

### Results 📊

<img src="https://github.com/akshaybahadur21/BLOB/blob/master/drowsy.gif">


### Execution 🐉
To run the code, type `python Drowsiness_Detection.py`

```
python Drowsiness_Detection.py
```
