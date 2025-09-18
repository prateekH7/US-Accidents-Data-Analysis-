
# US Accidents Data Analysis (2016–2023) 🚗💥

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/601d7f09-b440-4fe2-894a-fc1f9c8ea8df" />


---

## 📊 Project Overview

The **US Accidents Data Analysis** project investigates accident trends across the United States from **2016–2023**. Using a combination of **exploratory data analysis (EDA)** and **machine learning models**, we identify:

* Key factors that contribute to accidents.
* Temporal and geographical accident patterns.
* Predictive insights into accident severity.

This work provides **data-driven recommendations** for improving **road safety policies** and building **early-warning systems**.

---

## 📁 Dataset

* **Source**: [Kaggle - US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents/)
* **Size**: \~7.7M accident records (2016–2023)
* **Subset Used**: 10,000 records (for computational efficiency)
* **Features**:

  * 🕒 Start\_Time, End\_Time
  * 🌦️ Weather\_Condition, Temperature, Visibility, Humidity, Precipitation
  * 🚦 Severity (1–4)
  * 📍 Location coordinates (lat/long)
  * 🛣️ Road/City/State

---

## 🧠 Data Mining Task

### 🔹 Binary Classification

* Predicting **Severe (3–4)** vs **Non-Severe (1–2)** accidents.

### 🔹 Multiclass Classification

* Classifying accidents into **Severity Levels 1–4**.

---

## 🔧 Methodology

### 1. Data Preprocessing ✅

* Missing values → imputed with mean/mode.
* Outliers → capped using IQR method.
* Feature Engineering → label encoding, one-hot encoding, scaling.

### 2. Exploratory Data Analysis (EDA) ✅

* Accident frequency across **years, days, and hours**.
* **Geospatial heatmaps** of accident hotspots.
* Weather & road condition impacts.

### 3. Models Implemented ✅

* **Binary Classification**: Random Forest, Bagging Classifier, SVC, Perceptron
* **Multiclass Classification**: Random Forest, Bagging Classifier, Logistic Regression, KNN

### 4. Evaluation Metrics ✅

* Accuracy, Precision, Recall, F1 Score, ROC-AUC

---

## 🎯 Results

### Binary Classification

| Model                  | Test Accuracy | AUC  | F1 Score |
| ---------------------- | ------------- | ---- | -------- |
| RandomForestClassifier | **82.4%**     | 0.76 | High     |
| BaggingClassifier      | 82.1%         | 0.76 | Balanced |



### Multiclass Classification

| Model                  | Test Accuracy | AUC  |
| ---------------------- | ------------- | ---- |
| RandomForestClassifier | **81%**       | 0.81 |
| BaggingClassifier      | 81%           | 0.76 |



---

## 🔎 Key Insights

* 🚦 **Rush Hours (7–9 AM, 4–6 PM)** see the highest accident peaks.
* ❄️ **Winter months (Nov–Dec)** have more severe accidents.
* 🌎 **California, Texas, Florida** → highest accident hotspots.
* 🌧️ Weather factors (rain, fog, overcast) increase risk.
* 🌲 **Random Forest & Bagging** → best performing models.

---

## 📊 Tools & Libraries

* **Python** 🐍
* **Data Analysis**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn, Plotly
* **Machine Learning**: Scikit-learn

---

## ✅ Conclusion

This project demonstrates how **machine learning models** and **data analysis** can provide **actionable insights** for traffic safety improvements.

* Random Forest and Bagging Classifier → reliable for accident severity prediction.
* Potential future work → **real-time prediction system** for traffic management.

---

## 🤝 Contributors

* Pratik Harlikar
* Aditya Jadhav

💡 Contributions welcome!

* Fork 🍴 → Improve 🔄 → Submit PR ✅

---

## 📝 License

This project is licensed under the **MIT License**.

---

✨ *Drive safe, analyze smarter!* 🚗💨

---
