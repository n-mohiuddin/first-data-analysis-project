
# 🧠 Diabetes Prediction using Logistic Regression

This project uses the Pima Indians Diabetes Dataset to build a predictive model for diabetes diagnosis using clinical parameters.

---

## 📂 Dataset

- **File**: `diabetes.csv`
- **Target column**: `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

---

## 🔍 Project Steps

1. **Data Exploration**
   - View data types, missing values, and basic statistics
   - Visualize class imbalance
   - Detect invalid zero values in medical features

2. **Data Cleaning**
   - Replace biologically invalid zeros with NaN
   - Impute missing values:
     - Mean: `Glucose`, `BloodPressure`, `BMI`
     - Median: `SkinThickness`, `Insulin`

3. **Feature Scaling**
   - Applied `StandardScaler` for normalization

4. **Modeling**
   - Used Logistic Regression
   - Evaluated using 5-fold Stratified Cross-Validation
   - Metrics: Accuracy, Precision, Recall, F1-score

5. **Final Prediction**
   - Trained on full dataset
   - Predicted diabetes on a new sample input

---

## 📈 Results Example

```
Prediction: Non-Diabetic
Diabetes Probability: 0.2705
```

---

## ▶️ How to Run

1. Clone this repo or download the notebook.
2. Place the `diabetes.csv` file in the same folder.
3. Open `diabetes_analysis_english.ipynb` in Jupyter or Google Colab.
4. Run all cells.

---

## 💻 Requirements

Install required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📁 File Structure

```
📦 diabetes-prediction/
├── diabetes_analysis_english.ipynb
├── diabetes.csv
└── README.md
```

---

## 🧑‍💻 Author

Nezihe Mohiuddin
