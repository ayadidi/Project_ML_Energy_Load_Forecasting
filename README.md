# Electrical Energy Consumption Prediction (Morocco) 🇲🇦

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)

## 📌 Project Overview
[cite_start]This project aims to predict the electricity consumption of the city of Tetouan[cite: 4, 6, 109]. [cite_start]The goal is to provide a decision-support tool to optimize production, manage peak loads, and reduce the carbon footprint[cite: 33, 37, 80].

## 📊 Models and Performance
[cite_start]We adopted an incremental approach by comparing three different algorithms[cite: 304, 308]:
* [cite_start]**XGBoost (Final Choice):** Exceptional performance with an **R² score of 98.4%**[cite: 35, 715].
* [cite_start]**Linear Regression:** Used as a baseline, reaching **99.4%** accuracy by integrating lag variables[cite: 310, 520, 666].
* [cite_start]**Random Forest:** Robust against non-linearities with an accuracy of **89%**[cite: 313, 698].

## 🛠️ Key Influence Factors
Exploratory Data Analysis (EDA) demonstrated that:
* [cite_start]**Temperature** is the #1 determining factor due to the heavy use of air conditioning and heating[cite: 34, 876].
* [cite_start]A critical consumption peak systematically occurs at **8:00 PM (20h00)**[cite: 34, 425, 444].
* [cite_start]The months of **July and August** show the highest electrical loads[cite: 34, 420].

## 🖥️ Dashboard Application
[cite_start]An interactive interface developed with **Streamlit** allows users to[cite: 881, 883]:
1. [cite_start]**Simulate consumption** by modifying weather parameters (Temperature, Humidity, Wind Speed)[cite: 893, 895].
2. [cite_start]**Visualize real-time predictions** through a "Traffic Light" alert system[cite: 924, 926].
3. [cite_start]**Compare model performances** across historical data windows[cite: 937].

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ayadidi/Project_ML_Energy_Load_Forecasting.git](https://github.com/ayadidi/Project_ML_Energy_Load_Forecasting.git)
   cd Project_ML_Energy_Load_Forecasting