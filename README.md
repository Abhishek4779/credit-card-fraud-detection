﻿# credit-card-fraud-detection

This project focuses on detecting fraudulent transactions in credit card datasets  
using multiple machine learning models and advanced preprocessing techniques.  
We analyze transaction patterns to distinguish between genuine and fraudulent activities.  
The dataset used is highly imbalanced, so techniques like SMOTE are applied.  
Models implemented include Random Forest, XGBoost, Logistic Regression, and LightGBM.  
Evaluation metrics like Precision, Recall, F1-Score, and ROC-AUC are used to assess performance.  
This project demonstrates a complete ML pipeline with visualization, feature engineering, and explainability.


---

## 📁 Project Structure

```
Fraud_Detection_ML/
├── Models/                   # saved .pkl model files
├── Plots/                    # confusion matrix, metrics, SHAP plots
├── Kaggle_Fraud.ipynb        # complete ML pipeline using Kaggle dataset
├── IEEE_Fraud.ipynb          # (IEEE-CIS work, private/not public)
├── requirements.txt
├── README.md
```
## 🛠️ Tech Stack

- **Python** – Core programming language  
- **Pandas & NumPy** – Data manipulation and numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – ML algorithms and model evaluation  
- **XGBoost & LightGBM** – Advanced gradient boosting models  
- **Imbalanced-learn (SMOTE)** – Handling class imbalance  
- **SHAP** – Model explainability and interpretation  
---

## 📊 Models Used

- ✅ Random Forest
- ✅ Logistic Regression
- ✅ XGBoost
- ✅ LightGBM

---

## 🔍 Key Features

- End-to-end pipeline: EDA, preprocessing, SMOTE balancing
- Model training + evaluation (Accuracy, Precision, Recall, ROC-AUC)
- Explainability using SHAP
- Confusion matrix and metrics comparison visualization
- High-quality plots saved in `/Plots/` and `/Plots/shap/`

---

## 📚 Datasets

### ✅ [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions
- Highly imbalanced dataset
- Public and used in this project

### 🔒 IEEE-CIS Fraud Detection
- Not public (Kaggle competition dataset)
- Processed privately, not uploaded to GitHub

---

## 💾 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📝 License

This project is for academic and educational purposes. Dataset licenses belong to their original owners.

---

## 🙋‍♂️ Author

**Abhishek P. Hendge**  
📧 abhishekhendge786@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-hendge)  
🔗 [GitHub](https://github.com/Abhishek4779)
