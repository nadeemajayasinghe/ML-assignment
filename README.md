\# 🍷 Wine Quality Prediction using Machine Learning



\## 📌 Project Overview

This project focuses on predicting wine quality using multiple Machine Learning algorithms. The dataset contains physicochemical properties of wine, and the goal is to classify whether a wine is of good or bad quality.



\---



\## 🎯 Objective

\- Apply multiple Machine Learning algorithms on the same dataset

\- Compare their performance using evaluation metrics

\- Identify the best-performing model



\---



\## 📂 Dataset

\- Source: UCI Machine Learning Repository  

\- Link: https://archive.ics.uci.edu/ml/datasets/wine+quality 

\- Dataset: Wine Quality Dataset  

\- Files used:

&#x20; - `winequality-red.csv`

&#x20; - `winequality-white.csv`



\### 📊 Features:

\- Fixed acidity

\- Volatile acidity

\- Citric acid

\- Residual sugar

\- Chlorides

\- Free sulfur dioxide

\- Total sulfur dioxide

\- Density

\- pH

\- Sulphates

\- Alcohol



\### 🎯 Target:

\- Wine Quality (Converted to binary classification)

&#x20; - Good Wine (1): Quality ≥ 6

&#x20; - Bad Wine (0): Quality < 6



\---



\## ⚙️ Machine Learning Models Used



| Model | Description |

|------|------------|

| Logistic Regression | Baseline linear model |

| Decision Tree | Rule-based model |

| Random Forest | Ensemble learning method |

| Support Vector Machine (SVM) | Margin-based classifier |



\---



\## 🛠️ Technologies Used

\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib

\- Seaborn



\---



\## 📊 Evaluation Metrics

\- Accuracy

\- Confusion Matrix

\- Precision, Recall, F1-score

\- ROC Curve

\- Cross Validation



\---



\## 📈 Results Summary



| Model | Accuracy |

|------|----------|

| Random Forest | \~83% |

| SVM (Tuned) | \~78% |

| Logistic Regression | \~72% |

| Decision Tree | \~77% |



\---



\## 🏆 Best Model

Random Forest achieved the highest accuracy and provided strong performance due to its ability to handle non-linear relationships and reduce overfitting.



\---



\## 🧠 Key Insights

\- Ensemble methods outperform simple models

\- Logistic Regression provides interpretability

\- SVM performs well with tuned parameters

\- Dataset contains non-linear relationships



\---



\## ▶️ How to Run the Project



1\. Clone the repository:

```bash

git clone https://github.com/nadeemajayasinghe/ML-assignment.git

cd ML-assignment

