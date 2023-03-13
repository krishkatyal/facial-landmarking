# Exploring the Robustness and Accuracy of Facial Landmark Detection using OpenCV, dlib, and Python
## Introduction
This is a simple script for detecting facial landmarks in images using OpenCV, dlib and Python. The script takes an input image and returns the facial landmarks and bounding boxes for each face detected in the image.

## Getting Started
To use the script, you need to install the following libraries:
- imutils
- numpy
- argparse
- dlib
- OpenCV

You can install these libraries using `pip install` command.

## Usage
To use the script, run the following command:
python facial_landmarking.py --shape-predictor shape_predictor_68_face_landmarks.dat --image image.jpg
where `shape_predictor_68_face_landmarks.dat` is the path to the pre-trained facial landmark predictor and `image.jpg` is the path to the input image.

## Output
The script will output an image with the facial landmarks and bounding boxes for each face detected in the input image. The output image will be displayed on the screen and saved as `output.jpg` in the current working directory.

