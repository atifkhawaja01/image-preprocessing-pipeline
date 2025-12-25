# Image Preprocessing Pipeline (CIFAR-10)

This repository implements a custom image preprocessing pipeline for color images,
inspired by step-by-step preprocessing workflows used in machine learning.

The goal is to demonstrate how different image transformations affect image structure,
pixel values, and suitability for deep learning models.

## Dataset
- CIFAR-10 (public color image dataset)

## Images Used
- Two sample images selected from the CIFAR-10 test set

## Preprocessing Steps
1. Resize images to a fixed resolution
2. Convert RGB images to grayscale
3. Apply rotation for data augmentation
4. Apply horizontal flipping
5. Normalize pixel values
6. Apply a custom sharpening filter (Bonus)

## Outputs
- Side-by-side visualizations for each preprocessing step
- Printed image shapes and pixel value ranges
- Final tensor output of shape [batch_size, C, H, W]

## Tools & Libraries
- PyTorch
- Torchvision
- OpenCV
- Matplotlib
- NumPy

## Execution
The notebook is designed to be executed in Google Colab with optional GPU support.
