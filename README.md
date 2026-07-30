# 🚗 ML-Based Predictive Vehicle Maintenance & Engine Health Monitoring

An end-to-end **machine learning application for predictive vehicle maintenance and engine health monitoring**. The project analyzes vehicle engine sensor and telemetry data to identify patterns associated with abnormal engine conditions and predict the likelihood of maintenance requirements.

The system combines **data preprocessing, exploratory data analysis, feature engineering, machine learning, model evaluation, and Streamlit deployment** to provide a practical solution for proactive vehicle health monitoring.

---

## 🎯 Project Objective

The primary objective of this project is to use machine learning to identify potential vehicle maintenance risks before they develop into serious failures.

The system is designed to:

* Analyze vehicle engine sensor and telemetry data
* Identify patterns associated with abnormal engine conditions
* Predict vehicle maintenance risk
* Classify engine health conditions
* Estimate maintenance probability
* Provide confidence-based predictions
* Support proactive vehicle maintenance decisions

---

## 🛠️ Tech Stack

| Technology            | Purpose                                        |
| --------------------- | ---------------------------------------------- |
| **Python**            | Machine learning development and data analysis |
| **Pandas**            | Data manipulation and preprocessing            |
| **NumPy**             | Numerical computation                          |
| **Scikit-learn**      | Machine learning and model evaluation          |
| **Gradient Boosting** | Vehicle health classification                  |
| **Matplotlib**        | Exploratory data visualization                 |
| **Streamlit**         | Interactive ML application and deployment      |
| **Jupyter Notebook**  | Model development and experimentation          |

---

## 🔄 Project Workflow

```text
Vehicle Sensor & Telemetry Data
            ↓
    Data Preprocessing
            ↓
 Exploratory Data Analysis
            ↓
    Feature Engineering
            ↓
 Train / Test Data Split
            ↓
 Gradient Boosting Model
            ↓
    Model Evaluation
            ↓
 Maintenance Risk Prediction
            ↓
     Streamlit Application
            ↓
 Real-Time Vehicle Health Monitoring
```

---

## 📂 Project Structure

```text
ML-Predictive-Vehicle-Maintenance/
│
├── data/
│   └── vehicle_sensor_data.csv
│
├── notebooks/
│   └── vehicle_health_prediction.ipynb
│
├── model/
│   └── vehicle_health_model.pkl
│
├── app/
│   └── app.py
│
├── requirements.txt
│
└── README.md
```

---

## 🧹 Data Preprocessing

The raw vehicle telemetry dataset is processed to make it suitable for machine learning.

### Key preprocessing steps:

* Loaded and inspected vehicle sensor data
* Examined data types and dataset structure
* Handled missing and inconsistent values
* Identified relevant engine telemetry features
* Prepared input features for model training
* Processed the target variable for vehicle health classification
* Split the dataset into training and testing subsets

---

## 🔍 Exploratory Data Analysis

Exploratory analysis was performed to understand relationships between vehicle sensor measurements and engine health.

The analysis focused on identifying patterns across telemetry features that may indicate:

* Abnormal engine conditions
* Increased maintenance risk
* Potential component failures
* Changes in engine operating conditions
* Relationships between sensor measurements and vehicle health

Visual analysis was used to understand feature distributions, relationships, and potential indicators of engine abnormalities.

---

## ⚙️ Feature Engineering

Relevant engine telemetry features were prepared and transformed to improve the machine learning pipeline.

Feature engineering focused on extracting meaningful information from sensor measurements that could help the model distinguish between different vehicle health conditions.

The resulting feature set was used to train the predictive maintenance model.

---

## 🤖 Machine Learning Model

### Gradient Boosting Classifier

A **Gradient Boosting classification model** was used to predict vehicle health and maintenance risk.

Gradient Boosting was selected because it can effectively model complex relationships between multiple vehicle sensor features and the target health classification.

The trained model is used to:

* Classify vehicle engine health
* Estimate maintenance risk
* Generate prediction probabilities
* Support proactive maintenance decisions

---

## 📈 Model Evaluation

The trained model was evaluated using appropriate classification metrics to understand its predictive performance.

Evaluation included:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Prediction probability analysis

The evaluation process helps determine how reliably the model identifies vehicles that may require maintenance.

---

## 🚦 Predictive Maintenance System

The trained model transforms vehicle sensor readings into actionable health predictions.

The prediction pipeline can be represented as:

```text
Sensor Input
     ↓
Data Preprocessing
     ↓
Feature Transformation
     ↓
ML Model
     ↓
Vehicle Health Classification
     ↓
Maintenance Probability
     ↓
Recommended Action
```

This approach supports **proactive rather than reactive vehicle maintenance** by identifying potential risks from sensor patterns.

---

## 🖥️ Streamlit Application

The trained machine learning model is deployed through an interactive **Streamlit application**.

The application allows users to provide vehicle sensor values and receive an immediate prediction.

### Application features:

* Real-time sensor input
* Vehicle health prediction
* Maintenance risk probability
* Prediction confidence visualization
* Interactive results
* Proactive vehicle health monitoring

The application provides a simple interface for demonstrating how machine learning can be integrated into a practical vehicle monitoring system.

---

## 📊 Application Output

Based on the supplied sensor measurements, the application provides:

### Vehicle Health Prediction

The model classifies the current vehicle condition based on learned patterns from the training data.

### Maintenance Probability

The application displays the estimated probability associated with the predicted maintenance risk.

### Confidence Visualization

Prediction probabilities are visualized to make the model output easier to interpret.

---

## 💡 Key Insights

The project demonstrates how machine learning can be applied to vehicle telemetry data to:

* Detect patterns associated with abnormal engine conditions
* Identify potential maintenance risks
* Analyze relationships between sensor measurements and engine health
* Predict vehicle health conditions from telemetry data
* Support early identification of potential component issues
* Enable data-driven predictive maintenance

---

## 🚀 Future Improvements

Potential improvements to the system include:

* Integration with real-time vehicle IoT sensor streams
* Time-series analysis of sensor measurements
* Predicting remaining useful life (RUL) of components
* Integration of XGBoost and other advanced ensemble models
* Model explainability using SHAP
* Automated maintenance recommendations
* Historical vehicle health tracking
* Cloud deployment for continuous monitoring
* Integration with connected vehicle platforms

---

## 📌 Skills Demonstrated

* Machine Learning
* Predictive Maintenance
* Vehicle Health Monitoring
* Python
* Pandas
* NumPy
* Scikit-learn
* Gradient Boosting
* Feature Engineering
* Exploratory Data Analysis
* Classification
* Model Evaluation
* Predictive Analytics
* Data Visualization
* Streamlit
* Machine Learning Deployment
* Business Problem Solving

---

## 📊 Project Outcome

This project demonstrates an end-to-end machine learning workflow for **vehicle predictive maintenance**, starting from raw engine telemetry and ending with an interactive deployed application.

By combining **data preprocessing, exploratory analysis, feature engineering, Gradient Boosting, model evaluation, and Streamlit deployment**, the project showcases how machine learning can transform vehicle sensor data into actionable insights for proactive vehicle health monitoring.

---

## 👩‍💻 Author

**Yashashwini Siwach**

B.Tech — Computer Science & Engineering (Information Security)
Vellore Institute of Technology

Interested in **Data Analytics, Machine Learning, AI, and Software Engineering**.
