# 🏡 House Price Prediction AI System
### AICTE | IBM SkillsBuild Data Analytics with AI Academic Internship 2026
**Conducted by:** BharatCares in association with AICTE  
**Domain:** Data Analytics & Artificial Intelligence  

---

## 📌 Project Overview
An end-to-end Machine Learning real estate valuation system built entirely in **Python**, featuring advanced regression modeling for the backend and a reactive, interactive frontend powered by **Streamlit**.

The project uses the benchmark **California Housing Dataset** (20,640 records) to predict property valuations based on socio-economic demographics, property dimensions, and geographic coordinates.

---

## 🔗 Dataset Source & Link
- **Dataset Name:** California Housing Dataset (U.S. Census Bureau)
- **Direct Source:** Accessible via Scikit-Learn API: `sklearn.datasets.fetch_california_housing`
- **Reference URL:** [Scikit-Learn California Housing Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- **Local CSV Path:** `house_price_prediction/data/housing.csv`

---

## 🛠️ Technologies & Libraries Used
- **Programming Language:** Python 3.10+
- **Data Analytics & Preprocessing:** `pandas`, `numpy`
- **Machine Learning & Modeling:** `scikit-learn`, `joblib`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Interactive Web Frontend:** `streamlit`
- **Documentation Generation:** `python-docx`

---

## 🏆 Model Benchmarking & Performance

| Model | R² Score | Mean Absolute Error (MAE) | Root Mean Squared Error (RMSE) | Status |
| :--- | :---: | :---: | :---: | :---: |
| **Gradient Boosting Regressor** | **0.8193** | **$32,586.08** | **$48,662.08** | 🏆 **Best Model** |
| Random Forest Regressor | 0.8027 | $33,122.47 | $50,853.16 | Candidate |
| Linear Regression | 0.5942 | $52,606.21 | $72,920.65 | Baseline |
| Ridge Regression | 0.5942 | $52,605.18 | $72,920.27 | Regularized |

### 🔑 Top Pricing Drivers (Feature Importance):
1. **Median Household Income (`MedInc`)**: **57.0%**
2. **Average Household Occupancy (`AveOccup`)**: **13.0%**
3. **Geographic Coordinates (`Longitude` & `Latitude`)**: **20.5%**
4. **House Age & Living Rooms**: **9.5%**

---

## 💻 Streamlit Web Application Features
1. **🎯 Real-Time Price Predictor**: Interactive sliders, location presets (Silicon Valley, Santa Monica, La Jolla, Sacramento, Fresno), instant valuations, and confidence margins ($\pm \text{MAE}$).
2. **📊 Exploratory Data Analysis (EDA)**: Interactive price distributions, income-price trends, age distributions, and correlation heatmap.
3. **🗺️ Geospatial Price Map**: Interactive California map with real-time price filter slider.
4. **🤖 Model Benchmarking**: Comparative tables, R² bar charts, and feature importance rankings.
5. **📁 Batch CSV Prediction**: Upload custom CSV spreadsheets and download predicted property valuations.

---

## 🚀 Setup & Execution Instructions

### 1. Installation
Install the project dependencies:
```bash
pip install -r requirements.txt
```

### 2. Run the Machine Learning Pipeline
To re-train the models and evaluate benchmarks:
```bash
python house_price_prediction/src/train.py
```

### 3. Launch the Streamlit Web Application
```bash
# Option A: Root launcher
python run_app.py

# Option B: Streamlit module command
python -m streamlit run house_price_prediction/app.py
```
Open your browser at `http://localhost:8501`.

---

## 📂 Project Submission Files Summary

| Requirement | Submitted File | Description |
| :--- | :--- | :--- |
| **1. Code File** | `Soumik_HousePricePrediction.ipynb` | Complete executed Jupyter Notebook with markdown, code, outputs, and plots |
| **2. Requirements File** | `requirements.txt` | Python dependencies required to run the project |
| **3. Project Report** | `Soumik_ProjectReport.docx` | Comprehensive technical & academic project report |
| **4. README File** | `README.md` | Detailed project overview, dataset link, setup guide, and results |
