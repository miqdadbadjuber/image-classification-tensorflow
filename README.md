# Image Classification using TensorFlow

A Convolutional Neural Network (CNN) project for classifying natural scene images into six natural scene categories using TensorFlow and Keras.

## Overview

This project was developed as an end-to-end image classification pipeline using TensorFlow.

The model was trained on the Intel Image Classification dataset and exported into multiple deployment formats, including TensorFlow SavedModel, TensorFlow Lite, and TensorFlow.js.

## Dataset

**Classes**

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

## Features

- CNN-based image classification
- Data augmentation
- Model evaluation
- Training history visualization
- TensorFlow SavedModel export
- TensorFlow Lite (TFLite) export
- TensorFlow.js export
- Sample image prediction

## Project Structure

```text
image-classification-tensorflow/
├── assets/
├── images/
├── models/
│   ├── saved_model/
│   ├── tfjs_model/
│   └── tflite/
├── notebook.ipynb
├── requirements.txt
└── README.md
```

## Model Performance

| Metric | Value |
| :------ | ----: |
| Test Accuracy | **88.00%** |
| Test Loss | **0.3406** |

The model achieved **88.00% accuracy** on the test dataset.

## Model Architecture

The CNN model consists of:

- 4 Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense (512 neurons, ReLU)
- Dropout (0.3)
- Output layer (Softmax, 6 classes)

## Exported Models

The trained model is available in three deployment formats.

| Format | Purpose |
| :------ | :------ |
| TensorFlow SavedModel | TensorFlow deployment |
| TensorFlow Lite (.tflite) | Mobile & Edge devices |
| TensorFlow.js | Browser inference |

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Future Improvements

- Improve classification accuracy
- Apply Transfer Learning (MobileNetV2 / EfficientNet)
- Hyperparameter tuning
- Web deployment using TensorFlow.js
- Android deployment using TensorFlow Lite

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
