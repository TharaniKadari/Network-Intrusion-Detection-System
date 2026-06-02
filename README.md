# 🔐 Network Intrusion Detection System

## Overview

This project implements a Deep Learning-based Network Intrusion Detection System (NIDS) to identify malicious network activities and cyber attacks from network traffic data.

The system analyzes network traffic patterns and classifies them as either normal or intrusive, helping improve cybersecurity monitoring and threat detection.

---

## Dataset

Dataset Source:

https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection

The dataset contains network traffic records with multiple features representing network behavior and attack patterns.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* TensorFlow
* Keras
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Data Encoding
5. Deep Learning Model Development
6. Model Training
7. Performance Evaluation
8. Intrusion Classification

---

## Model Evaluation

The project evaluates multiple optimization algorithms, including:

* Adam
* RMSProp
* Adagrad
* Adadelta
* FTRL
* SGD
* Adamax
* Nadam

Performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results

The deep learning model achieved high classification performance in detecting malicious network traffic and distinguishing it from normal traffic.

Key observations:

* High classification accuracy across multiple optimizers
* Strong intrusion detection capability
* Low false positive and false negative rates
* Consistent performance across evaluation metrics

---

## Visualizations

### Dataset Distribution

![Dataset Distribution](images/class_distribution.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Optimizer Performance Comparison

![Optimizer Comparison](images/model_accuracy_comparison.png)

---

## Repository Structure

```text
Network-Intrusion-Detection-System
│
├── images
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   └── model_accuracy_comparison.png
│
├── notebooks
│   └── Network_Intrusion_Detection.ipynb
│
├── results
│   └── README.md
│
├── requirements.txt
│
└── README.md
```

---

## Installation

```bash
git clone <repository-url>
cd Network-Intrusion-Detection-System
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
Network_Intrusion_Detection.ipynb
```

and run all cells sequentially.

---

## Future Enhancements

* Real-time intrusion detection
* Deployment as a web application
* Cloud-based monitoring integration
* Advanced deep learning architectures
* Live network traffic analysis

---

## Author

Kadari Tharani

Artificial Intelligence & Machine Learning Engineering Student
