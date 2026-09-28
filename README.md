# Assignment 3 – Regression Model for Startup Profit

## TY B.Tech – Artificial Intelligence and Machine Learning

### 1. Title

**Prediction of Startup Profit using Linear Regression**

---

## 2. Problem Statement

Develop a regression model to predict the profit of a startup based on its research and development spending, administration spending, marketing spending, and state.

The performance of the regression model is evaluated using appropriate regression metrics.

---

## 3. Objective

* To understand regression using a real-world dataset.
* To perform data preprocessing and exploratory data analysis.
* To identify the relationship between startup expenses and profit.
* To develop a Linear Regression model.
* To evaluate the model using appropriate performance metrics.
* To visualize the actual and predicted profit values.

---

## 4. Dataset

The project uses the **50 Startups** dataset.

### Features

| Feature         | Description                             |
| --------------- | --------------------------------------- |
| R&D Spend       | Money spent on research and development |
| Administration  | Money spent on administration           |
| Marketing Spend | Money spent on marketing                |
| State           | State in which the startup operates     |

### Target Variable

**Profit** – Profit earned by the startup.

---

## 5. Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 6. Machine Learning Model

### Linear Regression

Linear Regression is used to establish a relationship between the independent variables and the target variable, Profit.

The general equation is:

```text
y = b0 + b1x1 + b2x2 + ... + bnxn
```

Where:

* `y` = predicted profit
* `b0` = intercept
* `b1, b2, ...` = model coefficients
* `x1, x2, ...` = input features

---

## 7. Data Preprocessing

The following preprocessing steps are performed:

1. Load the dataset.
2. Check the dataset for missing values.
3. Separate independent and dependent variables.
4. Convert the categorical `State` column into numerical form using encoding.
5. Split the data into training and testing sets.
6. Train the Linear Regression model.
7. Predict startup profit for the test data.

---

## 8. Model Evaluation

The model is evaluated using the following metrics:

### Mean Absolute Error (MAE)

MAE measures the average absolute difference between actual and predicted values.

```text
MAE = Average(|Actual - Predicted|)
```

Lower MAE indicates smaller prediction errors.

### Mean Squared Error (MSE)

MSE calculates the average squared difference between actual and predicted values.

```text
MSE = Average((Actual - Predicted)²)
```

Lower MSE indicates better prediction performance.

### Root Mean Squared Error (RMSE)

RMSE is the square root of MSE.

```text
RMSE = √MSE
```

### R² Score

R² score represents how well the model explains the variation in the target variable.

A value closer to 1 indicates that the model explains a larger proportion of the variation in the target data.

---

## 9. Visualization

The project includes visualizations such as:

* Distribution of startup profit
* Correlation between numerical variables
* Actual vs Predicted Profit
* Regression model performance

The **Actual vs Predicted Profit** graph helps compare the model predictions with the actual profit values.

---

## 10. Project Structure

```text
Assignment-3-Startup-Profit-Regression/
│
├── Startup_Profit_Regression.ipynb
├── 50_Startups.csv
├── README.md
└── screenshots/
    ├── dataset.png
    ├── correlation.png
    ├── actual_vs_predicted.png
    └── model_output.png
```

---

## 11. How to Run

### Using Google Colab

1. Open the `.ipynb` file in Google Colab.
2. Upload `50_Startups.csv`.
3. Run the notebook cells in order.
4. Check the preprocessing, training, evaluation and visualization outputs.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Then open:

```text
Startup_Profit_Regression.ipynb
```

and run all cells.

---

## 12. Sample Input

The model takes the following information as input:

```text
R&D Spend
Administration
Marketing Spend
State
```

For example:

```text
R&D Spend: 165349.20
Administration: 136897.80
Marketing Spend: 471784.10
State: New York
```

The model predicts the corresponding startup profit.

---

## 13. Output

The notebook displays:

* Dataset information
* Preprocessed data
* Training and testing results
* MAE
* MSE
* RMSE
* R² Score
* Actual and predicted profit values
* Graphs for model evaluation

> The exact metric values should be taken from the output of the notebook.

---

## 14. Result

A Linear Regression model was successfully developed to predict startup profit using the available startup expenditure and state-related information.

The performance of the model was evaluated using MAE, MSE, RMSE and R² Score. The Actual vs Predicted graph was also used to visually analyze the prediction performance.

---

## 15. Learning Outcomes

After completing this assignment, I learned:

* How regression can be applied to a real-world problem.
* How to preprocess a dataset before applying machine learning.
* How categorical data can be converted into numerical form.
* How to train a Linear Regression model.
* How to predict continuous values.
* How to evaluate a regression model using different metrics.
* How to visualize actual and predicted results.

---

## 16. Conclusion

In this assignment, Linear Regression was implemented for predicting startup profit. The 50 Startups dataset was preprocessed and divided into training and testing data. The model was trained using startup expenditure-related features and evaluated using suitable regression metrics.

The results show how machine learning can be used to estimate startup profit based on available business expenditure data.

---

## 17. Author

**Sanika Laxman Chavan**
TY B.Tech – Artificial Intelligence and Machine Learning
MIT Academy of Engineering, Alandi
Division: A | Batch: A3
