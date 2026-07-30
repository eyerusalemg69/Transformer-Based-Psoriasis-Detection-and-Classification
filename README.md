# Transformer-Based Psoriasis Detection and Classification

## Overview
This project applies deep learning for binary classification of psoriasis images.  
A ResNet-50 teacher model guides a DeiT student model using knowledge distillation.  
The pipeline includes data augmentation, training with early stopping, and evaluation with multiple metrics.

## Dataset
The original psoriasis dataset is private and not shared due to ethical restrictions.  
This repository contains only the code.  
To run the project, place your own dataset in the following structure:

data/
  train/
    class1/
    class2/
  val/
    class1/
    class2/
  test/
    class1/
    class2/

## Results
- Confusion matrix
- ROC curve
- Misclassified image visualization
- Training/validation accuracy and loss plots

## How to Run
```bash
pip install -r requirements.txt
python src/train.py

## Author
Developed by Eyerusalem Gebremeskel
