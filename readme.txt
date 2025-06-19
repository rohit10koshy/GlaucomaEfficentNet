# Glaucoma EfficientNet Detection 🚨

**Automatic glaucoma detection** using transfer learning with EfficientNet on a Kaggle eye-fundus dataset.


---

## Overview

This repository contains Jupyter notebooks and scripts for detecting glaucoma from retinal fundus images. The core model is based on **EfficientNet** (a state-of-the-art CNN with compound scaling) :contentReference[oaicite:1]{index=1}. The pipeline includes data augmentation, training, and evaluation.

---

## Dataset

- ⚙️ **Source**: Kaggle (“Glaucoma Detection”)  
- **Contents**: Labeled fundus images (glaucoma vs normal)  
- You must download and place the dataset under `data/raw/`.

---

## Approach

### Preprocessing & Augmentation

From the `.ipynb`, the following techniques are applied:

- Horizontal and vertical flipping  
- Brightness/contrast adjustments  
- CLAHE (Contrast Limited Adaptive Histogram Equalization)  
- Channel multipliers, random crops, and scaling  

These augmentations aim to improve model generalization.

### Model Architecture

- **Base model**: EfficientNet (B0–B7 as chosen via training) :contentReference[oaicite:2]{index=2}  
- Transfer learning: Pretrained weights + custom output layer for binary classification  

---

## Usage 🚀

1. Clone the repo:
   ```bash
   git clone https://github.com/rohit10koshy/GlaucomaEfficentNet.git
   cd GlaucomaEfficentNet
