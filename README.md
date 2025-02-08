# 🚗 Traffic Crash Severity Prediction Using Machine Learning

## 📌 Overview
This project aims to predict the **severity of traffic crashes** using machine learning techniques on the **Chicago Traffic Incident Dataset**. By identifying key contributing factors, our model assists in proactive safety planning, helping **city planners and policymakers** reduce severe crashes and enhance road safety.

## 📊 Research Objectives
- Identify key factors influencing **crash severity**.
- Develop **machine learning models** to predict crash severity.
- Improve prediction accuracy using techniques like **SMOTE** and **class weighting**.
- Provide actionable insights for **road safety improvements**.

## 📌 Dataset
The dataset includes attributes like:
- **Time & Location:** Hour of the day, intersection details.
- **Weather Conditions:** Rain, snow, fog, visibility.
- **Road Characteristics:** Speed limits, lane count, road type.
- **Incident Outcomes:** Crash severity (minor vs. severe).

## 📊 Data Preparation
- **Data Cleaning:** Handled missing values (10% of records).
- **Categorical Encoding:** Used **one-hot encoding** and **label encoding**.
- **Feature Engineering:** Created **time buckets** and **weather condition flags**.
- **Data Splitting:** 70% training, 30% testing.

## 🏆 Models Implemented
| Model                  | Accuracy | Recall (Severe Crashes) | F1 Score |
|------------------------|----------|-------------------------|----------|
| Logistic Regression    | 74%      | 62%                     | 0.68     |
| Random Forest         | 81%      | 70%                     | 0.75     |
| XGBoost               | 84%      | 78%                     | 0.80     |

✅ **Best Model:** **XGBoost** (Accuracy: **84%**, AUC-ROC: **0.89**).

## 📌 Key Insights
- 🚦 **Time of Day** and **Weather Conditions** are **strong predictors** of crash severity.
- 🌧️ **Rain & Snow** increase severe crash likelihood by **21%**.
- 🚗 **Rush Hour** crashes are **15% more likely** to be severe.
- 🚧 **Speed Limits and Road Types** significantly affect crash severity.

## 🔍 Visualizations
- **Feature Importance** (XGBoost & Random Forest)
- **Confusion Matrices** (Model Performance)
- **Crash Severity Distributions**
- **Impact of Weather on Crashes**

## 🔧 Technologies Used
- **Python** (`pandas`, `seaborn`, `scikit-learn`, `XGBoost`)
- **Jupyter Notebook**
- **Git & GitHub** (Version Control)
- **Matplotlib & Seaborn** (Visualizations)

## 👥 Contributors
- Garima Dubey (U22534435)
- Janhavi Kharmale (U30004934)
- Ruthvik Bacha (U12145480)
- Raajitha Sai (U82567912)
