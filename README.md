# HypImg-semantic-segmentation

Made by Bolohan Marian Cristian

This project implements **semantic segmentation** of hyperspectral images using **Convolutional Neural Networks (CNNs)**, specifically utilizing a **U-Net** architecture. The goal is to segment hyperspectral images into different classes based on pixel-level analysis. This project also includes a notebook of an analysis on supervised method for hyperspectral image classification.

## Datasets Used

- **Salinas**: Contains 224 spectral bands and represents agricultural land.
- **Indian Pines**: Contains 220 spectral bands with agricultural land from Indiana.
- **Pavia Center**: Contains 102 spectral bands representing urban areas in Italy.

The datasets are processed to reduce dimensionality using **Principal Component Analysis (PCA)**, followed by resizing and **One-Hot Encoding** for segmentation tasks.

## Key Features

- **Semantic Segmentation**: Classifies each pixel in the image into predefined classes.
- **U-Net Architecture**: Deep CNN for effective segmentation with encoder-decoder structure and skip connections.
- **Evaluation Metric**: Uses **Intersection over Union (IoU)** to measure segmentation accuracy.

## Requirements

- Python 3.x
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

