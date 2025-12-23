# Food Freshness & Quality Classifier

This project uses deep learning and computer vision to classify food images into
Fresh, Okay, or Spoiled categories.

## Tech Stack
- Python
- TensorFlow / Keras
- Transfer Learning (CNN)
- Google Colab
- GitHub

## Status
🚧 In progress
# Food Freshness & Quality Classifier

## Problem Statement
Assessing food freshness manually is subjective and error-prone.
This project uses deep learning and computer vision to automatically
classify food images based on their freshness.

## Dataset
The project uses the Fruits Fresh and Rotten dataset from Kaggle,
which contains images of fresh and spoiled fruits across multiple categories.

## Methodology
- Image preprocessing and normalization
- Data augmentation for robustness
- Transfer learning using a pre-trained CNN
- Multi-class image classification
- Model fine-tuning to improve performance

## Model Architecture
MobileNetV2 was used as the base convolutional neural network.
Custom fully connected layers were added on top, followed by a softmax
output layer for multi-class classification.

## Results
The final trained model achieved approximately 90–95% validation accuracy
on the test dataset.

## Evaluation
Model performance was evaluated using accuracy and loss curves,
confusion matrix analysis, and visual inspection of sample images.

## Tools & Technologies
- Python
- TensorFlow / Keras
- Google Colab
- GitHub
