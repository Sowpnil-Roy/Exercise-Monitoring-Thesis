### ✅ `README.md`

````markdown
# 🏋️ Exercise Activity Recognition System

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Gradient%20Boosting%2C%20XGBoost-orange)

A machine learning system that classifies exercise activities using sensor data from wearable devices. This project demonstrates a complete ML pipeline — from data preprocessing to model evaluation.

---

## 📌 Overview

This system classifies human physical exercises into **5 distinct categories (A, B, C, D, E)** using motion data collected from:

- Inertial Measurement Units (IMUs)
- Accelerometers
- Gyroscopes
- Magnetometers

📍 **Sensor Locations:** Belt, Arm, Dumbbell, Forearm  
📈 **Top Accuracy Achieved:** `98.21%` using **XGBoost**

---

## 📊 Dataset

- **Source:** Human Activity Recognition (HAR)
- **Total Samples:** 39,159 exercise records
- **Features:** 561 sensor measurements per record
- **Classes:** 5 labeled exercise types

### 🔠 Exercise Class Breakdown

| Class | Exercise Type     | Description               |
|-------|--------------------|---------------------------|
| A     | Correct             | Standard execution        |
| B     | Elbows Front        | Common mistake            |
| C     | Lifting Halfway     | Partial range of motion   |
| D     | Lowering Halfway    | Partial range of motion   |
| E     | Hips Forward        | Form deviation            |

---

## 📈 Results: Model Performance Comparison

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Gradient Boosting | 0.9768   | 0.98      | 0.98   | 0.98     |
| XGBoost           | 0.9821   | 0.98      | 0.98   | 0.98     |
| Neural Network    | 0.9735   | 0.97      | 0.97   | 0.97     |
| SVM               | 0.9552   | 0.96      | 0.96   | 0.96     |
| Random Forest     | 0.8897   | 0.90      | 0.89   | 0.89     |

---

## 🛠️ Requirements

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
````

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Sowpnil-Roy/Exercise-Monitoring-Thesis.git
   cd Exercise-Monitoring-Thesis
   ```

2. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `Exercise_monitoring.ipynb` and run all cells step by step.

---

## 👨‍💻 Author

**Sowpnil Roy**
Bachelor of Science in Computer Science & Engineering
Ahsanullah University of Science & Technology
