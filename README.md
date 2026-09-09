# 🚗 Accident Detection and Severity Prediction Using Machine Learning

## 📌 Project Overview

**Accident Detection and Severity Prediction Using Machine Learning** is a machine learning project developed to predict the severity of road traffic accidents based on different accident-related conditions.

The system analyzes factors such as **weather conditions, road surface conditions, vehicle type, and light conditions** and predicts the accident severity as **Slight Injury, Serious Injury, or Fatal Injury**.

The project also includes a **Telegram Bot** that allows users to enter accident-related information and receive the predicted severity.

## 🎯 Objectives

* Predict the severity of road traffic accidents.
* Apply machine learning techniques to real-world accident data.
* Perform data preprocessing and feature encoding.
* Compare different machine learning classification algorithms.
* Provide predictions through a Telegram Bot.
* Explore the possibility of integrating the system with IoT and real-time monitoring systems.

## 📊 Dataset

The project uses the **RTA Dataset (Road Traffic Accident Dataset)**.

* **Number of records:** 12,316
* **Number of features:** 32
* **Format:** CSV
* **Problem Type:** Supervised Learning – Classification
* **Target Variable:** `Accident_severity`

### Accident Severity Classes

* Slight Injury
* Serious Injury
* Fatal Injury

The dataset contains information related to weather, road conditions, vehicle type, lighting, collision type, casualties, causes of accidents, and other accident-related factors.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* NumPy
* Matplotlib
* Seaborn
* Telegram Bot API
* Asyncio
* Jupyter Notebook / Google Colab

## 🤖 Machine Learning Models

The following classification algorithms were explored:

### 1. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to make predictions.

### 2. Support Vector Machine (SVM)

A classification algorithm that finds a suitable decision boundary between different classes.

### 3. Multi-Layer Perceptron (MLP)

A neural-network-based classifier capable of learning complex patterns in the data.

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Accident Severity Prediction
   ↓
Telegram Bot
```

The project uses preprocessing techniques such as **missing-value handling, One-Hot Encoding, Standard Scaling, and a Column Transformer pipeline**.

## 📈 Model Performance

The models were evaluated using **accuracy, precision, recall, and F1-score**.

| Model         | Accuracy |
| ------------- | -------: |
| Random Forest |   83.60% |
| SVM           |   83.77% |

The results show that the models achieved around **84% overall accuracy** on the test data. However, the dataset is highly imbalanced, with much fewer Serious and Fatal Injury examples than Slight Injury examples, so accuracy alone should not be considered sufficient for evaluating the model.

## 💬 Telegram Bot

A Telegram Bot was integrated into the project to provide an easy way for users to enter accident information.

The bot collects:

1. Weather Condition
2. Road Surface Condition
3. Type of Vehicle
4. Light Condition

After collecting the inputs, the trained machine learning model predicts the accident severity and sends the result to the user.

## 📊 Data Visualization

The project includes visualizations for:

* Accident Severity Distribution
* Weather Conditions vs Accident Severity
* Road Surface Conditions vs Accident Severity
* Light Conditions vs Accident Severity
* Vehicle Type vs Accident Severity

These visualizations help understand patterns and relationships within the accident dataset.

## ⭐ Key Features

* Real-world accident dataset
* Data preprocessing pipeline
* Multiple ML classification models
* Accident severity prediction
* Data visualization
* Telegram Bot integration
* Scalable architecture
* Potential IoT integration

## 📁 Suggested Repository Structure

```text
Accident-Severity-Prediction/
│
├── data/
│   └── RTA Dataset.csv
│
├── notebooks/
│   └── accident_severity_prediction.ipynb
│
├── src/
│   └── accident_prediction.py
│
├── images/
│   └── visualizations/
│
├── requirements.txt
├── README.md
└── LICENSE
```

## 🚀 Future Improvements

* Handle class imbalance using appropriate techniques.
* Improve prediction performance for Serious and Fatal Injury classes.
* Add more relevant features to the prediction model.
* Integrate real-time IoT sensor data.
* Add computer vision-based accident detection.
* Deploy the model as a web application.
* Improve the Telegram Bot interface.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Python programming
* Machine learning classification
* Data preprocessing
* Feature engineering
* Model evaluation
* Data visualization
* Working with real-world datasets
* Telegram Bot integration
* Understanding ethical considerations in AI-based public safety systems.

## 👩‍💻 Author

**P. Divya**
B.Tech – Artificial Intelligence & Data Science

## 📜 Internship

This project was developed as part of a **Machine Learning Using Python Internship**.
