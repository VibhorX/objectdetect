# Real-time Object Detection using OpenCV

This Python script demonstrates real-time human (face) detection using the Haar Cascade classifier in OpenCV. It captures video from the default camera, detects faces in the video frames, and draws rectangles around the detected faces.

## Requirements

- Python 3.x
- OpenCV

## Usage

1. Make sure you have OpenCV installed (`pip install opencv-python`).
2. Run the Python script (`python human_detection.py`).
3. Position yourself in front of the camera.
4. The script will detect and draw rectangles around your face(s) in real-time.

## Description

- The script uses OpenCV's `CascadeClassifier` class to load the pre-trained Haar Cascade classifier for face detection.
- It captures video frames from the default camera (change the `cap = cv2.VideoCapture(0)` line if using a different camera).
- Each frame is converted to grayscale for face detection.
- The Haar Cascade classifier is used to detect faces in the grayscale frames.


## Additional Notes

- Haar Cascade classifiers are relatively fast but may have limitations in detecting faces under certain conditions, such as varying lighting conditions or occlusions.


