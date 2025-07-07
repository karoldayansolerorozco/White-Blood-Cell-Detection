# 🧪 White Blood Cell Detection in Microscopy Images

This project explores and compares different **image thresholding** and **preprocessing techniques** for the detection of white blood cells (WBCs) in microscopy images.

## 📌 Objective

The main goal is to **evaluate the effectiveness** of multiple image processing methods in terms of:

- 🎯 **Precision**: How accurately WBCs are detected.
- 🛠️ **Robustness**: Performance across various image conditions and qualities.
- 🧩 **Common challenges**: Identifying limitations and proposing improvements.

## ⚙️ Methods Explored

This project includes the implementation and analysis of:

- Global and adaptive thresholding (e.g., Otsu’s method, Adaptive Gaussian)
- Morphological operations (e.g., erosion, dilation, closing)
- Color space transformations (e.g., RGB, HSV, grayscale)
- Noise reduction and filtering (e.g., median filter, Gaussian blur)
- Contour detection and blob analysis

## 📊 Evaluation Metrics

We evaluate each technique based on:

- Detection accuracy (True Positives / False Positives)
- Processing time and computational cost
- Sensitivity to noise, lighting, and stain variation

## 🧠 Insights & Findings

- Certain preprocessing steps significantly improve thresholding reliability.
- Adaptive methods tend to outperform global thresholding on unevenly lit images.
- Color-based filtering enhances the detection of WBCs when combined with morphological operations.


