# Crowd-Detection
This project aims to detect and estimate crowd density in video footage using computer vision techniques. It is designed to support applications such as event monitoring, public safety, and automated surveillance. The system processes video input to identify and count human presence in real-time or batch mode.

## Objectives
- Detect people in surveillance footage using image processing techniques.
- Estimate the density or count of individuals in a frame.

## Key Features
- Frame-by-frame video processing using OpenCV
- Background subtraction and contour detection
- Real-time crowd detection and density estimation
- Option for ROI (Region of Interest) selection to limit analysis to specific zones

## Technologies Used
Python
OpenCV (cv2) – for video processing and frame extraction
NumPy – for numerical operations
Pandas – for data handling and logging
Matplotlib – for visualization
Scipy – for calculating spatial distances
Ultralytics YOLO – for object detection (people detection)
Torch (PyTorch) – as backend for YOLO model
Google Colab – for notebook execution and file handling

