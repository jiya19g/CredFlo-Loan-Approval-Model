
# **CredFlo Loan Approval Model**

This project aims to build and evaluate multiple machine learning models for loan approval prediction. The goal is to predict whether a loan applicant will be approved or rejected based on various features such as credit history, income, and other personal details.

## **Technologies Used**

- **Python**
- **TensorFlow (Keras)**
- **Scikit-learn**
- **XGBoost**
- **SHAP (Shapley Additive Explanations)**
- **Matplotlib** (for plotting)

## **Project Structure**

1. **Model1** (Logistic Regression)
   - A logistic regression model trained using standard machine learning techniques.
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score.
   - Performance visualization using ROC curve and confusion matrix.

2. **Model2** (Random Forest)
   - A Random Forest classifier used for loan approval predictions.
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score.
   - Performance visualization using ROC curve and confusion matrix.

3. **Model3** (XGBoost)
   - An XGBoost model for loan approval prediction.
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score.
   - Performance visualization using ROC curve and confusion matrix.

4. **Model4** (Neural Network using TensorFlow)
   - A Neural Network model built with TensorFlow (Keras).
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score.
   - Performance visualization using ROC curve and confusion matrix.

5. **SHAP Interpretability**
   - SHAP (Shapley Additive Explanations) values are used to interpret the models' predictions and understand feature importance.

## **How to Run**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CredFlo-Loan-Approval-Model.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Train and evaluate the models:
   - You can run each model script separately to train and evaluate the models.
   - The performance metrics and plots will be saved after each run.

## **Evaluation and Metrics**

- **Accuracy**: Measures the percentage of correctly predicted loan approval statuses.
- **Precision**: Measures the proportion of true positive predictions in relation to all positive predictions.
- **Recall**: Measures the proportion of true positive predictions in relation to all actual positive cases.
- **F1-score**: Harmonic mean of Precision and Recall, providing a balanced measure of a model's performance.

## **Results**

The models have been trained on the loan approval dataset, and each model's performance has been compared using the metrics mentioned above.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
