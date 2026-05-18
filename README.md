# Pet Mischief Detector

An end-to-end computer vision project that detects pets and household objects in images, then estimates whether the scene represents a potentially mischievous situation.

## Features

- Custom dataset curated from COCO classes
- YOLOv8 object detection
- Train/validation/test split with YOLO formatting
- Detection of pets and risky household objects
- Rule-based mischief risk scoring
- Spatial reasoning using bounding box distance and overlap
- Low, medium, and high risk warnings
- Quantitative evaluation using mAP, precision, and recall
- Qualitative failure analysis

## My Contributions

- Built the dataset splitting and formatting pipeline
- Exported the dataset into YOLO format
- Implemented detector evaluation code
- Designed and refined the mischief-logic module
- Generated qualitative output images
- Analyzed false positives, missed detections, and robustness issues

## Technologies Used

- Python
- YOLOv8
- Ultralytics
- OpenCV
- FiftyOne
- NumPy
- Google Colab
- Object Detection
- Computer Vision

## Results

- mAP@0.5: 0.3831
- mAP@0.5:0.95: 0.2457
- Precision: 0.4306
- Recall: 0.4213

## Report

[Project Report](Project_Report_25142309x_PATEL_Diya.pdf)
