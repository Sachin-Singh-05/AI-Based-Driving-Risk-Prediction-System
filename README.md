# AI-Based Driver Risk Prediction System

An AI-powered Driver Risk Prediction System that analyzes motion sensor data collected from Android smartphones to evaluate driving behavior and generate a Driving Risk Score. The system uses accelerometer and gyroscope readings to identify unsafe riding patterns and classify rider behavior using Machine Learning and Deep Learning techniques.

---

## Project Overview

This project focuses on analyzing two-wheeler driving behavior using smartphone motion sensors. Sensor readings are captured using an Android application and used to build a dataset representing the motion characteristics of riders under different real-world driving conditions.

The objective of the project is to:

- Collect motion sensor data from Android devices
- Build a diverse driving behavior dataset
- Train Machine Learning and Deep Learning models
- Generate Driving Score / Risk Score
- Evaluate model trustworthiness and prediction reliability
- Compare traditional sequence models with Transformer-based architectures

---

## Problem Statement

Use the Android application designed to capture readings from motion sensors (accelerometer and gyroscope) in an Android phone. Build a dataset containing the motion characteristics of an average person driving a two-wheeler.

The dataset includes:
- Multiple riders
- Multiple vehicles
- Different riding speeds
- Different phone placements

Build a model that generates a Driving Score / Risk Score indicating the driving behavior of an individual and evaluate the trustworthiness of the model.

Bonus:
Compare the performance of RNN-based architectures (LSTM/GRU) with Transformer-based models for the task.

---

## Features

- Sensor-based driving behavior analysis
- Accelerometer and gyroscope data processing
- Driver risk prediction using Machine Learning
- Driving Score generation
- Streamlit-based interactive dashboard
- Sensor visualization and analytics
- Real-world riding dataset creation
- Trustworthiness evaluation of predictions
- Comparative analysis of RNNs and Transformers

---

## Dataset Collection

The dataset was created using an Android application that records smartphone motion sensor readings during two-wheeler rides.

### Sensors Used
- Accelerometer
- Gyroscope

### Dataset Variations
- Multiple riders
- Multiple vehicles
- Different riding speeds
- Different phone placements
- Different driving conditions

### Data Captured
- Accelerometer X, Y, Z
- Gyroscope X, Y, Z
- Timestamp-based sequential readings

---

## Machine Learning Workflow

1. Sensor Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Sequence Preparation
5. Model Training
6. Risk Score Generation
7. Model Evaluation
8. Streamlit Deployment

---

## Technologies Used

### Programming Language
- Python

### Machine Learning & Deep Learning
- Scikit-learn
- TensorFlow
- Keras

### Data Processing
- Pandas
- NumPy

### Visualization
- Plotly
- Matplotlib

### Web Application
- Streamlit

### Deployment
- Streamlit Cloud

---

## Model Architectures

### Deep Learning Models
- LSTM
- GRU
- Transformer-based models

---

## Comparative Analysis

The project includes performance comparison between:

| Model Type | Purpose |
|---|---|
| LSTM | Sequential driving behavior analysis |
| GRU | Lightweight sequential modeling |
| Transformer | Attention-based sequence learning |

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Trustworthiness Analysis

## RNN vs Transformers
-
Transformer Final Results (from logs): 
• Training Accuracy: ~90.5% 
• Validation Accuracy: ~88.3% 
• Validation Loss: ~0.29 
GRU Results: 
• Training Accuracy: ~86–88% 
• Validation Accuracy: ~85–87% 
---

## Streamlit Dashboard

The project includes an interactive Streamlit dashboard for:

- Uploading sensor CSV files
- Visualizing accelerometer and gyroscope signals
- Predicting driving risk
- Generating driving scores
- Displaying analytics and risk insights

---

## Project Structure

```bash
AI-Driver-Risk-Prediction-System/
│
├── app.py
├── requirements.txt
├── models/
│   ├── random_forest.pkl
│   ├── lstm_model.h5
│   └── transformer_model.h5
│
├── dataset/
│   ├── raw_data/
│   └── processed_data/
│
├── notebooks/
│   └── AI_Based_Driver_Risk_Prediction_System.ipynb
│
├── assets/
│   └── dashboard.png
│
└── README.md
