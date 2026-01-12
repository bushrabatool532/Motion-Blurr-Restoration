# Motion Blur Restoration

This project demonstrates motion blur restoration using image processing techniques.

## Overview
This notebook implements motion blur restoration for uniformly blurred images using multiple methods including Unsharp Masking, Simple Deconvolution, and other enhancement techniques.

# Files
- `motion_blur_restoration.ipynb` - Main Jupyter notebook with implementation
- `original_blurred.jpg` - Original motion-blurred image
- `restored_final.jpg` - Final restored image
- `comparison_before_after.jpg` - Side-by-side comparison

# Methods Used
1. Unsharp Masking (Best Result)
2. Simple Deconvolution
3. Bilateral Filtering + Sharpening
4. Adaptive Sharpening
5. Frequency Domain Filtering

# Results
Unsharp Masking provided the best restoration with minimal artifacts and clear edge enhancement.

#How to Use
1. Open the notebook in Google Colab
2. Upload your motion-blurred image
3. Run all cells
4. Download the restored image

# Requirements
OpenCV
NumPy
Matplotlib
