# 🚦 Traffic Congestion Predictor

A machine learning project to classify road sections as **High**, **Medium**, or **Low** congestion using traffic sensor data.

## 📌 Problem Statement

Accurately predicting traffic congestion is crucial for modern cities. This project uses machine learning to classify congestion levels based on real-time traffic sensor data such as vehicle count, average speed, and occupancy.

## 📊 Features

- Traffic congestion classification: High, Medium, Low
- Data preprocessing and normalization
- Random Forest Classifier implementation
- Model evaluation with confusion matrix and classification report

## 🛠️ Technologies Used

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib (optional for visualizations)

## 📁 Dataset

Traffic sensor data should include features like:

- `vehicle_count`
- `avg_speed`
- `occupancy`
- `congestion_level` (Low / Medium / High)

> Example data source: [Kaggle Traffic Sensor Dataset](https://www.kaggle.com/)

## ⚙️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/traffic-congestion-predictor.git
   cd traffic-congestion-predictor
