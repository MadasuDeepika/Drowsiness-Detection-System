# Drowsiness-Detection-System
Driver drowsiness detection system

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


shape_predictor_68_face_landmarks.dat dlib.get_frontal_face_detector () is used in detecting the face in a frame or image.
This can be downloaded from https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat


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
