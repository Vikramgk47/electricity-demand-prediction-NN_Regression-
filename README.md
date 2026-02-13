# ⚡ Energy Demand Prediction using Neural Networks

This project builds a **Neural Network regression model** to predict hourly electricity demand using real-world weather data.

The goal is to understand how weather conditions and time of day influence electricity consumption and use deep learning to forecast demand accurately.

---

## 📌 Problem Overview

Electricity demand varies throughout the day based on temperature, humidity, wind, and time patterns.  

In this project, I:
- Cleaned and prepared hourly weather + energy data
- Engineered time-based features (hour of day)
- Built a neural network regression model
- Evaluated performance using standard metrics

This is a **supervised regression problem**.

---

## 📂 Dataset

The dataset contains ~96,000 hourly observations with:

### Features
- Temperature (BDL_tmpf)
- Dew point (BDL_dwpf)
- Relative humidity (BDL_relh)
- Wind direction (BDL_drct)
- Wind speed (BDL_sknt)
- Hour of day (engineered feature)

### Target
- Electricity Demand

Note: A local CSV file is included in this repository as a backup in case the Google Drive link used in the notebook does not work.

---

## ⚙️ Workflow

### Data Preparation
- Checked missing values
- Converted datetime and created hour feature
- Selected relevant weather variables
- Removed incomplete rows

### Modeling
- 80/20 train–validation split
- StandardScaler normalization
- Neural Network (Dense layers)
- Dropout regularization
- Early stopping to prevent overfitting

### Evaluation
- Learning curves
- Scatter plots (actual vs predicted)
- Metrics: MAE, RMSE, R²

---

## 📊 Results

| Metric | Train | Validation |
|--------|--------|------------|
| MAE | ~356 | ~355 |
| RMSE | ~437 | ~436 |
| R² | ~0.67 | ~0.67 |

The model shows good generalization with similar training and validation performance and minimal overfitting.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
3. Open:
4. Run all cells

---

## 📈 Skills Demonstrated

- Data cleaning & preprocessing
- Feature engineering
- Neural network regression
- Regularization techniques (Dropout, EarlyStopping)
- Model evaluation & visualization
- End-to-end ML workflow

---

## 👤 Author

Vikram Krishnareddy  
MS Business Analytics & Project Management – University of Connecticut

