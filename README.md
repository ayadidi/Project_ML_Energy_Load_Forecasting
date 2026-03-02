# Electrical Energy Consumption Prediction (Morocco) 🇲🇦

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)

## 📌 Project Overview
This project aims to predict the electricity consumption of the city of Tetouan[cite: 4, 6, 109]. [cite_start]The goal is to provide a decision-support tool to optimize production, manage peak loads, and reduce the carbon footprint.

## 📊 Models and Performance
We adopted an incremental approach by comparing three different algorithms:
* **XGBoost (Final Choice):** Exceptional performance with an **R² score of 98.4%**.
* **Linear Regression:** Used as a baseline, reaching **99.4%** accuracy by integrating lag variables.
* **Random Forest:** Robust against non-linearities with an accuracy of **89%**.

## 🛠️ Key Influence Factors
Exploratory Data Analysis (EDA) demonstrated that:
* **Temperature** is the #1 determining factor due to the heavy use of air conditioning and heating.
* A critical consumption peak systematically occurs at **8:00 PM (20h00)**.
* The months of **July and August** show the highest electrical loads.

## 🖥️ Dashboard Application
An interactive interface developed with **Streamlit** allows users to:
1. **Simulate consumption** by modifying weather parameters (Temperature, Humidity, Wind Speed).
2. **Visualize real-time predictions** through a "Traffic Light" alert system.
3. **Compare model performances** across historical data windows.

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ayadidi/Project_ML_Energy_Load_Forecasting.git](https://github.com/ayadidi/Project_ML_Energy_Load_Forecasting.git)
   cd Project_ML_Energy_Load_Forecasting
