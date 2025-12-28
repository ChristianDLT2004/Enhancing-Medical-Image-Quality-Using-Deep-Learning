# Enhancing Medical Image Quality Using Deep Learning (SRCNN & VDSR)

## Overview
This project implements and compares deep learning–based super-resolution models to enhance low-resolution medical images. Specifically, it evaluates **SRCNN** and **VDSR** convolutional neural networks on chest X-ray datasets.

The focus is on understanding tradeoffs between reconstruction quality and computational cost under constrained training settings.

## Dataset
- Public chest X-ray datasets (Kaggle)
- Images converted to grayscale and resized for efficient experimentation

## Methodology
- Simulated low-resolution images via downsampling and upscaling
- Implemented SRCNN and a reduced-depth VDSR architecture
- Trained models using mean squared error loss
- Evaluated reconstruction quality using:
  - **PSNR (Peak Signal-to-Noise Ratio)**
  - **SSIM (Structural Similarity Index)**
- Benchmarked performance across multiple datasets

## Results
- VDSR consistently achieved higher PSNR and SSIM scores across datasets
- SRCNN trained faster but exhibited lower reconstruction fidelity
- Results highlight the tradeoff between image quality and computational cost

## Technologies
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- scikit-image
- Matplotlib

## Notes
This project emphasizes **model comparison, evaluation metrics, and computational constraints**, rather than clinical diagnosis or deployment.
