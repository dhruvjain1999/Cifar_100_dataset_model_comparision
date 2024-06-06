# CIFAR-100 Image Classification Project

![Project Gif](link-to-your-gif.gif)

## Overview

This project focuses on image classification using the CIFAR-100 dataset. The goal is to classify images into one of 100 classes, which include animals, vehicles, and various everyday objects.

## Features

- Utilizes TensorFlow and Keras for model development.
- Implements data augmentation techniques to improve model generalization.
- Includes three different models for comparison: a custom CNN, ResNet50, and VGG16.
- Evaluates models on test set accuracy, inference speed, and robustness to noise.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the training script:

   ```bash
   python train.py
   ```

4. Evaluate models:

   ```bash
   python evaluate.py
   ```

## Results

- **Custom CNN:**
  - Test Accuracy: 42.06%
  - Inference Speed: 87.20 samples per second
  - Robustness: 41.69% accuracy on noisy images

- **ResNet50:**
  - Test Accuracy: 34.48%
  - Inference Speed: 9.09 samples per second
  - Robustness: 34.63% accuracy on noisy images

- **VGG16:**
  - Test Accuracy: 26.29%
  - Inference Speed: 49.34 samples per second
  - Robustness: 26.05% accuracy on noisy images

## Novel Image Testing

- Uploaded and tested on the trained models.
- ResNet50 predicted "poppy" with 1.46% probability.
- VGG16 predicted "clock" with 100% probability.
- Custom CNN predicted "apple" with 82.93% probability.

## t-SNE Visualization

- Visualized embeddings of the models to see class separability.
- t-SNE plots for each model included.

## Conclusion

This project demonstrates the effectiveness of different models for image classification on the CIFAR-100 dataset. The custom CNN outperforms ResNet50 and VGG16 in terms of accuracy and inference speed, while VGG16 shows higher robustness to noise.

Feel free to explore the code and experiment with different architectures and hyperparameters!

---
