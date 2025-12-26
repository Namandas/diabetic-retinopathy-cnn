# Diabetic Retinopathy Detection using CNN

## 🧠 Project Overview

This project focuses on the automated **detection and classification of Diabetic Retinopathy (DR)** from retinal fundus images using **Convolutional Neural Networks (CNNs)**. The work explores advanced preprocessing techniques and attention-based model improvements to enhance accuracy and robustness, particularly in the presence of class imbalance.

---

## 📌 Key Contributions

### 🏥 Image Preprocessing
- Applied **CLAHE (Contrast Limited Adaptive Histogram Equalization)** to enhance contrast and retinal vessel visibility.
- Implemented **Ben Graham normalization** to standardize illumination across fundus images.
- Achieved approximately **50% reduction in training time** due to improved feature clarity.

### 🧠 Model Enhancements
- Integrated **channel attention** and **spatial attention** mechanisms to focus on clinically relevant regions.
- Added **Squeeze-and-Excitation (SE) blocks** for adaptive channel-wise feature recalibration.
- Used **Focal Loss** to effectively address severe class imbalance across DR classes.

### 🎯 Performance Improvements
- Baseline CNN with attention achieved **~81% accuracy**.
- Improved to **~85% accuracy** after incorporating SE blocks and focal loss.

---

## ⚙️ Tech Stack

```bash
Python 3.8+
TensorFlow / Keras
OpenCV
NumPy
Pandas
Matplotlib
