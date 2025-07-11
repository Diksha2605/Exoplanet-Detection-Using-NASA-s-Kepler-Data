# 🪐 Exoplanet Detection using NASA Kepler Data

This project focuses on building a machine learning model to detect **exoplanets** (planets outside our solar system) using data from NASA's **Kepler** space telescope. The model leverages statistical and classification techniques to distinguish confirmed exoplanets from false positives.

---

## 🚀 Overview

NASA’s Kepler mission gathered light curve data from thousands of stars, looking for dips in brightness that suggest a planet passing in front of its host star. This project uses the Kepler dataset to classify planet candidates as either:

- **CONFIRMED**
- **FALSE POSITIVE**
- **CANDIDATE**

---

## 🧠 Machine Learning Workflow

### ✅ 1. Data Preprocessing
- Missing value handling
- Label encoding for categorical features
- Feature selection based on correlation and importance

### 📊 2. Exploratory Data Analysis (EDA)
- Distribution of exoplanet categories
- Correlation heatmaps
- Feature importance visualizations

### 🤖 3. Model Building
Models used:
- Logistic Regression
- K-Nearest Neighbors
- Random Forest (Best performer)
- Gradient Boosting

### 📈 4. Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve

---

## 📂 Project Structure

