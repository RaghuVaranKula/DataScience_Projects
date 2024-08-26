# 💳 Credit Card Fraud Detection

## 📝 Overview
Credit card fraud poses significant financial risks and challenges. This project aims to detect fraudulent transactions using supervised machine learning techniques. Due to the highly imbalanced nature of the dataset, the focus is on choosing appropriate preprocessing techniques and evaluation metrics.

## 📊 Dataset
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Observations**: 284,807 transactions
- **Features**: 30 anonymized variables (V1-V28) + `Time`, `Amount`
- **Target**: `Class` (1 = Fraud, 0 = Legitimate)

## 📌 Objectives
- Preprocess and normalize credit card transaction data.
- Handle class imbalance using oversampling techniques like SMOTE.
- Train and evaluate different classification models.
- Use performance metrics tailored for imbalanced datasets (F1-Score, ROC-AUC).

## 🔧 Workflow
1. Data loading and preprocessing
2. EDA (Exploratory Data Analysis)
3. Handling imbalance with:
   - SMOTE
   - Random undersampling
4. Model training:
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Isolation Forest (optional)
5. Model evaluation and comparison
6. Final model export and visualization

## 🤖 Models Used
| Model               | Key Advantage                              |
|--------------------|---------------------------------------------|
| Logistic Regression| Baseline interpretable model                |
| Random Forest      | Handles imbalance, robust to outliers       |
| XGBoost            | Efficient and accurate boosting technique   |
| Isolation Forest   | Unsupervised anomaly detection (optional)   |

## 📈 Evaluation Metrics
- Precision, Recall, F1-Score
- ROC-AUC Curve
- Confusion Matrix

## 🚀 Getting Started

### 🔧 Installation
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt

##  📂 Project Structure

├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks
├── models/                 # Saved models
├── utils/                  # Helper functions
├── Credit Card Fraud Detection.ipynb
├── requirements.txt
└── README.md

##  📌 Future Improvements
- Deep learning-based classification (e.g., autoencoders)
- Deployment as a Streamlit or Flask web app
- Real-time fraud prediction pipeline

##  © License
This project is licensed under the MIT License.