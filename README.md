# Computer Vision Practical Assignment

## Overview

This project explores how computers process images, improve image quality, extract visual features, recognize objects, and estimate motion in video streams. It covers foundational and modern computer vision techniques implemented in Python using OpenCV, scikit-image, NumPy, Matplotlib, and Ultralytics YOLOv8.

## Objectives

* Task 1: Image restoration using noise injection and filtering, followed by morphological processing and watershed segmentation.
* Task 2: Feature extraction using Histogram of Oriented Gradients (HOG) and SIFT keypoint detection with Brute-Force matching and Lowe's ratio test.
* Task 3: Object recognition using deep learning-based YOLOv8 detection.
* Task 4: Video motion estimation using frame differencing, GMM background subtraction, and Lucas-Kanade optical flow.

## Technologies and Libraries

| Library or Tool | Purpose |
| :--- | :--- |
| Python | Main programming language |
| OpenCV (`cv2`) | Image processing, feature detection, geometric transforms, video capture, and optical flow |
| scikit-image (`skimage`) | Image quality metrics (PSNR, SSIM) and HOG feature extraction |
| Ultralytics YOLO (`ultralytics`) | Deep learning-based object detection (`yolov8n.pt`) |
| NumPy | Numerical operations and array manipulations |
| Matplotlib | Visualizing intermediate and final image/video results |
| Git and GitHub | Version control and project hosting |

## Project Structure

```text
Computer-Vision-Project/
├── input/                  # Input images and video dataset
├── outputs/                # Generated processing results and visual outputs
├── notebooks/              # Jupyter Notebooks containing implementation code
├── requirements.txt        # Python package dependencies
└── README.md               # Technical project documentation