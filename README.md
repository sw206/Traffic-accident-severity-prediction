TRAFFIC ACCIDENT SEVERITY PREDICTION MODEL

GROUP 8/CONTRIBUTORS

AMINA BASHIR – 674220   -  amina1460

NICHOLAS BAHATI – 672949    -nicholasb777

IKIGU ELIZABETH – 674201      -lizwanjikuu

SYLVIA MACHARIA – 673922      - sw206

# Accident Severity Prediction Model

## 👥 Group 8 Members

- **Amina Bashir** – 674220  
- **Nicholas Bahati** – 672949  
- **Ikigu Elizabeth** – 674201  
- **Sylvia Macharia** – 673922  

---

## 🎯 Objective

The primary objective of this project was to develop and evaluate a predictive model capable of classifying the **severity of traffic accidents** based on various factors such as weather, road type, traffic density, and driver-related features.

The target variable, **Accident Severity**, is classified into:
- **Class 0:** Low severity  
- **Class 1:** Medium severity  
- **Class 2:** High severity  

---

## 📊 Data Overview

The dataset includes the following features:

- `Accident_ID`, `Date`, `Time`, `Severity` (Target)
- `Weather_Condition`, `Road_Type`, `Visibility`, `Temperature_C`
- `Traffic_Density`, `Speed_Limit`, `Traffic_Signal`
- `Vehicle_Count`, `Driver_Age`, `Alcohol_Involved`
- `County`, `Road_Name`, `Police_Response_Time`
- `Driver_Age_Group`

---

## 🧠 Methodology

1. **Data Preprocessing:** Handled missing values, encoded categorical variables.
2. **Model Training:** Used a Decision Tree Classifier (80/20 train-test split).
3. **Evaluation Metrics:** Accuracy, precision, recall, F1-score, confusion matrix.

---

## 📈 Model Evaluation Results

**Overall Accuracy:** `61%`

### Class-wise Performance:
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0 (Low) | 0.63 | 0.95 | 0.76 |
| 1 (Medium) | 0.22 | 0.04 | 0.06 |
| 2 (High) | 1.00 | 0.00 | 0.00 |

- **Macro Avg:** Precision: 0.62, Recall: 0.33, F1-Score: 0.27  
- **Weighted Avg:** Precision: 0.54, Recall: 0.61, F1-Score: 0.50  

> 🔍 **Insight:** The model performs well on low severity accidents, but struggles to detect medium and high severity ones — indicating class imbalance.

---

## 🔑 Key Findings

✅ **Strength:**  
- High recall for low severity accidents (Class 0).

⚠️ **Weaknesses:**  
- Poor prediction for medium (Class 1) and high (Class 2) severity.
- Zero recall for high severity despite perfect precision.

---

## 💡 Recommendations

- **Handle Class Imbalance:** Use SMOTE or undersampling.
- **Hyperparameter Tuning:** Improve Decision Tree settings.
- **Feature Engineering:** Create better signals from existing data.
- **Try Advanced Models:** Use Random Forest or XGBoost for better results.

---

## 📌 Conclusion

This model is a solid baseline, especially for low-severity accident detection. However, to enhance its effectiveness across all classes, future work should focus on addressing class imbalance, tuning the model, and exploring more powerful algorithms.

---

## 📦 Requirements

Make sure the following libraries are installed:

```bash
pip install matplotlib seaborn pandas numpy scikit-learn statsmodels scipy


MATPLOTLIB | matplotlib 
SEABORN | seaborn 
PANDAS | pandas 
NUMPY | numpy 
RANDOM FORESTS | scikit-learn (part of sklearn) 
STATSMODEL | statsmodels 
SKLEARN | scikit-learn 
SCIPYSTATS | scipy.stats


THANKYOU







