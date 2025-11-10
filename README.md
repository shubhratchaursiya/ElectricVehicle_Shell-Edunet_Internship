```
# Week 2 – EV Charging Stations Project  
**Author:** Shubhrat Chaursiya  
**Project:** Electric Vehicle Charging Stations – Shell-Edunet Internship  
**Week:** 2 — Model Selection & Building  
**Prerequisite (Week 1):** Data cleaning, EDA & clustering of EV charging station dataset

---

## 🎯 Objectives for Week 2  
- Research and select appropriate machine learning models for the charging-station dataset.  
- Implement a baseline regression model (for example: predicting station power or usage) and evaluate its performance.  
- Train additional models (e.g., Random Forest, Gradient Boosting) and perform feature engineering to enhance performance.  
- Apply cross-validation for reliable model evaluation and compare results.

---

## 📂 Project Structure  
```

/Week2/
│
├── Week2_Model_Selection.ipynb      # Jupyter notebook with modelling workflow
├── datasets/                        # (Optional) folder for raw/processed datasets
│   └── EV_Charging_Stations_with_Clusters.csv
├── models/                          # (Optional) folder to store trained model files
│   └── best_model.pkl
├── README.md                        # This documentation file
└── outputs/                         # (Optional) folder for outputs, charts etc.
└── feature_importance.png

````

---

## 🛠️ How to Run  
1. Ensure you have the cleaned dataset from **Week 1** (`EV_Charging_Stations_with_Clusters.csv`).  
2. Install required libraries if not already followed:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
````

3. Open the notebook: `Week2_Model_Selection.ipynb` in Jupyter or Colab.
4. Run through the notebook and examine:

   * Baseline model training & evaluation
   * Feature engineering steps
   * Model comparisons and selection
   * Final chosen model saved to `models/best_model.pkl`
5. Review outputs in the `outputs/` folder (charts, logs, etc.).

---

## 📌 Key Highlights

* Baseline model established (e.g., Linear Regression) to set performance benchmark.
* Feature engineering applied (e.g., encoding connector types, power bins, geographic clusters).
* Advanced models trained and compared (e.g., Random Forest, Gradient Boosting).
* Cross-validation used for robust evaluation of metrics such as RMSE, MAE, R².
* Final model serialized for potential deployment in Week 3/4.

---

## 🔍 Improvements Introduced in Week 2

* Introduced supervised machine learning predictive modelling (regression) instead of just clustering.
* Enhanced feature set with engineered variables (example: cluster_id, power_kW bin, connector count).
* Performed hyper-parameter tuning and model comparison to identify best-fit algorithm.
* Adopted cross-validation to reduce over-fitting and assess model generalisation.
* Stored final model and created visual artefacts (feature importance plot) for interpretability.

---

## 🚀 Next Steps (Week 3 Preview)

* Model evaluation and optimisation: apply more advanced techniques (ensembles, boosting).
* Perform error analysis, diagnose under-/over-fitting issues.
* Interpret model output: feature importance, partial dependence, SHAP values etc.
* Prepare final deliverables: dashboard/PPT/report and code for deployment or demonstration.

---

## 📄 Licence & Acknowledgements

Dataset (EV Charging Stations 2024) sourced from Kaggle.
Project performed under the Shell-Edunet Skills4Future Internship.
Feel free to explore and extend the work further.


---

## 📫 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/shubhrat-chaursiya-819672354/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="28" height="28" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/shubhratchaursiya" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" width="28" height="28" alt="GitHub" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:shubhratchuarsiya2005@gmail.com">
    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="28" height="28" alt="Email" />
  </a>
</p>

---
