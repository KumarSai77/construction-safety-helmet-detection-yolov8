# Construction Safety Helmet Detection using YOLOv8

## Overview

This project implements a Computer Vision system for detecting construction safety helmets using YOLOv8.

The model was trained on a large annotated construction-site dataset and evaluated on unseen images to assess real-world performance.

## Problem Statement

Construction sites require workers to wear protective helmets for safety compliance. Manual monitoring can be time-consuming and inconsistent.

This project automates helmet detection using deep learning and object detection techniques.

## Technologies Used

* Python
* YOLOv8
* OpenCV
* PyTorch
* Computer Vision

## Model Performance

| Metric    | Value |
| --------- | ----- |
| Precision | 97.1% |
| Recall    | 92.9% |
| mAP50     | 96.8% |
| mAP50-95  | 91.9% |

## Workflow

1. Dataset Preparation
2. Model Training
3. Evaluation
4. Image Inference
5. Error Analysis

## Results

The trained model successfully detected construction helmets in unseen images.

During testing, the model showed stronger performance on helmet styles and viewpoints similar to the training data. Additional dataset diversity may further improve robustness.

## Future Improvements

* PPE Detection (Helmet + Vest)
* Video-based Detection
* Real-Time Webcam Detection
* Construction Site Monitoring



## Dataset

This project was trained on a publicly available construction safety helmet dataset obtained from Roboflow Universe.

The dataset contains annotated images of construction workers wearing safety helmets and was used for training and validation of the YOLOv8 object detection model.

Dataset Source:
Hard Hat Detection.v2.yolov8



## Author

Kumar Sai


