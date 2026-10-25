# House Price Prediction

## Project Overview

This project focuses on predicting house prices using machine learning techniques. It explores housing data, applies data preprocessing and feature engineering, and builds regression models to estimate house prices.

The project demonstrates a complete machine learning workflow, from exploratory data analysis to model evaluation and error analysis.

## Objectives

- Explore and understand housing data.
- Perform data cleaning and preprocessing.
- Apply feature engineering techniques.
- Build and compare regression models.
- Perform hyperparameter tuning.
- Evaluate model performance and analyze prediction errors.

## Machine Learning Models

The project explores the following regression algorithms:

- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor

These models are used to compare different approaches to predicting house prices.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Development Environment:** Jupyter Notebook

## Project Workflow

1. **Data Loading:** Load the housing dataset and inspect its structure.
2. **Exploratory Data Analysis:** Explore data distributions, relationships, and potential data quality issues.
3. **Data Preprocessing:** Prepare the data for machine learning.
4. **Feature Engineering:** Transform and create relevant features.
5. **Model Building:** Train regression models using the prepared dataset.
6. **Model Comparison:** Compare model performance using appropriate evaluation metrics.
7. **Hyperparameter Tuning:** Optimize model parameters.
8. **Error Analysis:** Examine prediction errors to understand model behaviour.

## Repository Structure

```text
house-price-prediction/
│
├── README.md
├── requirements.txt
├── house_price_prediction.ipynb
```

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <YOUR-REPOSITORY-URL>
cd house-price-prediction
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Prepare the Dataset

Place the dataset in your local `data/` directory and ensure that the file path in the notebook matches its location.

The dataset is not included in this repository. Only use datasets you are authorized to access and share.

### 5. Run the Notebook

```bash
jupyter notebook
```

Open `house_price_prediction.ipynb` and execute the cells in sequence.

## Key Learnings

- Exploratory data analysis and data preprocessing
- Feature engineering
- Regression modelling
- Regularization techniques using Ridge and Lasso
- Tree-based ensemble methods
- Hyperparameter tuning
- Model evaluation and error analysis

## Conclusion

This project provides practical experience in applying regression techniques to a house price prediction problem. It demonstrates the process of preparing data, building and comparing machine learning models, and evaluating their predictive performance.

## Author

**Srinivas Panchangam**

- **LinkedIn:** [Srinivas Panchangam](https://www.linkedin.com/in/srinivas-panchangam-271a262b4/)
