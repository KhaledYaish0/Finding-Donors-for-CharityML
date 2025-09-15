# 🎯 Finding Donors for CharityML

This project applies **supervised machine learning** to predict whether an individual earns more than \$50,000 per year using U.S. Census data.  
The goal is to help **CharityML**, a fictitious NGO, identify potential donors and target them efficiently.

---

## 📦 Data

- **Source:** U.S. Census demographic dataset (`census.csv`)  
- **Features:** Age, education, occupation, workclass, hours-per-week, etc.  
- **Target:** `income` (whether >50K or <=50K)

---

## 🛠️ Methods

1. **Data Preprocessing**
   - Handle categorical & numerical variables
   - Apply one-hot encoding
   - Scale/normalize features
   - Train/validation/test split

2. **Baseline Model**
   - Naive predictor as benchmark

3. **Supervised Learning Models**
   - Decision Tree  
   - Random Forest  
   - AdaBoost  
   - Support Vector Machine (SVM)

4. **Model Evaluation**
   - Metrics: accuracy, F1-score
   - Compare model performance vs. baseline

5. **Model Tuning**
   - Hyperparameter optimization using `GridSearchCV` (best results with AdaBoost)

6. **Feature Importance**
   - Identify top predictive features using `feature_importances_`
   - Visualize with helper functions from `visuals.py`

---

## 📊 Results

- **Best model:** AdaBoost (after tuning)  
- **Performance:**  
  - Accuracy and F1-score significantly better than baseline  
  - Top features included **age**, **hours-per-week**, **education-level**, and **occupation**  
- **Impact:** Allows targeted marketing to maximize donor ROI

---
## 📁 Project Layout

Finding-Donors-Project/
├── finding_donors.ipynb # Main notebook (exploration, training, evaluation).

├── census.csv # U.S. Census dataset.

├── visuals.py # Visualization helper functions.

├── project_description.md # Udacity project brief.

└── README.md # Project documentation.



---

## ⚙️ Setup

```bash
# (Optional) create a virtual environment first
pip install -r requirements.txt
```

## 📌 Requirements

1. numpy

2. pandas

3. scikit-learn

4. matplotlib

5. seaborn

## 📜 License
For educational use (Udacity ML Nanodegree project)
## 📁 Project Layout

