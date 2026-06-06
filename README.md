# Plant Disease Prediction Using Deep Learning

## Overview

This project aims to develop a Deep Learning-based system for identifying plant diseases from leaf images using Convolutional Neural Networks (CNNs).

The model is trained on the PlantVillage Dataset and will be deployed as an interactive web application for real-time disease prediction.

---

## Project Workflow

```text
Image Data
    ↓
Data Curation
    ↓
Data Preprocessing
    ↓
Train/Test Split
    ↓
CNN Model Development
    ↓
Model Evaluation
    ↓
Disease Prediction System
    ↓
Streamlit Deployment
```

---

## Dataset

**Dataset Name:** PlantVillage Dataset

**Source:**
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

The dataset contains thousands of images of healthy and diseased plant leaves from multiple crop species.

---

## Project Progress

### Day 1

Completed Tasks

* Importing Dependencies
* Data Curation
* Data Preprocessing

### Day 2

Completed Tasks

* CNN Architecture Design
* Model Compilation
* Model Training

### Day 3

Completed Tasks

* Model Evaluation with Training & Validation Accuracy and Loss Visualization
* Disease Prediction System with Class Index Mapping
* Prediction Testing on Sample Images

### Upcoming Tasks

* Streamlit Web Application
* User Image Upload Feature
* Model Integration with Streamlit
* GitHub Documentation
* Deployment on Streamlit Cloud

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn
* Streamlit

---

## Project Structure

```text
Plant-Disease-Prediction/
│
├── Plant_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── class_indices.json
│
├── data/
│   └── dataset_link.txt
│
├── images/
│
└── test_images/
```

---

## Future Improvements

* Hyperparameter Tuning
* Data Augmentation
* Transfer Learning (ResNet50, EfficientNet)
* Model Optimization
* Cloud Deployment

---

## Expected Output

The model will classify plant leaf images into healthy or diseased categories and provide disease predictions with confidence scores.

---

## Author

Raghuvendra Kumar