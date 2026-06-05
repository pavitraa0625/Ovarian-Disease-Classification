# Ovarian Disease Classification Using YOLO

## Overview

This project presents a comparative study of YOLO-based deep learning models for multi-class ovarian disease classification using ultrasound images. The study evaluates the performance of YOLOv8-cls, YOLOv11-cls, and YOLOv12-cls on the MMOTU ovarian ultrasound dataset under identical experimental conditions.

## Dataset

**MMOTU (Multi-Modality Ovarian Tumor Ultrasound) Dataset**

* Total Images: 1416
* Total Classes: 7
* Classes:

  * Normal Ovary
  * Teratoma
  * Chocolate Cyst
  * Simple Cyst
  * Theca Cell Tumor
  * Serous Cystadenoma
  * Mucinous Cystadenoma

## Data Preprocessing

* Image resizing to 224 × 224 pixels
* Grayscale to RGB conversion
* Stratified train-validation-test split
* Data augmentation techniques:

  * Rotation
  * Horizontal flipping
  * Vertical flipping
  * Brightness adjustment
  * Noise addition

## Models Evaluated

* YOLOv8-cls
* YOLOv11-cls
* YOLOv12-cls

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* PR-AUC

## Results

| Model       | Test Accuracy |
| ----------- | ------------- |
| YOLOv8-cls  | 70.14%        |
| YOLOv11-cls | 77.08%        |
| YOLOv12-cls | 53.47%        |

YOLOv11-cls achieved the best overall performance, obtaining a test accuracy of **77.08%** and outperforming the other evaluated architectures.

## Repository Contents

* YOLOv8 implementation notebook
* YOLOv11 and YOLOv12 implementation notebook
* Evaluation metrics notebook
* Research paper

## Research Publication

**A Comparative Study of YOLO-Based Models for Multi-Class Ovarian Disease Classification**

This work investigates the effectiveness of YOLO-based classification architectures for ovarian disease detection using ultrasound imaging and provides a comparative analysis of their performance.

## Authors

* M. Sai Meghana
* K. L. Anvitha
* P. Pavitra Kumari
* B. Saranya Devi
