# PCA + kNN for Handwritten Digit Recognition

This project implements a **Principal Component Analysis (PCA)** + **k-Nearest Neighbors (kNN)** classifier for digit recognition.  
It demonstrates dimensionality reduction (PCA) and pattern classification (kNN) on standard datasets.

---

## 📌 Overview
- **PCA**: Reduces feature space while preserving variance.  
- **kNN**: Classifies digits based on nearest neighbors in reduced space.  
- **Dataset**:
  - [sklearn digits dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_digits_last_image.html) (8x8 images)  
  - [MNIST dataset](http://yann.lecun.com/exdb/mnist/) (28x28 images)  

---

## ⚙️ Requirements
Install dependencies:
```bash
pip install numpy scikit-learn matplotlib joblib
