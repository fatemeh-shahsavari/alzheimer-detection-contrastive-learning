# alzheimer-detection-contrastive-learning
Alzheimer's disease diagnosis in three classes 'AD', 'CI', 'CN'


# Alzheimer's Disease Detection using Contrastive Learning

## Overview

This repository contains the implementation of a semi-supervised deep learning architecture for Alzheimer's disease classification using MRI images. The project leverages contrastive representation learning with k-nearest neighbors (KNN) and convolutional neural networks (CNN) to achieve high accuracy with limited labeled data.

## Abstract

Alzheimer's disease is a neurodegenerative disorder with unknown onset and progressive development. Currently, there is no accurate diagnosis method or treatment that can alter the disease's effects. Given that symptoms include sudden and severe memory loss, there are high costs associated with patient care. Accurate diagnosis of this disease is crucial for patients and society.

With the increasing volume of data generated in this field, machine learning methods, particularly self-supervised and semi-supervised learning approaches such as contrastive representation learning, can be utilized as powerful tools to address this challenge.

## Key Features

- **Semi-supervised learning approach** using contrastive representation learning with k-nearest neighbors
- **Lightweight CNN architecture** with fewer parameters compared to traditional supervised networks
- **Data augmentation techniques** to increase training dataset size
- **98% accuracy** on Kaggle dataset with only 20% labeled data (~3% improvement over baseline)
- **99% accuracy** on ADNI baseline dataset
- Faster execution time due to optimized network architecture

## Datasets

### 1. Kaggle Alzheimer's Dataset
- **Classes:** 4 categories
  - Moderate Demented
  - Mild Demented
  - Very Mild Demented
  - Non Demented
- **Performance:** 98% accuracy on test set

### 2. ADNI Baseline Dataset
- **Classes:** 3 categories
  - Healthy Control (CN)
  - Mild Cognitive Impairment (MCI)
  - Alzheimer's Disease (AD)
- **Performance:** 99% accuracy on test set

## Architecture

The proposed architecture consists of:
1. **Data Augmentation Layer:** Increases training sample diversity
2. **Convolutional Neural Network:** Extracts important image features
3. **Contrastive Learning Module:** Self-supervised pre-training phase
4. **Semi-supervised Fine-tuning:** Training with limited labeled data (20%)

## Installation

### Prerequisites
- Python 3.8+
- TensorFlow/PyTorch
- NumPy
- Matplotlib
- scikit-learn



