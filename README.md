# 🫁 Lung Cancer Classification using Deep Learning (VGG16)

This project builds a deep learning-based image classifier to detect **lung cancer types** — **Benign**, **Malignant**, and **Normal** — from CT scan images using the **VGG16** architecture with transfer learning.

---

## 📂 Project Structure


---

## 🔍 Problem Statement

Classify lung CT scan images into:
- **Benign**
- **Malignant**
- **Normal**

Using a transfer learning approach to improve classification performance on a small dataset.

---

## 🧠 Model Architecture

- **Backbone**: [VGG16](https://arxiv.org/abs/1409.1556) from `timm` library with pretrained ImageNet weights
- **Modified head**: Fully connected layer for 3-class classification
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam

---

## 🔧 Key Features

- Transfer Learning with VGG16
- Evaluation on precision, recall, F1-score, accuracy
- Visualization of training curves
- Confusion matrix for test performance
- Best model saved automatically based on top metrics

---

## 📈 Training Results

- Epochs: 20  
- Batch Size: 16  
- Best Test Accuracy Achieved: **~90%** *(varies based on dataset split and augmentation)*

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix

---

## 🧪 Sample Output

```bash
Epoch 20/20:
Train Loss: 0.23, Accuracy: 92.5%
Validation Loss: 0.31, Accuracy: 89.7%

Test Accuracy of Model = 0.91
