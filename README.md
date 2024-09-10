# UCCC2513_Assignment_T05

# Project A
# Project Overview
## This project implements a traffic sign detection system using computer vision techniques. The system uses Histogram of Oriented Gradients (HOG) for feature extraction and a linear SVM (Support Vector Machine) for classification. Non-Maximum Suppression (NMS) is applied to filter out redundant bounding boxes after detection.

## Features
- Traffic Sign Detection: Detects traffic signs in an image using HOG feature extraction and SVM classification.
- Non-Maximum Suppression (NMS): Removes overlapping bounding boxes to retain only the most confident detections.
- Intersection over Union (IoU) Calculation: Evaluates detection performance by comparing predicted bounding boxes with ground truth.
- Visualization: Displays the detection results with bounding boxes for both ground truth and predictions.

## Setup Instructions
### Prerequisites
The following Python libraries installed:
- pandas
- cv2 (OpenCV)
- numpy
- os
- sklearn (scikit-learn)
- scipy

## Running the Code
### Method 1 (Run the training and detection pipeline)
You need to run both cells under:
1) Import library
2) Load train set and test set metadata
3) Crop negative samples and store the negative samples
4) Load training samples
5) Train SVM
6) Detection
The following figure shows the notebook of the project, run each cell under 1) - 6) for the training and detection pipeline from UCCC2513_Assignment_T05_SourceCode.ipynb.
![image](https://github.com/user-attachments/assets/82aafc75-5d1a-454f-a1dd-8e7450129816)


### Method 2 (Run the detection pipeline only)
For running the detection pipeline only, you need to run both cells under:
1) Import library
2) Load train set and test set metadata
6) Detection

