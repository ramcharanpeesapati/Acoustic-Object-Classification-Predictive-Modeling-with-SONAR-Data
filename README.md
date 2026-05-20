# Acoustic Object Classification: Predictive Modeling with SONAR Data 🌊🔍

An end-to-end binary classification pipeline built in Python utilizing Logistic Regression to predict whether an underwater object detected by SONAR is a Rock (R) or a metal Mine (M).

## 📊 Dataset Profile
* **Features:** 60 numerical columns representing sonar energy returns at different angles.
* **Instances:** 208 data points (111 Mines, 97 Rocks).
* **Source:** UCI Machine Learning Repository.

## 🛠️ Tech Stack & Workflow
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Scikit-learn, ipywidgets
* **Model:** Logistic Regression (`sklearn.linear_model`)
* **Strategy:** Data Preprocessing -> Stratified 90/10 Train-Test Split -> Optimization -> Evaluation -> Predictive Inference System -> Interactive Visualizer.

## 📈 Performance Metrics
* **Training Accuracy:** ~83.42%
* **Testing Accuracy:** ~76.19%

## 🎮 Interactive Visualizer
This project includes a custom UI built with `ipywidgets` allowing users to manually adjust the Acoustic Gain ($w_1$), Density Factor ($w_2$), and Sensitivity Threshold ($b$) to see how the mathematical decision boundary shifts in real-time. (Open the Colab notebook to interact with the sliders).
