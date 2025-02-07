# Business understanding

This project is part of the course **CVI03.HS24 Computer Vision** from the **MSc in Applied Information and Data Science** at **HSLU**.

## Problem Statement
Bone fractures are a common medical condition that can occur due to accidents, osteoporosis, or other underlying health conditions. Early and accurate detection of fractures is crucial for effective treatment and recovery. However, manual analysis of X-ray images can be time-consuming and prone to human error. 

## Objective
The goal of this project is to leverage machine learning and deep learning techniques to automate the detection and classification of bone fractures using medical imaging data. By developing a robust fracture detection model, we aim to:
- Improve the accuracy of fracture diagnosis
- Reduce the time required for analysis
- Assist radiologists and medical professionals in making better-informed decisions

## Dataset
This project utilizes the **FracAtlas** dataset, which is available on Kaggle: [FracAtlas Dataset](https://www.kaggle.com/datasets/shyamgupta196/fracatlas). The dataset contains X-ray images of bones with annotations indicating the presence of fractures. 

Many existing X-ray datasets are either too small for training machine learning models or lack proper annotation for localization and segmentation tasks. This limitation makes it difficult to compare state-of-the-art (SOTA) methods and hinders the development of robust machine-learning algorithms. The **FracAtlas** dataset addresses this issue by providing over 14,000 X-ray scans collected from three major hospitals in Bangladesh. From this raw data, 4,083 images have been manually annotated for classification, localization, and segmentation of bone fractures in hand, leg, hip and shoulder regions.  All scans are available in JPG format with proper annotations, making this dataset a valuable resource for developing and benchmarking fracture detection models.

## Expected Outcomes
- A trained machine learning model capable of detecting fractures with high accuracy.

  ADD HERE INFO, WHAT KIND OF MODELS WERE USED OR WERE COMPARED

- Visualizations and insights into the dataset's characteristics and model performance.

- Potential integration into a clinical decision support system for automated fracture detection.