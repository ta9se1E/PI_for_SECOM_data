
# Semiconductor Manufacturing Data Analysis
English | [日本語](README_JP.md)
## Overview

This repository documents my study and experiments on **data analysis for manufacturing processes**, focusing on semiconductor production data.

The goal of this project is to develop practical skills in:

* Industrial data analysis
* Multivariate sensor data processing
* Fault detection and yield prediction
* Machine learning for manufacturing processes

This repository serves as a **learning log and research notebook** while exploring real-world industrial datasets.

---

## Dataset

This project uses the **SECOM dataset**, a publicly available semiconductor manufacturing dataset.

Dataset source:
UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/179/secom

Dataset characteristics:

* 1567 samples
* 590 sensor features
* Pass / Fail label indicating manufacturing quality

The dataset represents **sensor measurements collected from a semiconductor manufacturing process**.

⚠️ Note:
The dataset itself is **not included in this repository**.
Please download it directly from the official source.

---

## Project Goals

The objectives of this study are:

1. Understand characteristics of industrial sensor data
2. Practice preprocessing techniques for manufacturing data
3. Explore machine learning methods for fault detection
4. Investigate feature importance in semiconductor processes
5. Build a foundation for **process informatics and industrial AI**

---

## Analysis Plan

The following analysis steps are planned:

### 1. Data Exploration

* Missing value analysis
* Sensor distribution visualization
* Correlation analysis
* Principal Component Analysis (PCA)

### 2. Data Preprocessing

* Handling missing values
* Removing constant sensors
* Feature scaling
* Dimensionality reduction

### 3. Machine Learning Models

* Random Forest
* XGBoost
* LightGBM

Goal: **Predict pass/fail results from sensor data**

### 4. Explainable AI

* Feature importance
* SHAP analysis
* Identification of key sensors affecting quality

---

## Repository Structure

```
project/
│
├─ data/
│   └─ dataset_download.md
│
├─ notebooks/
│   └─ exploratory_analysis.ipynb
│
├─ src/
│   ├─ preprocessing.py
│   ├─ model_training.py
│   └─ evaluation.py
│
└─ README.md
```

---

## Learning Focus

This project focuses on developing knowledge in:

* Industrial Machine Learning
* Process Informatics
* Multivariate Time Series Analysis
* Fault Detection in Manufacturing
* Explainable AI for industrial systems

---

## Future Work

Planned future extensions include:

* Time-series modeling of manufacturing processes
* Spatiotemporal modeling for industrial systems
* Anomaly detection in sensor streams
* Predictive maintenance modeling

---

## Author

This repository is maintained as part of my ongoing learning in:

* Data Science
* Industrial AI
* Manufacturing analytics
# PI_for_SECOM_data
