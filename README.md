
# 🫀 ECG Arrhythmia Classification using Machine Learning

[![View Notebook](https://img.shields.io/badge/View--on--GitHub-Machine%20Learning%20Notebook-blue?logo=github)](https://github.com/bongssss/ML-/blob/main/Arrythmia%20Machine%20Learning.ipynb)

## 📌 Overview

This project implements and evaluates multiple supervised machine learning models to classify heartbeat signals from ECG (Electrocardiogram) data into arrhythmia types using the **MIT-BIH Arrhythmia Dataset**.

The project was completed as part of the assessment for the **Principles of Data Mining and Machine Learning** module (MOD 007892) at Anglia Ruskin University.

---

## 📄 Assessment Requirements & Implementation Summary

### ✅ Jupyter Notebook Tasks

| Requirement                                                                                   | Implementation Summary                                                                                   |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| 1. **Download the Dataset**                                                                   | Downloaded from [Kaggle MIT-BIH](https://www.kaggle.com/datasets/shayanfazeli/heartbeat/data)            |
| 2. **EDA and Visualization**                                                                  | Data merged, null values checked, class distributions plotted, correlation matrix visualized             |
| 3. **Pre-processing**                                                                         | Label encoding, feature-target split, normalization, class balancing suggestions noted                   |
| 4. **ML Algorithm Development**                                                               | Implemented 3 classifiers: Random Forest, Support Vector Machine (SVM), Multi-Layer Perceptron (MLP)     |
| 5. **Novel Contributions**                                                                    | Ensemble testing, performance metrics analysis, class imbalance analysis                                 |
| 6. **Performance Comparison**                                                                 | Used Accuracy, Precision, Recall, F1 Score, Confusion Matrices                                            |

---

### 📘 Written Report Summary

| Section                         | Summary                                                                                                                                       |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| **Introduction**                | Addresses the prevalence and fatal risk of arrhythmia and the need for accurate early classification using ML.                              |
| **EDA & Data Visualization**    | Shows ECG signal graphs, heartbeat class distribution, and highlights dataset imbalance (majority class: normal)                            |
| **Implementation**              | Describes full ML pipeline: data cleaning → correlation matrix → model building with math formulas                                           |
| **Results**                     | MLP achieved highest accuracy (98%), followed by RF and SVM (97%). Performance metrics visualized and discussed per class                    |
| **Conclusion**                  | Suggested upsampling, label encoding for improved class balance and interpretability. Highlighted class imbalance as performance limiter.   |
| **References**                  | Includes academic and industry sources for ML theory and ECG domain knowledge                                                               |

---

## 📈 Key Metrics

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| **MLP (Neural Net)**| 98%      | High      | High   | Highest  |
| **Random Forest**   | 97%      | High      | High   | High     |
| **SVM**             | 97%      | High      | Moderate| Moderate |

---

## 🧪 Machine Learning Models Used

- **Random Forest Classifier (RF)**
- **Multi-Layer Perceptron (MLP)**
- **Support Vector Machine (SVM)**

---

## 🧠 Dataset Classes

| Class | Description         | Label |
|-------|---------------------|-------|
| N     | Normal              | 0     |
| S     | Supraventricular    | 1     |
| V     | Ventricular         | 2     |
| F     | Fusion              | 3     |
| Q     | Unknown             | 4     |

---

## 📎 Links

- 🔗 **Notebook**: [Arrhythmia Machine Learning.ipynb](https://github.com/bongssss/ML-/blob/main/Arrythmia%20Machine%20Learning.ipynb)
- 🔗 **Dataset**: [Kaggle – MIT-BIH Heartbeat Dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat/data)
- 📄 **Report PDF**: *Available on request or in coursework submission*

---

## 🗃️ Submission Checklist (as per brief)

- ✅ Jupyter Notebook  
- ✅ Written Report PDF  
- ✅ Lab Logbook with GitHub link

---

## 📚 References

Key references include:
- MIT-BIH Dataset documentation
- Random Forests (Cutler)
- MLP (Prof. Alex Bronstein)
- SVMs (Tristan Fletcher)
- Performance metrics (Analytics Vidhya, Eugenio Zuccarelli)

