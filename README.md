# Image Classification using TensorFlow

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Accuracy](https://img.shields.io/badge/Accuracy-88.00%25-28A745?style=for-the-badge) ![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

A Convolutional Neural Network (CNN) project for classifying natural scene images into six categories using TensorFlow and Keras. The model was trained on the Intel Image Classification dataset and exported for deployment on TensorFlow, TensorFlow Lite, and TensorFlow.js.

---

## Preview

### Training History

![Training History](assets/training-history.png)

### Sample Prediction

**Predicted Class:** Glacier

**Confidence:** **97.64%**

![Sample Prediction](assets/sample-prediction.png)

---

# Overview

This project demonstrates an end-to-end Deep Learning workflow for image classification.

The pipeline includes:

- Dataset preprocessing
- Data augmentation
- CNN model development
- Model training
- Performance evaluation
- Multiple deployment exports
- Sample inference

The trained model can be deployed on desktop, web browsers, mobile devices, and embedded systems.

---

# Dataset

Dataset:

**Intel Image Classification Dataset**

Number of classes:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

---

# Model Performance

| Metric | Value |
|:------|------:|
| Test Accuracy | **88.00%** |
| Test Loss | **0.3406** |
| Number of Classes | **6** |
| Framework | **TensorFlow 2.20** |

The model achieved **88% classification accuracy** on the testing dataset while maintaining a relatively low validation loss, indicating good generalization performance.

---

# CNN Architecture

The implemented CNN consists of:

- 4 Convolutional Layers
- ReLU Activation
- MaxPooling Layers
- Flatten Layer
- Dense Layer (512 Neurons)
- Dropout (0.3)
- Softmax Output Layer

---

# Features

- CNN-based Image Classification
- Image Data Augmentation
- Training & Validation Visualization
- Model Evaluation
- TensorFlow SavedModel Export
- TensorFlow Lite Export
- TensorFlow.js Export
- Sample Prediction
- Deployment-ready Models

---

# Exported Models

| Format | Description |
|:------|:------------|
| TensorFlow SavedModel | Production deployment |
| TensorFlow Lite (.tflite) | Android / Mobile deployment |
| TensorFlow.js | Browser inference |

---

# Project Structure

```text
image-classification-tensorflow/
│
├── assets/
│   ├── training-history.png
│   └── sample-prediction.png
│
├── images/
│
├── models/
│   ├── saved_model/
│   ├── tfjs_model/
│   └── tflite/
│
├── notebook.ipynb
├── requirements.txt
├── LICENSE
└── README.md
```

---

# Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

# Future Improvements

- Improve classification accuracy beyond 90%
- Implement Transfer Learning (MobileNetV2 / EfficientNet)
- Hyperparameter Optimization
- Model Quantization
- Web Deployment using TensorFlow.js
- Android Deployment using TensorFlow Lite

---

# Author

**Miqdad Badjuber**

GitHub:
https://github.com/miqdadbadjuber

---

### If you find this project useful, consider giving it a ⭐ on GitHub.
