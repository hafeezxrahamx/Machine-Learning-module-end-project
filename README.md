# Machine-Learning-module-end-project
# Car Price Prediction Project

## Overview
This project aims to predict car prices based on various features using multiple machine learning regression models. By analyzing different car attributes, the objective is to determine the key factors influencing car prices and develop an accurate predictive model.

## Dataset
- The dataset is stored in `car_price_dataset.csv`.
- It contains both categorical and numerical variables.
- The target variable is `price`.

## Project Workflow

### 1. Data Loading and Preprocessing
- Load the dataset using Pandas.
- Check for and handle missing values.
- Identify categorical and numerical columns.
- Apply preprocessing techniques:
  - StandardScaler for numerical data.
  - OneHotEncoder for categorical data.

### 2. Model Implementation
The following regression models are implemented:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor**

Each model is trained using a pipeline that integrates preprocessing and training.

### 3. Model Evaluation
The models are evaluated using the following metrics:
- **R-squared (R²)**
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

The performance of all models is compared to select the best one.

### 4. Hyperparameter Tuning
- The best-performing model undergoes hyperparameter tuning using GridSearchCV.
- The tuned model is evaluated again to check for performance improvements.

### 5. Feature Importance Analysis
- The best model’s feature importances are analyzed.
- A bar chart is plotted to visualize the most influential factors in determining car prices.

## Results
- Model performances are stored in a Pandas DataFrame.
- The best model is identified based on the R² score and other evaluation metrics.
- Feature importance analysis highlights the key predictors of car prices.

## Installation
Ensure you have the required Python libraries installed:
```bash
pip install -r requirements.txt
```
Alternatively, install the required libraries individually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-price-prediction
   ```
3. Place the dataset (`car_price_dataset.csv`) in the project directory.
4. Run the script in a Jupyter Notebook or as a standalone Python script.
5. Review the model evaluation results and feature importance analysis.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Make your changes and commit them.
4. Push the changes and open a pull request.

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

---
**Maintainer:** Hafeez Rahman S H ()

