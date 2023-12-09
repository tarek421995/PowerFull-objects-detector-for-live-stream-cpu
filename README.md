Real-Time Object Detection with MediaPipe and OpenCV
Overview

This repository hosts a Jupyter Notebook implementing real-time object detection, utilizing the capabilities of MediaPipe and OpenCV. This solution aims to be more stable and efficient than the native Google live streaming object detection, making it suitable for robust real-time applications.
Features

    Real-Time Object Detection: Leverages MediaPipe for efficient object detection.
    OpenCV Integration: Utilizes OpenCV for video capture and image processing.
    Customizable Detection Threshold: Allows tweaking the sensitivity of the object detection.
    Results Visualization: Displays detection results with bounding boxes and labels.

Requirements

    Python 3.x
    OpenCV
    MediaPipe

Installation

To set up this project, install the necessary dependencies using the following commands:

bash

pip install opencv-python
pip install mediapipe

Usage

To run the object detection, open the Jupyter Notebook:

bash

jupyter notebook object_detection.ipynb

Execute the cells in the notebook to start the object detection process. The notebook will access the webcam (or a specified video file) and begin detecting objects in real-time, highlighting them with bounding boxes.
How It Works

The Jupyter Notebook initializes a MediaPipe Object Detector using a pre-trained model. It captures frames from the webcam (or a video file), converts them to RGB format, and feeds them into the MediaPipe Object Detector. The detection results are then visualized on the frames and displayed within the notebook.
Customization

You can adjust the object detection threshold and other parameters by modifying the ObjectDetectorOptions within the notebook.
