# Computer Vision Course Labs

This repository contains five labs for the Computer Vision course, covering various essential topics in the field. Each lab provides practical exercises and examples to help understand and implement different computer vision techniques.

## Lab Topics

1. [Image Classification](#image-classification)
2. [Image Stitching](#image-stitching)
3. [Image Matching](#image-matching)
4. [Image Segmentation](#image-segmentation)
5. [Feature Extraction](#feature-extraction)

### Image Classification

In this lab, we explore the concepts of image classification using convolutional neural networks (CNNs). The lab includes:
- Data preprocessing and augmentation
- Building and training a CNN model
- Evaluating model performance
- Fine-tuning a pre-trained model using transfer learning

### Image Stitching

This lab focuses on image stitching techniques to create panoramic images. The lab covers:
- Feature detection and matching
- Homography estimation
- Image warping and blending
- Creating a seamless panorama

### Image Matching

In this lab, we delve into image matching using various feature descriptors and keypoint detectors. The lab includes:
- Keypoint detection using SIFT, ORB, and BRISK
- Feature descriptor extraction
- Matching features between images
- Geometric verification using RANSAC

### Image Segmentation

This lab covers the fundamental techniques for image segmentation. The lab includes:
- Image thresholding
- Edge detection
- Region-based segmentation
- Semantic segmentation using deep learning models

### Feature Extraction

The feature extraction lab demonstrates various methods to extract and visualize features from images. The lab covers:
- Using the DELF (DEep Local Features) model for feature extraction
- Visualizing keypoints and descriptors
- Matching features between images
- Evaluating feature matching performance

## How to Use

Each lab is contained in its own directory with the following structure:

To get started with a lab:
1. Navigate to the respective lab directory.
2. Follow the instructions in the `README.md` file inside the lab directory.
3. Open the Jupyter notebooks to start the exercises.

## Prerequisites

Make sure you have the following installed:
- Python 3.6 or higher
- TensorFlow
- OpenCV
- Matplotlib
- NumPy
- PIL (Python Imaging Library)
- TensorFlow Hub

You can install the required packages using `pip`:

```sh
pip install tensorflow opencv-python matplotlib numpy pillow tensorflow_hub
