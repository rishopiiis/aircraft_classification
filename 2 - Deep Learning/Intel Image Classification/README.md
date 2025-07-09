# 🧠 Intel Image Classification using CNN

This project focuses on building a Convolutional Neural Network (CNN) to classify natural scene images into six distinct categories using the **Intel Image Classification** dataset.

---

## 📂 About the Dataset

- Source: [Intel Image Classificatio](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- Description: 25,000+ images (150x150 resolution)
- Classes:
  
0 - Buildings

1 - Forest

2 - Glacier

3 - Mountain

4 - Sea

5 - Street


- Data Split:
- **Training**: ~14,000 images  
- **Testing**: ~3,000 images  
- **Prediction**: ~7,000 images  

---

## 🧠 Project Overview

- **Goal**: Classify natural scenes from images into one of 6 categories.
- **Model**: Custom Convolutional Neural Network (CNN)
- **Framework**: TensorFlow / Keras
- **Data Augmentation**: ❌ Not used
- **Final Accuracy**: ✅ Achieved **83%** on test data

---

📊 Results

| Metric        | Value                                              |
| ------------- | -------------------------------------------------- |
| Test Accuracy | 83%                                                |
| Loss Curve    | Included in training logs                          |
| Model Summary | CNN with Conv2D, MaxPooling, Dropout, Dense layers |
