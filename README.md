# Quantum-Classical-Oral-Cancer-Detection
Quantum-Classical Hybrid Deep Learning framework for early oral cancer detection from histopathological images using DenseNet121 and quantum-enhanced feature learning.
# Quantum-Classical Hybrid Deep Learning for Early Oral Cancer Detection from Histopathological Images

<p align="center">
  <img src="images/architecture.png" alt="Model Architecture" width="800"/>
</p>

## Overview

Oral cancer is among the most common and life-threatening cancers worldwide. Early detection plays a critical role in improving patient survival rates and treatment outcomes. Histopathological examination remains the gold standard for diagnosis; however, it is labor-intensive, time-consuming, and highly dependent on expert interpretation.

This project presents a **Quantum-Classical Hybrid Deep Learning Framework** for the automated detection of oral cancer from histopathological images. The proposed model integrates the powerful feature extraction capabilities of **DenseNet121** with **quantum-enhanced learning mechanisms** to improve classification performance and diagnostic reliability.

---

## Problem Statement

Traditional histopathological diagnosis faces several challenges:

* Dependence on highly skilled pathologists
* Large diagnostic workload
* Inter-observer variability
* Delayed diagnosis due to manual analysis

The objective of this research is to develop an intelligent Computer-Aided Diagnosis (CAD) system capable of accurately classifying histopathological images into cancerous and non-cancerous categories using a hybrid quantum-classical architecture.

---

## Objectives

* Develop an automated oral cancer detection system using deep learning.
* Explore the potential of hybrid quantum-classical learning for medical image analysis.
* Improve classification accuracy through quantum-enhanced feature representation.
* Evaluate the effectiveness of the proposed framework using standard performance metrics.
* Contribute towards faster and more reliable oral cancer diagnosis.

---

## Dataset

The model is trained on histopathological oral tissue images categorized into:

* Cancerous Tissue
* Non-Cancerous Tissue

### Preprocessing Steps

* Image resizing
* Pixel normalization
* Data augmentation
* Dataset balancing
* Train-validation-test split

---

## Proposed Architecture

### QI-DenseNet121 (Quantum-Inspired DenseNet121)

The proposed architecture combines classical deep learning with quantum-inspired computation.

### Classical Components

* DenseNet121 Backbone
* Global Average Pooling
* Batch Normalization
* Dropout Regularization
* Dense Classification Layers

### Quantum Components

* Quantum Feature Embedding
* Variational Quantum Circuit (VQC)
* Quantum Measurement Layer

The hybrid architecture leverages deep feature extraction from DenseNet121 and quantum feature transformations to improve discrimination between cancerous and non-cancerous tissue patterns.

---

## System Workflow

```text
Histopathological Images
            │
            ▼
      Preprocessing
            │
            ▼
     Data Augmentation
            │
            ▼
       DenseNet121
            │
            ▼
     Feature Extraction
            │
            ▼
     Quantum Embedding
            │
            ▼
 Variational Quantum Circuit
            │
            ▼
     Quantum Measurement
            │
            ▼
      Dense Layers
            │
            ▼
        Prediction
```

---

## Repository Structure

```text
Quantum-Classical-Oral-Cancer-Detection/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── Oral.ipynb
│
├── models/
│   └── QI_DenseNet121_best.keras
│
├── images/
│   ├── workflow.png
│   ├── architecture.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── accuracy_curve.png
│   └── loss_curve.png
│
├── results/
│   └── performance_metrics.csv
│
└── docs/
    └── project_report.pdf
```

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-Learn
* PennyLane
* Jupyter Notebook

---

## Evaluation Metrics

The proposed model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## Results

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | XX.XX% |
| Precision | XX.XX% |
| Recall    | XX.XX% |
| F1-Score  | XX.XX% |
| ROC-AUC   | XX.XX% |

> Replace the above values with the final results obtained from your trained model.

---

## Key Contributions

* Hybrid Quantum-Classical Learning Framework
* DenseNet121-Based Feature Extraction
* Quantum Feature Representation
* Automated Histopathological Image Analysis
* Early Oral Cancer Detection
* Medical AI Research Application

---

## Visual Results

### Model Architecture

![Architecture](images/architecture.png)

### Training Accuracy

![Accuracy](images/accuracy_curve.png)

### Training Loss

![Loss](images/loss_curve.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve

![ROC Curve](images/roc_curve.png)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Quantum-Classical-Oral-Cancer-Detection.git
```

Move into the project directory:

```bash
cd Quantum-Classical-Oral-Cancer-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/Oral.ipynb
```

Run all cells to train and evaluate the model.

---

## Future Scope

### Explainable AI Integration

* Grad-CAM
* SHAP Analysis
* Attention Visualization

### Clinical Deployment

* Web-Based Diagnostic Platform
* Hospital Integration
* Decision Support System

### Advanced Classification

* Multi-Class Oral Lesion Classification
* Cancer Stage Prediction
* Severity Assessment

### Federated Learning

* Privacy-Preserving Collaborative Learning
* Multi-Hospital Training Framework

### Quantum Hardware Deployment

* Implementation on Real Quantum Processors
* Quantum Advantage Evaluation

---

## Research Impact

This work demonstrates the potential of combining quantum-inspired computation with deep learning for medical image analysis. The proposed framework aims to support pathologists by providing a fast, reliable, and scalable diagnostic assistance system for early oral cancer detection.

---



---

## License

This project is licensed under the MIT License.

---

⭐ If you find this project useful, consider giving the repository a star. It helps others discover the work and supports future development.
