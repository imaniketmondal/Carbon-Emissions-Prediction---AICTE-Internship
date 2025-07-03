
# 🌍 Carbon Emission Prediction

**AI/ML Internship Project – June 2025 Batch**
**Presented by Edunet Foundation**, in collaboration with **AICTE & Shell**

**AICTE Student ID**: `STU63b8ff682f6021673068392`

---

## 📌 Project Overview

This internship project focuses on preparing and modeling a climate dataset to predict CO₂ emissions using machine learning techniques. The end-to-end process includes data cleaning, exploratory data analysis (EDA), feature engineering, and building a predictive model to forecast emissions based on selected indicators.

---

## ✅ Milestones

### 📅 Week 1: **Stage 1 – Data Cleaning & Preparation** (Completed: *18 June 2025*)

* **Data Source**: `Dataset.xlsx` (multiple sheets)
* **Loading Method**: Used `pandas.read_excel()` to load Excel sheets directly (no CSV conversion)
* **Steps Performed**:

  * Removed null values, duplicates, and irrelevant rows/columns
  * Parsed sheets and standardized formats
  * Reformatted data for ML compatibility
* **Output File**: `data_cleaned.csv`

#### 📁 Files Included:

* `data_preparation.ipynb` → Jupyter Notebook with data loading & cleaning
* `Dataset.xlsx` → Original raw dataset
* `data_cleaned.csv` → Exported cleaned dataset

#### 🛠 Tools Used:

* Python
* Pandas
* Jupyter Notebook

---

### 📅 Week 2: **Stage 2 – Data Exploration & Visualization** (Completed: *24 June 2025*)

* **Input**: Cleaned dataset from Stage 1

* **Exploration Highlights**:

  * Identified and decoded key dataset columns & units
  * Correlation analysis and feature selection

* **Visualizations Created**:

  * Correlation matrix heatmap
  * Scatterplots and histograms
  * Outlier detection plots

#### 📁 Files Included:

* `data_exploration.ipynb` → Jupyter Notebook with EDA, feature analysis & plots

#### 🛠 Tools Used:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

### 📅 Week 3: **Final Stage – Predictive Modeling** (Completed: *1 July 2025*)

* **Goal**: Predict future CO₂ emissions using selected features

* **Target Variable**: Emissions

* **Key Steps**:

  * Confirmed relevant features from EDA
  * Applied Recursive Feature Elimination (RFECV)
  * Model: Random Forest Regressor
  * Performed hyperparameter tuning using cross-validation
  * Trained final model and evaluated on test data

#### 📁 Files Included:

* `model_building.ipynb` → Notebook with model training, tuning, and evaluation
* `Model/forecasting_co2_emmision.zip` → Trained model archive (`.pkl` file)

#### 🔗 Model Download:

[Download Trained Model (.pkl) via Google Drive](https://drive.google.com/file/d/1-wzx_IyQUtciTfOTHopAUv4VufQa00ba/view?usp=sharing)

#### 🛠 Tools Used:

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 🚀 Deployment

The trained model has been deployed as a web application using **Railway**.

**🌐 Live App Link**: [https://co2emmisionforecasting.up.railway.app/](https://co2emmisionforecasting.up.railway.app/)

> Users can input feature values and get predicted CO₂ emissions directly from the app.

---

## 📦 Project Folder Structure

```
Carbon_Emission_Prediction/
│
├── Dataset.xlsx
├── data_cleaned.csv
├── data_preparation.ipynb
├── data_exploration.ipynb
├── model_building.ipynb
├── Model/
│   └── forecasting_co2_emmision.zip
└── README.md
```

---

## 📈 Future Scope

* Integration with real-time climate data APIs
* Deployment of the model using Flask/FastAPI + Docker
* Try alternative models like XGBoost, LSTM (for temporal trends)
* Add model explainability tools like SHAP or LIME

---

## 👨‍💻 Developed Under

**AI/ML Internship Program – June 2025 Batch**
Supervised Capstone Project on Climate Analytics & Prediction
Hosted by **Edunet Foundation**, in collaboration with **AICTE & Shell**

---

