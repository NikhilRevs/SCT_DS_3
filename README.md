# Bank Marketing Campaign - Decision Tree Classifier

## 📌 Overview
This project builds a decision tree model to predict whether a bank client will subscribe to a term deposit (`yes` or `no`). It uses the UCI Bank Marketing dataset and applies basic preprocessing and visualization to enhance model interpretability.

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Features include client demographics, contact information, and campaign details.
- Target variable: `y` (whether the client subscribed)

## 🧠 Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib

## ⚙️ Steps
1. Load dataset with proper delimiter (`;`)
2. Encode categorical variables using `pd.get_dummies`
3. Split into training/testing sets
4. Train a decision tree classifier
5. Visualize both unpruned and pruned trees using `plot_tree`

## 📈 Output
- Accuracy scores for both models
- Decision tree visualizations for interpretability

## 🚀 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Ensemble methods (Random Forest, Gradient Boosting)
