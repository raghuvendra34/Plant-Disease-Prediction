# Plant Disease Prediction Using Deep Learning

## Overview

This project is a Deep Learning-based Plant Disease Prediction System that identifies diseases in plant leaves from images using Convolutional Neural Networks (CNNs).

The model is trained on the PlantVillage Dataset and integrated with a Streamlit web application that allows users to upload plant leaf images and receive disease predictions in real time.

---

## Features

* Plant disease classification using Deep Learning
* Image-based disease detection
* Interactive Streamlit web application
* Real-time prediction on uploaded leaf images
* Support for multiple plant disease categories
* Disease prediction with confidence scores
* User-friendly interface

---

## Dataset

**Dataset Name:** PlantVillage Dataset

The dataset contains thousands of images of healthy and diseased plant leaves across multiple crop species.

**Dataset Source:**
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn
* Streamlit

---

## Project Workflow

```text
Image Data
    ↓
Data Preprocessing
    ↓
Train/Test Split
    ↓
CNN Model Development
    ↓
Model Training
    ↓
Model Evaluation
    ↓
Disease Prediction System
    ↓
Streamlit Web Application
```

---

## Project Structure

```text
Plant-Disease-Prediction/
│
├── app/
│   ├── main.py
│   ├── class_indices.json
│   └── requirements.txt
│
├── model_training_notebook/
│   └── Plant_Disease_Prediction.ipynb
│
├── screenshots/
│
├── test_images/
│
├── README.md
├── requirements.txt
├── dataset_link.txt
└── .gitignore
```
---

## Model Download

The trained model file is not included in this repository because it exceeds GitHub's file size limit (547 MB).

Download the trained model from Google Drive:

https://drive.google.com/file/d/1a9volp-XB29zDHFT_r2FCvJdV_tCM1yR/view?usp=drive_link

After downloading, place the model file inside:

```text
app/trained_model/
```

Expected file:

```text
plant_disease_prediction_model.keras
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/raghuvendra34/Plant-Disease-Prediction.git
cd Plant-Disease-Prediction
```

Create and activate a virtual environment:

```bash
conda create -n plantdisease python=3.11 -y
conda activate plantdisease
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the Streamlit application:

```bash
streamlit run app/main.py
```

Open your browser and visit:

```text
http://localhost:8501
```

---

## Model Performance

The CNN model was trained on the PlantVillage Dataset and evaluated using training and validation metrics.

Performance visualization and model evaluation results are included in the notebook:

```text
model_training_notebook/Plant_Disease_Prediction.ipynb
```

---

## Model File Notice

The trained model file (~547 MB) is not included in this repository because it exceeds GitHub's file size limitations.

The model can be downloaded using the Google Drive link provided above and placed inside:

```text
app/trained_model/
```

The application has been successfully tested in a local Streamlit environment.

---

## Future Improvements

* Transfer Learning (ResNet50, EfficientNet)
* Hyperparameter Optimization
* Model Compression
* Cloud Deployment
* Mobile Application Integration
* Improved Prediction Confidence Analysis
  
---

## Author

**Raghuvendra Kumar**
