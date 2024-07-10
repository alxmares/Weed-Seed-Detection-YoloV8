# Weed Seed Detection using YOLOv8

## Overview

This project aims to detect various types of weed seeds using the YOLOv8 object detection model. It involves image preprocessing, data preparation, and training a state-of-the-art deep learning model to accurately identify and classify weed seeds in images.

## Introduction

### Objective
- Preprocess and prepare image data for object detection
- Train and evaluate a YOLOv8 model for weed seed detection
- Develop a robust pipeline for converting image annotations and standardizing image inputs

## Methodology

### Image Processing
- **Rescale Images**: Rescaled images to 640x640 pixels to standardize input for the YOLOv8 model
- **Annotation Conversion**: Converted XML annotations to YOLO format (.txt) for compatibility with the model

### Data Preparation
- **Data Pipeline**: Automated the conversion of XML annotations to YOLO format and organized datasets
- **Dataset Structuring**: Created `data.yaml` files to structure the datasets for training

### Model Training
- **YOLOv8 Training**: Utilized the YOLOv8 model to train on the prepared dataset, optimizing for accuracy in weed seed detection

## Results

### Detection Results
The YOLOv8 model successfully detected and classified weed seeds with high accuracy. Below is an example of the detection results:

![Detection Results](/assets/results.jpg)

### Model Performance
Achieved an accuracy of 97% in detecting and classifying weed seeds. The preprocessing steps ensured consistency and reliability in the training data, contributing significantly to the model's performance. Performance graphs illustrate the accuracy and loss metrics during training:

![Performance Graphs](/assets/graphs.png)

### Evaluation Metrics
The confusion matrix below shows the distribution of true positives, false positives, true negatives, and false negatives, highlighting the model's effectiveness in distinguishing between different weed seeds:

![Confusion Matrix](/assets/confussionmatrix.png)

## Conclusion

This project demonstrates the application of advanced image processing and deep learning techniques to the field of agricultural technology. By leveraging YOLOv8 for weed seed detection, we have developed a robust and efficient model capable of accurate object detection, providing valuable insights and tools for weed management.

## Appendix

### Notebooks
- [01-Rescale Images](/01-Rescale_images.ipynb)
- [02-Preparing Data](/02-Preparing_data.ipynb)
- [03-YOLOv8 Model Training](/03-YoloV8.ipynb)
