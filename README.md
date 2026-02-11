# Face-Eye-Detection-using-OpenCV-Gradio


## I’m excited to share my recent computer vision project where I built a Face and Eye Detection system using Python, OpenCV (Haar Cascade), NumPy, and Gradio.

## ==> What this project does:
Detects faces and eyes in real-time from uploaded images
Uses Haar Cascade Classifiers for accurate detection
Provides an interactive web-based UI using Gradio
Draws bounding boxes around detected faces and eyes instantly

## ==> Tech Stack:
Python
OpenCV (cv2)
Haar Cascade Classifiers
NumPy
Gradio

## ==> How it works (Code Flow):
Load pre-trained Haar Cascade XML files
Convert input image from PIL to OpenCV format
Convert image to grayscale for better detection
Detect faces first, then eyes within each detected face
Draw rectangles and display the processed output using Gradio

## ==> Challenges Faced & Solutions:
 ModuleNotFoundError: cv2 → Solved by installing opencv-python
Image format mismatch between Gradio & OpenCV → Fixed using NumPy conversion


This project strengthened my fundamentals in Computer Vision and real-time image processing, and it’s a solid step toward advanced AI applications 
