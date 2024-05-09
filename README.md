# Chest X-ray Classification Model

## Overview
This repository contains a model for classifying chest X-ray images into two categories: Pneumonia and Normal. The dataset used for training, testing, and validation consists of 5,863 X-ray images in JPEG format organized into three folders: train, test, and val. Each folder contains subfolders for each image category (Pneumonia/Normal).The dataset has been balanced, with 1,341 images for each class (NORMAL and PNEUMONIA)

## Dataset Details
The chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients aged one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

## Model Architecture
The model architecture used in this project is based on the ResNet50 pretrained model. The model was trained to achieve an accuracy score of 95%. During testing, the model showed the following performance metrics:
- True Positives (TP): 67
- True Negatives (TN): 61
- False Positives (FP): 6
- False Negatives (FN): 1


## Model Testing
The trained model has been tested with random chest X-rays available on the internet. It demonstrates a robust capacity to differentiate between Pneumonia and Normal X-rays.

## Files Structure
- `train/`: Contains training images organized into subfolders for each category.
- `test/`: Contains testing images organized into subfolders for each category.
- `val/`: Contains validation images organized into subfolders for each category.


## Note
This model is intended for research and educational purposes only. It should not be used for diagnostic or clinical purposes without proper validation and regulatory approval.

# Link
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
