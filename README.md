# ECG-Arrhythmia-Detection
# 🫀 ECG Arrhythmia Detection Using Deep Learning (Synthetic Data)

This project builds a Convolutional Neural Network (CNN) model to classify ECG signals into multiple classes, including **Normal**, **Arrhythmia**, and abnormalities such as **ST Depression**, **ST Elevation**, and **T Wave Inversion** — using **synthetically generated ECG signals**.

## 💡 Motivation

Heart arrhythmias are irregular heartbeats that can lead to serious health risks such as strokes or sudden cardiac arrest. Timely and accurate detection is crucial. This project aims to create a cost-effective, automated system using machine learning to classify ECG signals for real-time screening and monitoring.

## 🧪 Features

- 📈 Synthetic ECG signal generation with labeled abnormalities:
  - Normal
  - Arrhythmia
  - ST Depression
  - ST Elevation
  - T Wave Inversion
- 🧠 Deep CNN-based classification model using TensorFlow/Keras
- 🧪 High test accuracy (~97%) on synthetic validation dataset
- 📦 Model saving and reusability via `.h5` file
- 📊 Confusion matrix and classification report for evaluation

---

---

## ✅ Future Scope

- 🔄 Replace synthetic data with real-world ECG datasets (e.g., MIT-BIH Arrhythmia Database)
- 📱 Deploy model on mobile/wearable devices for real-time heart monitoring
- 🧠 Use advanced models like LSTM/Transformers for sequence modeling
- 🧪 Include multi-lead ECG signal support (12-lead clinical ECGs)
- 🧹 Add noise robustness, data augmentation, and domain adaptation
- ☁️ Integrate into telemedicine platforms for remote diagnostics
- 📉 Improve interpretability with saliency maps or attention mechanisms

---

## 📊 Results Summary

- **Training Accuracy:** Up to 95%+ on synthetic ECG signals
- **Validation Accuracy:** Reached 97.3% on held-out synthetic test set
- **Precision, Recall, F1-Score:** All ~96–98% for each class
- **Model Size:** ~915 KB (lightweight for deployment)
- **Confusion Matrix:**


