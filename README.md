---

# **CredFlo - Loan Approval Model**

This project aims to build and evaluate multiple machine learning models for loan approval prediction. The goal is to predict whether a loan applicant will be approved or rejected based on various features such as credit history, income, and other personal details.

## **Technologies Used**

- **Python**
- **TensorFlow (Keras)**
- **Scikit-learn**
- **XGBoost**
- **SHAP (Shapley Additive Explanations)**
- **Matplotlib** (for plotting)

## **Project Structure**

1. **Model1: Logistic Regression**  
   - A logistic regression model is trained using the dataset to predict loan approval.

2. **Model2: Random Forest, XGBoost, and Neural Network**  
   - Multiple models (Random Forest, XGBoost, Neural Network) are trained and evaluated to compare performance.

## **Key Metrics & Evaluation**

### **Model Performance**
- **Accuracy, Precision, Recall, F1 Score**: Evaluates how well the model performs on both training and test data.
- **Confusion Matrix**: Visualizes the true positive, true negative, false positive, and false negative predictions.
- **Precision-Recall Curve**: Measures the balance between precision and recall.
- **ROC Curve and AUC**: Evaluates the true positive rate vs. false positive rate, with AUC indicating model performance.

### **Feature Importance**
- **SHAP Analysis**: Used to interpret model predictions and understand which features are most influential in loan approval decisions.

## **Model Training and Evaluation Workflow**
1. **Data Preprocessing**: Prepare and clean the dataset for model training.
2. **Model Training**: Train Logistic Regression, Random Forest, XGBoost, and Neural Network models.
3. **Evaluation**: Evaluate the models using accuracy, precision, recall, F1 score, confusion matrix, ROC-AUC, and SHAP feature importance.
4. **Comparison**: Compare the performance of all models based on selected metrics.

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CredFlo-Loan-Approval-Model.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

Run the `model1.py` and `model2.py` files to train and evaluate the models. Ensure that the dataset is correctly placed in the directory or update the path in the scripts accordingly.

### **Model1 (Logistic Regression)**:
```bash
python model1.py
```

### **Model2 (Random Forest, XGBoost, Neural Network)**:
```bash
python model2.py
```

## **Results**
- The performance of the models will be printed out, along with the visualizations for each evaluation metric.
- The SHAP summary plot will show feature importance for the models.

## **Contributors**
- [Jiya Gayawer]
- [Akshat Neolia]
---
