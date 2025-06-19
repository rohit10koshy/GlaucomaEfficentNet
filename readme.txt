# 👁️ Glaucoma Detection using EfficientNet

> **A deep learning project for automated *glaucoma detection*** from retinal fundus images  
> using **EfficientNet** and Keras.  
> 🧪 This model uses guided filtering, advanced data augmentation, and transfer learning  
> to perform accurate binary classification: `Glaucoma` vs `Non-Glaucoma`.

---

## 📌 Overview

This repository contains all the code and documentation required to detect **glaucoma** from eye fundus images using a deep CNN architecture.

- ✅ **Base Model**: EfficientNet (pretrained on ImageNet)
- 🖼️ **Input**: Retinal fundus images from a Kaggle dataset
- 🧪 **Techniques**:
  - Guided image enhancement
  - Real-time data augmentation
  - Learning rate scheduling
  - Early stopping
- 📊 **Evaluation**: Accuracy, ROC Curve, Confusion Matrix, and F1-Score

---

## 📁 Sample Preview (optional)

> You can include before/after image preprocessing here:

| Original Image | After Preprocessing |
|----------------|---------------------|
| ![](images/original.jpg) | ![](images/filtered.jpg) |

---

## 📥 Quick Access

- 🔗 [View Notebook](./GlaucomaEfficentNet.ipynb)
- 📦 [Trained Model (H5)](./saved_model.h5)
- 📂 [Dataset Folder Structure](#dataset)

---
