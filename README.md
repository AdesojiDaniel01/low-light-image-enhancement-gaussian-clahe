# A Novel Lightweight Framework for Low-Light Image Enhancement via Gaussian Denoising and CLAHE

This repository contains the implementation used in the thesis titled:

“A Novel Lightweight Framework for Low-Light Image Enhancement via Gaussian Denoising and Contrast-Limited Adaptive Histogram Equalization (CLAHE).”

## Project Overview
This work proposes a lightweight image enhancement framework that combines:
- Gaussian denoising for noise reduction
- CLAHE for contrast enhancement

The method is applied to both grayscale and color images (LAB color space).

## Features
- Gaussian denoising (grayscale and color)
- CLAHE-based enhancement
- Image quality evaluation using:
  - PSNR
  - SSIM
  - MSE
  - LOE
- Visualization:
  - Bar charts
  - Histograms
- Supplementary VGG16-based validation

## Tools & Libraries
- Python
- OpenCV
- NumPy
- Matplotlib
- Pandas
- scikit-image
- TensorFlow / Keras

## How to Run
1. Open the notebook in Google Colab
2. Upload an input image
3. Run all cells
4. Outputs will be saved automatically

## Note
This code supports the methodology presented in Chapter 3 and the results discussed in Chapter 4 of the thesis.

## Author
Daniel Adesoji, M.Sc. Computer And Information Science, Fort Hays State University, KS, USA.
