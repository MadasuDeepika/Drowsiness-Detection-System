# Drowsiness-Detection-System
Driver drowsiness detection system

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


### Description:

Python application to assist drivers to alert when they feel drowsy and thus reduce the number of accidents.

### Algorithm:

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.


### Execution:
To run the code, type `python Drowsiness_Detection.py`

```
python Drowsiness_Detection.py
```
