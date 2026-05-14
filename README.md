# Facial Emotion Recognition System

A Deep Learning-based Facial Emotion Recognition system built using TensorFlow, Keras, OpenCV, and MobileNetV2 Transfer Learning architecture. The project classifies human facial expressions into seven emotion categories using computer vision and deep learning techniques.

---

# Project Overview

This project focuses on multi-class facial emotion classification using the CK+ dataset. A pretrained MobileNetV2 model is used as the feature extractor to improve generalization and performance on a relatively small dataset.

The system performs:
- Image preprocessing
- Data augmentation
- Transfer learning
- Emotion classification
- Model evaluation using classification metrics

---

# Emotion Classes

The model classifies facial expressions into the following categories:

- Anger
- Contempt
- Disgust
- Fear
- Happy
- Sadness
- Surprise

---

# Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- MobileNetV2

---

# Dataset

Dataset Used: CK+ (Extended Cohn-Kanade Dataset)

The CK+ dataset contains labeled facial expression images used for emotion recognition research.

Dataset features:
- Grayscale facial images
- Multiple emotion categories
- Human facial expression sequences

---

# Model Architecture

The project uses Transfer Learning with MobileNetV2.

Architecture Flow:

Input Image → Preprocessing → MobileNetV2 → GlobalAveragePooling → Dense Layers → Softmax Output

Key Features:
- Transfer Learning
- RGB image preprocessing
- Data augmentation
- Dropout regularization
- Softmax multi-class classification

---

# Data Preprocessing

The following preprocessing techniques were applied:

- Image resizing (96×96)
- RGB conversion
- MobileNetV2 preprocessing
- Data augmentation
  - Rotation
  - Width shift
  - Height shift
  - Horizontal flip

---

# Training Details

- Input Size: 96×96×3
- Batch Size: 32
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Transfer Learning Model: MobileNetV2
- Validation Split: 20%

---

# Model Performance

The model achieved approximately:

- 80% Validation Accuracy

Evaluation Metrics:
- Precision
- Recall
- F1-score
- Confusion Matrix

The model performed particularly well on:
- Happy
- Surprise
- Disgust

---

# Future Improvements

- Real-time webcam emotion detection
- Streamlit deployment
- Grad-CAM visualization
- Fine-tuning MobileNetV2 layers
- Support for larger emotion datasets

---

# Results

The project demonstrates the effectiveness of transfer learning for facial emotion recognition on small datasets. MobileNetV2 significantly improved classification performance compared to training CNN models from scratch.

---

# Author

Harsh Agarwal

B.Tech CSE | Machine Learning & Deep Learning Enthusiast

