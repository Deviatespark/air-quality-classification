# 🌫️ Air Quality Classification in Madrid

This project applies decision tree-based classification models to analyze and predict air quality levels based on pollutant data from Madrid.

---

## 📁 Project Structure

```
air-quality-classification/
├── data/
│   └── estaciones_madrid.csv
├── notebook/
│   └── air_quality_classification.ipynb
├── models/
│   └── decision_tree_model.pkl (optional)
├── outputs/
│   ├── no2_distribution_station_16.png
│   ├── correlation_matrix.png
│   ├── confusion_matrix.png
│   ├── decision_tree_plot.png
│   ├── confusion_matrix_without_nox.png
│   └── confusion_matrix_random_forest.png
├── report/
│   └── EN_Air_Quality_Classification_Report_Sergio_Galvez.pdf
│   └── ES_Air_Quality_Classification_Report_Sergio_Galvez.pdf
├── README.md
└── requirements.txt (optional)
```

---

## 📊 Objective

Predict air quality levels (NO2) by training and evaluating classification models using real pollutant data from Madrid. The NO2 variable was discretized into 3 levels: **low**, **medium**, and **high**.

---

## 🔧 Models Used

- `DecisionTreeClassifier`
- `RandomForestClassifier`

Both models were trained and evaluated with and without the most correlated feature (`nox`) to measure its impact on performance.

---

## 📈 Key Results

- ✅ Decision Tree accuracy: **94%**
- ✅ Random Forest accuracy: **94%**
- 📉 Accuracy without `nox`: **76%**

Confusion matrices and the tree plot are available in the `outputs/` folder.

---

## 📄 Full Report

Detailed reports summarizing the methodology, data transformation, analysis, and results are available below:

- 📘 [Read the full report in English](report/EN_Air_Quality_Classification_Report_Sergio_Galvez.pdf)
- 📙 [Leer el informe completo en español](report/ES_Air_Quality_Classification_Report_Sergio_Galvez.pdff)

---

## ✍️ Author

Developed by **Sergio Gálvez Reguera**  
As part of an academic project, structured and documented for professional use.

