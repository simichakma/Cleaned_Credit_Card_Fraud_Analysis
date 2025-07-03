# 💳 Credit Card Fraud Detection

This project is part of my final year submission, focused on detecting fraudulent transactions using machine learning models such as Logistic Regression, Random Forest, XGBoost, CatBoost, LightGBM. The goal is to build a system that can effectively identify fraudulent transactions from a highly imbalanced dataset.

---

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains transactions made by European cardholders in September 2013.
- Total Records: 284,807 transactions  
- Fraudulent Transactions: 492 (0.172%)

---

## 🧠 Models Used

- Logistic Regression  
- Random Forest  
- Decision Tree  
- XGBoost  
- CatBoost  
- LightGBM  

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Confusion Matrix**  
- **Precision** (%)
- **Recall** (%)
- **F1-Score** (%)

Each model was evaluated on how well it detects fraudulent vs. non-fraudulent transactions, using the imbalanced dataset strategy (with scaling and stratified train-test split).

---

## 🛠️ Technologies & Libraries

- Python  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- TensorFlow/Keras  
- XGBoost, CatBoost, LightGBM

---

## 📈 Results Summary (Example)

| Model           | Precision (%) | Recall (%) | F1-Score (%) | Test Accuracy (%) |
|----------------|---------------|------------|--------------|-------------------|
| Logistic Reg.   | 89.32         | 74.51      | 81.23        | 99.29             |
| Random Forest   | 93.25         | 82.67      | 87.63        | 99.91             |
| XGBoost         | 94.80         | 84.00      | 89.07        | 99.93             |
| CatBoost        | 95.10         | 85.34      | 89.94        | 99.94             |
| LightGBM        | 94.67         | 83.99      | 88.93        | 99.92             |

> 📌 Note: These are sample values — replace with your real results.

---

## 📦 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/Credit_Card_Fraud_Analysis.git
cd Credit_Card_Fraud_Analysis

# 2. Install required packages
pip install -r requirements.txt

# 3. Run the Jupyter Notebook or .py script
