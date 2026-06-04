# Quantum-Classical-Oral-Cancer-Detection
Quantum-Classical Hybrid Deep Learning framework for early oral cancer detection from histopathological images using DenseNet121 and quantum-enhanced feature learning.
# Quantum-Classical Hybrid Deep Learning for Early Oral Cancer Detection from Histopathological Images

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

## Augmentation Parameters Used in Training
<img width="981" height="455" alt="IMG_3375" src="https://github.com/user-attachments/assets/3a9aa918-8641-47e9-9299-766c0a7a65d2" />

## Dataset Split: Train/Validation Distribution
<img width="977" height="240" alt="IMG_3374" src="https://github.com/user-attachments/assets/bf8e6563-c96f-4cea-bf5a-d7b27b2a541a" />

## Development Environment and Tools
<img width="935" height="539" alt="IMG_3373" src="https://github.com/user-attachments/assets/fc4c5e68-e284-4236-b83b-4d87d02ecaab" />

## Hyperparameters for model training 
<img width="973" height="714" alt="image" src="https://github.com/user-attachments/assets/fa40a082-f474-4a20-a669-f489f33a3b0e" />


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
### Performance Metrics of Baseline Models on OSCC Validation Set
<img width="1021" height="367" alt="image" src="https://github.com/user-attachments/assets/83589862-8f7a-4864-87b5-0286896ea85f" />

### Comparative Analysis: Q1-IncepNet vs. All Baselines
<img width="970" height="538" alt="image" src="https://github.com/user-attachments/assets/84220158-8712-49b6-8dd2-8962a45dcbe9" />


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

### FINAL COMPARISON: DenseNet121 vs QI-DenseNet121
<img width="720" height="290" alt="image" src="https://github.com/user-attachments/assets/9ce7698d-2b44-435b-b052-8393abbd7835" />

<img width="815" height="209" alt="image" src="https://github.com/user-attachments/assets/c3900322-5004-420a-b0cc-5d6b6e05c04e" />

### Performance Gain (QI vs Baseline)
<img width="735" height="549" alt="image" src="https://github.com/user-attachments/assets/e7997200-5583-45cc-92d3-c3e24cf05c58" />


### Radar Comparison
<img width="647" height="536" alt="image" src="https://github.com/user-attachments/assets/07f2c32a-9f36-45f3-9211-d5328941ae4f" />

### Per-Class F1-Score Heatmap - All CNN Architrctures
<img width="795" height="575" alt="image" src="https://github.com/user-attachments/assets/96a7d041-a609-4eb8-8459-0ecc7a03eada" />

### AUC-ROC Comparison-- CNN Architectures
<img width="1488" height="742" alt="image" src="https://github.com/user-attachments/assets/4fb0216f-6e0e-4d72-8d73-8c7cbb40a1cf" />

### Precision Curve & Recall Curve
<img width="1600" height="441" alt="image" src="https://github.com/user-attachments/assets/3dc17d10-321a-4b6c-866e-ed1709a28804" />

### Training vs Validation Accuracy & Training vs Validation Loss
<img width="1600" height="440" alt="image" src="https://github.com/user-attachments/assets/a6d0a5f4-45b7-4099-9d3d-c5bf48eeb455" />

## Output Images

<img width="1600" height="896" alt="image" src="https://github.com/user-attachments/assets/80085a6e-2e68-4f3e-b614-7cbbc0167647" />
<img width="1600" height="871" alt="image" src="https://github.com/user-attachments/assets/98794837-bd86-4bc2-9656-5a6a42e9a561" />
<img width="1600" height="890" alt="image" src="https://github.com/user-attachments/assets/37489d29-cc33-4799-8e4b-9da47d6825d0" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c9b47ae1-9c77-4574-950e-7cb9af7205f2" />










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
