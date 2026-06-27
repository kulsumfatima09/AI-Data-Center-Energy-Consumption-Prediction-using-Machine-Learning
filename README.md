# 🔋 AI Data Center Energy Consumption Prediction using Machine Learning

## 📌 Project Overview

As Artificial Intelligence continues to expand, AI data centers require enormous computational power, resulting in high electricity consumption and increased cooling demands. Efficient energy management has become one of the biggest challenges in building sustainable AI infrastructure.

This project develops a Machine Learning model that predicts **energy consumption (kWh)** of an AI data center using operational and environmental parameters. The objective is to understand the factors that influence energy usage and support smarter, more sustainable resource management.

---

## 🎯 Problem Statement

Modern AI data centers consume significant amounts of electricity due to heavy CPU/GPU workloads and cooling requirements. Predicting energy consumption can help organizations:

* Optimize resource utilization
* Reduce operational costs
* Improve cooling efficiency
* Support sustainable AI infrastructure
* Make data-driven operational decisions

---

## 📊 Dataset Features

The dataset includes:

* Date & Hour
* CPU Utilization (%)
* GPU Utilization (%)
* Active Servers
* Outside Temperature (°C)
* Humidity (%)
* Cooling Method
* Cooling Efficiency (%)
* AI Workload
* Renewable Energy (%)
* Power Usage Effectiveness (PUE)

**Target Variable**

* Energy Consumption (kWh)

---

## ⚙️ Project Workflow

* Data Loading
* Data Cleaning
* Feature Engineering
* Label Encoding
* Exploratory Data Analysis (EDA)
* Data Visualization using Matplotlib
* Train-Test Split
* Linear Regression Model
* Model Evaluation
* Prediction & Performance Analysis

---

## Feature Engineering

Additional features were created to improve prediction performance:

* Total Computation Power
* Energy Per Server
* Cooling Load

---

## Model Performance

| Metric   |      Score |
| -------- | ---------: |
| MAE      |  **24.10** |
| MSE      | **805.89** |
| RMSE     |  **28.39** |
| R² Score | **0.9924** |

The model achieved an **R² score of 99.24%**, indicating excellent prediction accuracy on the available dataset.

---

## 📊 Visualizations

The project includes visual analysis of:

* Energy Consumption Distribution
* CPU Utilization vs Energy Consumption
* GPU Utilization vs Energy Consumption
* Temperature vs Energy Consumption
* Cooling Method vs Energy Consumption
* AI Workload vs Energy Consumption
* Actual vs Predicted Energy Consumption

---

## 💡 Key Insights

* Higher CPU and GPU utilization generally increases energy consumption.
* Outside temperature significantly affects cooling requirements.
* Cooling methods influence overall power usage.
* AI workload directly impacts computational demand and energy usage.
* Feature engineering improved the model's ability to capture operational patterns.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## 🚀 Future Improvements

This project can be extended further by:

* Predicting energy consumption using **real-time user inputs** instead of only the test dataset.
* Deploying the model as an interactive **Streamlit web application**.
* Comparing Linear Regression with advanced models such as Random Forest, XGBoost, and Gradient Boosting.
* Training the model on real-world AI data center datasets for better generalization.
* Integrating weather APIs to improve prediction accuracy using live environmental data.
* Developing an AI recommendation system that suggests optimal cooling strategies and resource allocation to reduce energy consumption.
* Building an energy optimization dashboard using Tableau or Power BI for business decision-making.

---

## 🎯 Conclusion

This project demonstrates how Machine Learning can be applied to estimate AI data center energy consumption and identify operational factors affecting power usage. It highlights the potential of predictive analytics in supporting sustainable AI infrastructure and energy-efficient decision-making.
