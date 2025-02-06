
# CredFlo Loan Approval Model

This project aims to build and evaluate multiple machine learning models for loan approval prediction. The goal is to predict whether a loan applicant will be approved or rejected based on various features such as credit history, income, and other personal details.

## Technologies Used

- Python
- Pandas
- Numpy
- Scikit-learn
- TensorFlow (for neural networks)
- SHAP (for feature importance visualization)
- Matplotlib (for data visualization)
- XGBoost (for model training)
- Random Forest (for model training)
- Logistic Regression (for model training)

## Project Structure

1. **Data Preprocessing**: The dataset is cleaned and preprocessed, handling missing values, encoding categorical variables, and scaling features as necessary.
2. **Model Training**: Multiple models (Logistic Regression, Random Forest, XGBoost, Neural Network) are trained and evaluated.
3. **Evaluation Metrics**: The models are evaluated using various metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
4. **Feature Importance**: SHAP values are used to interpret and visualize feature importance for each model.
5. **Model Comparison**: The models' performances are compared, and the best-performing model is selected.
6. **Deployment**: Not covered in this repository, but the models can be integrated into a production environment for loan approval predictions.

## Requirements

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- TensorFlow
- SHAP
- Matplotlib
- XGBoost

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script to train and evaluate models:
   ```bash
   python main.py
   ```

## License

This project is licensed under the MIT License.
