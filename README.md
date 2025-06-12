# 🏥 Medical Cost Prediction using Machine Learning

This project focuses on predicting individual medical insurance charges using machine learning techniques. It uses features such as age, sex, BMI, number of children, smoking status, and region to forecast charges.

---

## 📌 Overview

Accurately predicting medical costs is vital for both insurers and policyholders. This project demonstrates how machine learning algorithms like **Linear Regression** can be used to model and predict charges based on a set of features.

---

## 📊 Dataset

- **Source:** [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Rows:** 1,338
- **Features:**
  - `age`
  - `sex`
  - `bmi`
  - `children`
  - `smoker`
  - `region`
  - `charges` *(target)*

---

## 🧰 Tech Stack

- **Language:** Python 3.x
- **Libraries Used:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `jupyter`

---

## 📈 Workflow

1. **Data Loading & Exploration**
   - Read CSV using `pandas`
   - Summary statistics, null checks, and data types

2. **Exploratory Data Analysis (EDA)**
   - Visualization of relationships between features and `charges`
   - Distribution analysis and correlation heatmap

3. **Data Preprocessing**
   - Label encoding for categorical variables (`sex`, `smoker`, `region`)
   - Feature-target split
   - Train-test split

4. **Model Building**
   - Trained a **Linear Regression** model
   - Evaluated using:
     - R² Score
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)

5. **Model Inference**
   - Input form for predicting insurance charges for a new patient

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/medical-cost-prediction.git
cd medical-cost-prediction

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
