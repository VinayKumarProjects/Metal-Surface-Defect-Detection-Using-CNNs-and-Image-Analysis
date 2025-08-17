# Metal-Surface-Defect-Detection-Using-CNNs-and-Image-Analysis
Metal surface defect detection using CNN and image analysis. Classifies six defect types from grayscale images with 92% accuracy. Includes data preprocessing, augmentation, and performance evaluation. Built with TensorFlow, OpenCV, NumPy, and Matplotlib for automated quality inspection.

---

## Overview

This project automates metal surface defect detection to improve industrial quality inspection. Using grayscale images and a custom CNN (or MobileNetV2), it classifies six common types of surface defects.

---

## Defect Categories

The model can detect the following six types of defects:

- 🟤 **Rolled-in Scale (RS)**
- 🟪 **Patches (Pa)**
- 🔵 **Crazing (Cr)**
- ⚫ **Pitted Surface (PS)**
- 🟥 **Inclusion (In)**
- ⚪ **Scratches (Sc)**

---

## Dataset

- **Source**: [NEU Surface Defect Database (via Kaggle)](https://www.kaggle.com/code/ysnyldrms/neu-surface-defect-mobilenetv2/input)
- **Authors**: Kechen Song and Yunhui Yan
- **Total Images**: 1,800 grayscale images
  - 300 images per defect class
  - Split:
    - **Training**: 240 images/class
    - **Testing**: 60 images/class

---

## Tech Stack

- **Model**: Custom CNN / MobileNetV2
- **Languages**: Python
- **Libraries**:
  - TensorFlow / Keras
  - OpenCV
  - NumPy
  - Matplotlib

---

## Features

- ✅ Image preprocessing (resize, normalization, grayscale)
- ✅ Data augmentation (rotation, flip, zoom)
- ✅ Model training & evaluation pipeline
- ✅ Confusion matrix and accuracy visualization
- ✅ Modular & clean code structure

---
