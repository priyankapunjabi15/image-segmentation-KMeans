# Image Segmentation using K-Means Clustering

## Overview
This repository contains a computer vision project focused on color-based image segmentation. It utilizes K-means clustering within the LAB color space to group pixels based on perceptual similarity, rather than raw RGB values, resulting in highly accurate object extraction.

## Features
* **LAB Color Space Conversion:** Transforms images from RGB to LAB color space to separate lightness from color information, improving clustering accuracy.
* **K-Means Clustering:** Implements unsupervised machine learning via Scikit-Learn to automatically identify and group dominant color regions.
* **Morphological Operations:** Applies morphological dilation to clean up noise, fill gaps, and refine the boundaries of the segmented regions.

## Technologies Used
* **Python**
* **OpenCV** (cv2)
* **Scikit-Learn**
* **NumPy**
* **Matplotlib**

## Repository Structure
* `image_segmentation.ipynb`: Core implementation and visualization.
* `data/`: Contains the input, output and test images used.
* `Report.pdf`: Detailed documentation and analysis of the segmentation results.
