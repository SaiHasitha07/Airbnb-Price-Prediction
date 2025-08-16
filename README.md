# Airbnb-Price-Prediction
# Airbnb Price Prediction

## 📌 Project Overview
This project builds an **ML model** to predict nightly **Airbnb listing prices** using listing metadata (location, room type, reviews, host details, amenities).  
The solution provides price drivers and estimates to support **competitive pricing** and **market analysis**.

## 📂 Dataset
- **Source**: Kaggle – [Airbnb Price Prediction](https://www.kaggle.com/stevezhenghp/airbnb-price-prediction)  
- Typical fields:
  - Location / Neighbourhood
  - Room Type & Property Type
  - Accommodates / Beds / Bathrooms
  - Amenities & Description
  - Reviews & Ratings
  - Host Tenure
  - **Price** (target)

## 🛠️ Project Workflow

### 1. **Data Preparation**
- Cleaned records, handled missing values and outliers.
- Standardized formats (dates, text, numerical units).
- Encoded categorical variables for modeling.

### 2. **Feature Engineering**
- Derived features: **amenities_count**, **price_per_guest**, **host_tenure_days**.
- One-hot / target encoding for high-cardinality fields.
- Optional log-transform for skewed target distribution.

### 3. **Modeling & Evaluation**
- Baselines: **Linear/Ridge/Lasso Regression**.
- Trees/ensembles: **Random Forest**, **Gradient Boosting** (XGBoost/LightGBM optional).
- Metrics: **MAE**, **RMSE**, **R²** with cross-validation.

### 4. **Analysis & Insights**
- Identified top price drivers (location, room type, capacity, amenities).
- Compared neighbourhood-level pricing bands and seasonal effects.
- Produced explainability visuals (feature importance, partial dependence).

## 📊 Key Features
- **End-to-end pipeline**: cleaning → features → training → evaluation.
- **Interpretability-first**: clear view of drivers impacting price.
- **Reusable notebook/scripts** for rapid experimentation.

## 📦 Tools & Technologies
- **Python**, **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**, **Plotly**

## 🚀 Future Improvements
- Add **calendar seasonality** and event-based features.
- Incorporate **geospatial encodings** (grid/H3) for neighbourhood effects.
- Deploy a **Streamlit** app for interactive price estimation.

## 📜 License
Open for educational and portfolio use. Attribute original dataset per [Kaggle terms](https://www.kaggle.com/stevezhenghp/airbnb-price-prediction).
