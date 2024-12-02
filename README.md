# Lung Disease Detection from Chest X-rays

## Overview
This project uses deep learning techniques to classify chest X-ray images into five categories:
- Viral Pneumonia
- Bacterial Pneumonia
- COVID-19
- Tuberculosis
- Normal Lungs

The goal is to support early diagnosis and enhance medical decision-making.

## Dataset
- The dataset was created by combining multiple publicly available datasets.
- Duplicate images were removed using VisiPics.
- Augmentation was applied to expand the dataset to 10,000 images.

## Project Workflow
1. **Data Preprocessing**:
   - Duplicate removal and quality assurance.
   - Data augmentation to balance the classes.
2. **Model Training**:
   - A convolutional neural network (CNN) was used for feature extraction and classification.
3. **Validation and Testing**:
   - Performance metrics include accuracy, precision, and recall.

## Features
- Automated detection of lung diseases from chest X-ray images.
- High accuracy with robust deep learning models.
- Scalable and efficient for real-world applications.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
