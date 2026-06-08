# Rice Leaf Disease Classification Framework

# Machine Learning Coursework - Phase II:
# Quick Links:

Kaggle: https://www.kaggle.com/code/amulyajm1/fork-of-notebook01

Dataset: https://www.kaggle.com/competitions/paddy-disease-classification/data

## Project Overview

This project develops an automated rice leaf disease classification system using Deep Learning techniques. The objective is to identify and classify rice plant diseases from leaf images using Convolutional Neural Networks (CNNs) and Transfer Learning models.

Early detection of rice diseases helps farmers reduce crop losses, improve productivity, and support precision agriculture practices. This project compares a custom CNN architecture with state-of-the-art transfer learning models to evaluate classification performance.

---

## Project Information

**Models:** Custom CNN | EfficientNetB0 | MobileNetV2

**Dataset:** Paddy Disease Classification Dataset

**Task:** 10-Class Rice Leaf Disease Classification

**Framework:** TensorFlow / Keras

**Project Type:** Supervised Deep Learning (Image Classification)

---

## Dataset

### Dataset Source

Kaggle Paddy Disease Classification Dataset

https://www.kaggle.com/competitions/paddy-disease-classification

### Disease Classes

1. bacterial_leaf_blight
2. bacterial_leaf_streak
3. bacterial_panicle_blight
4. blast
5. brown_spot
6. dead_heart
7. downy_mildew
8. hispa
9. normal
10. tungro

### Dataset Characteristics

- RGB leaf images
- 10 disease categories
- Multi-class image classification problem
- Real-world agricultural disease dataset

---

## Research Objectives

- Develop a custom CNN model for rice disease classification.
- Apply transfer learning using EfficientNetB0 and MobileNetV2.
- Compare model performance across multiple evaluation metrics.
- Analyze class-wise classification effectiveness.
- Generate publication-quality figures and tables.

---

## Research Questions

1. Can deep learning accurately classify rice leaf diseases?
2. How does transfer learning compare with a custom CNN model?
3. Which disease categories are most difficult to classify?
4. Does data augmentation improve model generalization?
5. What are the precision, recall, and F1-scores for each class?
6. Which model achieves the highest overall accuracy?
7. What model provides the best balance between accuracy and computational cost?

---

## Methodology

### 1. Data Preprocessing

- Image resizing (224 × 224)
- Image normalization
- Label encoding
- Dataset splitting

### 2. Data Augmentation

- Rotation
- Horizontal flipping
- Zooming
- Width shifting
- Height shifting

### 3. Model Development

#### Custom CNN

- Convolution Layers
- ReLU Activation
- Max Pooling
- Dropout Regularization
- Fully Connected Layers
- Softmax Output Layer

#### Transfer Learning Models

- EfficientNetB0
- MobileNetV2

### 4. Model Evaluation

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```text
Rice-Leaf-Disease-Classification/
│
├── Rice-Leaf-Disease-Classification.ipynb
│
├── outputs/
│   ├── figures/
│   │   ├── class_distribution.pdf
│   │   ├── cnn_accuracy_curve.pdf
│   │   ├── cnn_loss_curve.pdf
│   │   ├── cnn_confusion_matrix.pdf
│   │   ├── efficientnet_confusion_matrix.pdf
│   │   ├── mobilenet_confusion_matrix.pdf
│   │   └── model_comparison.pdf
│   │
│   ├── tables/
│   │   ├── class_distribution.csv
│   │   ├── cnn_classification_report.csv
│   │   ├── efficientnet_classification_report.csv
│   │   ├── mobilenet_classification_report.csv
│   │   └── model_comparison.csv
│   │
│   └── models/
│       ├── cnn_model.keras
│       ├── efficientnet_model.keras
│       └── mobilenet_model.keras
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook
  

### Programming Language

- Python 3.x

### Libraries

- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- OpenCV

### Development Environment

- Kaggle Notebook
- Jupyter Notebook

---

## Experimental Workflow

1. Dataset Loading
2. Data Exploration
3. Data Preprocessing
4. Data Augmentation
5. CNN Model Training
6. Transfer Learning Model Training
7. Model Evaluation
8. Performance Comparison
9. Result Visualization
10. Exporting Figures and Tables

---

## Results

The performance comparison table will be updated after model training.

| Model | Accuracy |
|---------|---------|
| Custom CNN | 75.70 % |
| EfficientNetB0 | 16.91 % |

---

## Outputs Generated

- model predictions
- trained model results
- evaluation metrics
- sample outputs (images, plots, reports)
- final exported files
  

### Figures

- Class Distribution Plot
- Accuracy Curves
- Loss Curves
- Confusion Matrices
- Model Comparison Charts

### Tables

- Dataset Summary
- Classification Reports
- Model Performance Comparison

---

### Discussion Section:

The custom CNN achieved a test accuracy of 75.70%, substantially outperforming the EfficientNetB0 implementation (16.91%). The poor performance of EfficientNetB0 is likely attributable to transfer-learning configuration limitations, preprocessing differences, or the inability to utilize pretrained weights during experimentation. Consequently, the custom CNN was selected as the final model for this study.

---

## Future Enhancements

- Grad-CAM Visualization
- Vision Transformers (ViT)
- Ensemble Learning
- Hyperparameter Optimization
- Real-Time Disease Detection System

---

### Clone Repository

```bash
git clone https://github.com/Amulya-jagaluru-manjunath/Rice-Leaf-Disease-Classification-Framework.git
cd Rice-Leaf-Disease-Classification
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

---

## Author

Amulya J M

Machine Learning Project

Rice Leaf Disease Classification Using Deep Learning

2026
