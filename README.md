# 🧠 Logistic Regression Model - Purchase Prediction

This project demonstrates a **Logistic Regression** model built using Python and Scikit-learn to predict whether a customer will make a purchase based on their demographic and behavioral data.

---

## 📂 Project Files

| File Name | Description |
|------------|--------------|
| `logistic_dataset.xlsx` | Dataset used for training the model |
| `logistic_wk.ipynb` | Jupyter Notebook containing preprocessing, model training, and evaluation |
| `Probabilitiy_of_purchase_joblib` | Trained Logistic Regression model saved using joblib |

---

## 🧩 Model Overview

**Algorithm Used:** Logistic Regression  
**Goal:** Predict whether a user will purchase a product (`Purchased = 1`) or not (`Purchased = 0`)

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Logistic-Regression-Model.git
   cd Logistic-Regression-Model
2. open jupyter notebook
   jupyter notebook logistic_wk.ipynb
3.Install required libraries
   pip install pandas numpy scikit-learn joblib matplotlib
4. Run to see all output

Output

Model accuracy score
Confusion matrix
Visualization of prediction probabilities

6. Model Deployment

You can load the saved model and use it for prediction:
import joblib
model = joblib.load('Probabilitiy_of_purchase_joblib')

# Example prediction
input_data = [[35, 50000, 1]]  # Example age, salary, gender
print(model.predict(input_data))

