# Transfer-Learning

This project applies transfer learning for rock image classification using a pretrained neural network. The dataset consists of 360 training images and 120 validation images, grouped into 30 rock categories.

## Key Components:
### Dataset Preparation:
Organizing images into 30 categories (12 images per category for training, 4 for validation).
Grayscale conversion and image resizing for optimization.
### Input Pipeline & Data Augmentation:
Implementing preprocessing operations and data augmentation for model generalization.
### Transfer Learning & Fine-Tuning:
Removing the top layer of a pretrained model.
Adding two new layers (8 neurons + softmax with 30 output classes).
### Stepwise fine-tuning: First training only new layers, then full model training.
Training for at least 20 epochs and tracking loss/accuracy trends.
### Performance Evaluation:
Plotting train & validation loss/accuracy, marking when full fine-tuning begins.
Discussing model performance, convergence, and hyperparameter tuning.
### Feature Representation Analysis:
Procrustes Analysis to compare network-extracted features with human-judged data.
Reporting 8 correlation coefficients and their average for both training and validation sets.
