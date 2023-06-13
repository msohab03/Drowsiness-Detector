# Drowsiness-Detector
A drowsiness detection module to keep drivers alert 😴 🚫
## Application 🍎
This can be implemented in automobiles to alert the driver if they fall asleep at the wheel.
### Code Dependencies 🏁
* import cv2
* import dlib
* import imutils
* import scipy
### Description 📍
A real-time video stream is analyzed by a computer vision system to automatically identify signs of driver drowsiness, triggering an alarm when the system detects drowsiness in the driver.
### Algorithm 🧪
The coordinates of the eyes are denoted by 6 (x, y) pairs, beginning from the top-left corner of the eye (from the perspective of the observer), and progressing in a clockwise direction around the eye.

It checks for an arbitrary wait time of 6 seconds or 20 frames to avoid flickering and changes status depending on the position of the eye mapped using the 68 facial markers. 
<img src="https://github.com/msohab03/Drowsiness-Detector/blob/main/assets/Screenshot%20(65).png">

### Results 📊

<img src="https://github.com/msohab03/Drowsiness-Detector/blob/main/assets/Screenshot%20(70).png">

<img src="https://github.com/msohab03/Drowsiness-Detector/blob/main/assets/Screenshot%20(71).png">

### Execution 🐉
To run the code, type `python Drowsiness_Detection.py`

```
python DrowsinessDetector.py
```

## References 🍷
 
 -   Adrian Rosebrock, [PyImageSearch Blog](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

