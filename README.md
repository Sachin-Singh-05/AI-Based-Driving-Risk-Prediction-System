# AI-Based Driver Risk Prediction System

An AI-powered Driver Risk Prediction System that analyzes accelerometer and gyroscope sensor data collected from Android smartphones to evaluate two-wheeler driving behavior and generate a Driving Risk Score.

The project uses Machine Learning and Deep Learning models to classify riding patterns as safe, moderate, or risky based on motion sensor readings.

---

## Project Overview

This project focuses on building a real-world driving behavior analysis system using smartphone motion sensors.

Sensor data was collected using an Android application under different driving conditions including:
- Multiple riders
- Multiple vehicles
- Different riding speeds
- Different phone placements

The collected dataset was used to train and compare Machine Learning and Deep Learning models for driver risk prediction.

---

## Features

- Driving Risk Score prediction
- Accelerometer and gyroscope data analysis
- Real-world sensor dataset creation
- Streamlit-based interactive dashboard
- Driving behavior visualization
- Deep Learning sequence modeling
- RNN vs Transformer comparison
- Trustworthiness evaluation of predictions

---

## Technologies Used

### Programming & ML
- Python
- Scikit-learn
- TensorFlow
- Keras

### Data Processing
- Pandas
- NumPy

### Visualization
- Plotly
- Matplotlib

### Deployment
- Streamlit
- Streamlit Cloud

---

## Dataset

The dataset contains sequential motion sensor readings captured from Android smartphones during two-wheeler rides.

### Sensors Used
- Accelerometer
- Gyroscope

### Input Features
- Accelerometer X, Y, Z
- Gyroscope X, Y, Z
- Sequential motion patterns

### Output
- Safe Driving
- Moderate Risk
- High Risk

---

## Models Used

### Deep Learning Models
- GRU
- Transformer

---

## Performance Results

### Transformer Model
| Metric | Value |
|---|---|
| Training Accuracy | ~90.5% |
| Validation Accuracy | ~88.3% |
| Validation Loss | ~0.29 |

### GRU Model
| Metric | Value |
|---|---|
| Training Accuracy | ~86–88% |
| Validation Accuracy | ~85–87% |

### Observation
Transformer models achieved better sequence understanding and higher validation accuracy compared to GRU models for long sensor sequences.

---

## Streamlit Dashboard (Working)

The project includes an interactive Streamlit dashboard for:
- Uploading sensor CSV files
- Predicting driver risk
- Visualizing sensor signals
- Displaying driving analytics and risk scores

---

## Project Structure

```bash
AI-Driver-Risk-Prediction-System/
│
├── app.py
├── requirements.txt
├── models/
├── dataset/
├── notebooks/
├── assets/
└── README.md
