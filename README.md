# 🎓 Student Performance Analysis Dashboard

**Academic Performance Prediction with Python & Power BI** combining Python data cleaning & Random Forest modeling with an interactive Power BI dashboard.

---

## 🔎 Project summary
This project predicts student CGPA using survey features (attendance, previous SGPA, study hours, family income, etc.). It includes:
- A Jupyter Notebook for data cleaning, EDA, modeling and saving outputs.
- A Random Forest model trained to predict current CGPA.
- A Power BI dashboard that visualizes dataset insights and model predictions.

---

## 📁 Project structure

```
Student_Project/
│
├── outputs/ # All model outputs & CSVs
│   ├── student_performance_clean.csv
│   ├── rf_feature_importance.csv
│   ├── student_predictions_rf.csv
│   └── random_forest_model.joblib
│
├── Student_Python.ipynb               # Jupyter Notebook (cleaning + modeling)
├── student_performance_dashboard.pbix # Power BI Dashboard
├── Students_Performance_data_set.xlsx # Raw Dataset
└── README.md                          # Project documentation
```

---

## ⚙️ Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Student_Performance_Dashboard.git
   cd Student_Performance_Dashboard
   ```

---

## 📊 Dashboard Highlights

* **Feature Importance**: Previous SGPA is the strongest predictor (~66%).
* **Model Accuracy**: R² ≈ 0.77, MAE ≈ 0.15 CGPA points.
* **Visuals**: Distribution of CGPA, Actual vs Predicted, Residual analysis.
* **Filters**: Gender, Performance level, Current Semester.

---

## ✅ Conclusion

* The model performs well with residuals centered around 0.
* Previous SGPA, credits completed, and attendance are key predictors of CGPA.
* The combination of Python + Power BI provides both analytical depth and interactive storytelling.

---

## 📌 Author

👤 Malika Shivarla  
🔗 [GitHub](https://github.com/malika713189)
