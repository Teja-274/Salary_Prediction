
# Salary Prediction Using Machine Learning

## Project Overview
This project predicts employee salaries based on various factors such as **Age**, **Gender**, **Degree**, **Job Title**, and **Experience** using machine learning models.

This README outlines the necessary steps to set up the project, run the code, and ensure that dependencies are installed properly.

---

## Dependencies
The project requires the following Python libraries:
- **Python 3.8+**
- **pandas**: For data manipulation and analysis  
- **numpy**: For numerical computations  
- **matplotlib**: For data visualization  
- **seaborn**: For advanced visualizations  
- **scikit-learn**: For implementing machine learning models  
- **xgboost**: For using the XGBoost regressor  

Installed the dependencies using the following command:
```
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

## Code Execution Instructions

### Step 1: Clone the Repository
Download the project from the repository:
```
git clone https://github.com/your-repo-name/salary-prediction.git
cd salary-prediction
```

### Step 2: Prepare the Dataset
Ensure that the dataset file (`Salary_Pred.csv`) is placed in the same directory as the code.

### Step 3: Open the Code
You can execute the project using either a **Jupyter Notebook** or a **Python script**.

- For **Jupyter Notebook**:
  ```
  jupyter notebook salary_prediction.ipynb
  ```

- For **Python Script**:
  ```
  python salary_prediction.py
  ```

### Step 4: Run the Code
Follow the sequence of code execution:

#### a) Data Preprocessing
- Load the dataset.
- Handle missing values using `df.dropna()` or imputation methods.
- Normalize numerical columns like **Age** and **Experience** using **Min-Max Scaling**.

#### b) Train-Test Split
- Divide the dataset into training and testing sets using `train_test_split`.

#### c) Model Training
Train the following machine learning models:
1. Linear Regression  
2. Random Forest Regressor  
3. XGBoost Regressor  

#### d) Model Evaluation
Evaluate the models using metrics such as:
- **Root Mean Square Error (RMSE)**  
- **R² Score**

#### e) Visualization
Generate visualizations such as:
- Feature importance (bar chart)  
- Histograms for each feature  
- Salary distribution by degree (boxplot)  

### Step 5: View Results
After running the code, you will get the following:
- Predicted salaries for the test dataset.
- Model evaluation scores (**RMSE**, **R²**).

