# ✈️ Aircraft Image Classification using CNN

This project presents a Convolutional Neural Network (CNN) model for classifying aircraft images into **9 distinct categories**. The dataset contains over **21,000 images** of various aircraft types collected from publicly available sources.

---

## 📁 Dataset Overview

- **Total Categories**: 9 aircraft types
- **Training Set**: ~2,000 images per class
- **Test Set**: ~55 images per class
- **Image Format**: JPG, 224x224 pixels
- **Total Images**: ~21,900

### 📚 Aircraft Categories

1. Delta Wing  
2. Biplane  
3. Seaplane  
4. Quadcopter  
5. Helicopter  
6. Forward-Swept Wing  
7. Passenger Plane  
8. Fighter  
9. Paraglider

---

## 📦 Data Source

The dataset was curated from **publicly available aircraft images on the Internet**, gathered for educational and research purposes. Images were manually sorted and labeled into the 9 aircraft categories listed above.

📌 *If you're the original creator of any image and wish to be credited or have it removed, please reach out via the issues tab or contact info in this repo.*

> 🔗 (Optional) **Download Dataset**: [Aircraft Classification Dataset](https://www.kaggle.com/datasets/sleppyfish/aircraft-classification-dataset?select=train)


## 🚀 Model & Results

A deep learning model based on **Convolutional Neural Networks (CNN)** was trained on the dataset using TensorFlow/Keras.

### ✅ Final Test Accuracy: **97%**

- Model Type: Custom CNN
- Input Size: 224x224x3
- Optimizer: Adam
- Loss Function: sparse categorical crossentropy
- Metrics: Accuracy
- Epochs: 50 
- Batch Size: 128

---
