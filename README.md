# Medical-Image-Annotation-Job

## Overview
This project aims to develop machine learning models for detecting pneumonia in chest X-ray images. The project was completed as part of the **Makeen Program** and utilizes the **Appen** platform for data collection and annotation.

## Datasets
The project includes multiple datasets:
1. **Clean/Unbalanced**: 100 "normal" images and 300 "pneumonia" images.
2. **Dirty/Balanced**: 100 "normal" images and 100 "pneumonia" images, with intentional mislabeling (30 "normal" images in the pneumonia folder and 30 "pneumonia" images in the normal folder).
3. **3-Class**: A dataset with three classes: "normal", "bacterial pneumonia", and "viral pneumonia".

## Model Details
- **Binary Classification Model**: Differentiates between "normal" and "pneumonia" classes.
- **3-Class Model**: Identifies "normal", "bacterial pneumonia", and "viral pneumonia".

## Evaluation Metrics
The models were evaluated using the following metrics:
- **Precision**: The proportion of true positive results in the predicted positive cases.
- **Recall**: The proportion of true positive results in the actual positive cases.
- **F1 Score**: The harmonic mean of precision and recall, providing a single score to assess model performance.

## Results
- The binary classification model achieved a precision, recall, and F1 score of **1.0**.
- Confusion matrices were analyzed to identify areas of improvement and model robustness.

## Installation
To run this project locally, ensure you have the following dependencies installed:
- Python
- Required libraries (e.g., TensorFlow, Keras, NumPy, etc.)

Clone the repository:
```bash
git clone [Your GitHub Repository URL]
