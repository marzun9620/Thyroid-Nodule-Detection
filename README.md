# Thyroid Nodule Detection with Image Processing Pipeline

This project demonstrates an automated method for detecting and analyzing thyroid nodules from ultrasound images. The pipeline consists of multiple image processing steps, including noise reduction, morphological operations, edge detection, thresholding, and texture feature extraction.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Pipeline Steps](#pipeline-steps)
- [Examples](#examples)
- [Feature Extraction](#feature-extraction)
- [License](#license)

## Introduction

This project aims to detect thyroid nodules using various image processing techniques. The steps include filtering, segmentation, and feature extraction, helping radiologists or researchers analyze the nodules for potential anomalies.

## Features
- **Noise Reduction**: Gaussian blur is applied to reduce noise from ultrasound images.
- **Morphological Operations**: Erosion and dilation are used to highlight the regions of interest (ROIs).
- **Edge Detection**: Canny edge detection is used to preserve the edges.
- **Image Enhancement**: Histogram equalization is used to enhance the image contrast.
- **Thresholding**: Otsu's thresholding is used for optimal image segmentation.
- **Texture Analysis**: Grey Level Co-occurrence Matrix (GLCM) method is applied for texture feature extraction.
- **ROI Extraction and Visualization**: ROIs are extracted, and their contours are visualized.

## Requirements

Ensure you have the following Python libraries installed:
```bash
opencv-python
numpy
matplotlib
scikit-image
scipy
