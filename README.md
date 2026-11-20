# Experiment 3: Regression Techniques in Business Data(Simple Linear Regression)

##  Aim
To implement Simple Linear Regression in Python to study and predict the relationship between two business-related variables.

## Dataset
A sample business dataset representing the relationship between **Advertising Expenditure** (in Lakhs) and **Sales Revenue** (in Crores). The goal is to analyze how changes in advertising investment affect sales performance.

| Index | Advertising (Lakhs) | Sales (Crores) |
| :---: | :---: | :---: |
| 0 | 18 | 12 |
| 1 | 22 | 18 |
| 2 | 25 | 20 |
| 3 | 30 | 24 |
| 4 | 35 | 28 |
| 5 | 40 | 35 |
| 6 | 45 | 38 |
| 7 | 50 | 40 |
| 8 | 55 | 42 |
| 9 | 60 | 45 |

## Algorithm / Steps Followed
1. Import required Python libraries (`numpy`, `pandas`, `matplotlib`, `scikit-learn`).
2. Create and load the dataset into a Pandas DataFrame.
3. Display the dataset.
4. Select independent ($X$) and dependent ($Y$) variables and reshape $X$ into a 2D array.
5. Build a `LinearRegression` model using `sklearn.linear_model`.
6. Fit the model and calculate the intercept ($a$) and slope ($b$).
7. Predict $Y$ values for given $X$ values and evaluate performance using the $R^2$ score.
8. Plot the actual data points alongside the fitted regression line and predict sales for a new advertising budget.

##  Functions and Methods Used

| Category | Function / Method | Purpose / Description |
| :--- | :--- | :--- |
| **Data Creation / Handling** | `np.array()` | Create numerical arrays for regression input data |
| | `pd.DataFrame()` | Create or manage tabular data for regression |
| **Model Building (Scikit-learn)** | `LinearRegression()` | Initialize the Simple Linear Regression model |
| | `model.fit()` | Train the linear regression model using $X$ and $Y$ values |
| | `model.predict()` | Predict $Y$ values for given $X$ inputs using the fitted model |
| | `model.score()` | Calculate model performance ($R^2$ score) |
| **Visualization (Matplotlib)** | `plt.scatter()` | Plot scatter points (actual data points) |
| | `plt.plot()` | Plot regression line (predicted relationship) |
| | `plt.title()`, `plt.xlabel()`, `plt.ylabel()`, `plt.show()` | Configure and display the regression plot |

##  Program & Output
# Experiment 4: Multiple Regression Analysis (Fish Dataset)  

## Aim
To perform Multiple Linear Regression on a dataset imported from a CSV file to analyze how multiple features together predict a dependent variable.

## Dataset     
The dataset used for this experiment is `fish.csv` which contains real-world physical measurements of various fish species:
* **Independent Variables ($X$):**
  * `L`: Mean length derived from `Length1`, `Length2`, and `Length3`
  * `Height`: Vertical height of the fish
  * `Width`: Diagonal width of the fish
* **Dependent Variable ($Y$):**
  * `Weight`: Weight of the fish (in grams)

    
## Algorithm / Steps Followed
1. Import the required Python libraries (`numpy`, `pandas`, `matplotlib`, `scikit-learn`).
2. Load the fish dataset into a Pandas DataFrame using `pd.read_csv()`.
3. Display the dataset and inspect its columns.
4. Define the dependent ($Y$) and independent ($X$) variables.
5. Train the Multiple Linear Regression model using `LinearRegression()`.
6. Display the model coefficients (`model.coef_`), intercept (`model.intercept_`), and regression equation.
7. Predict target variable (`Weight`) values using `model.predict()`.
8. Evaluate model accuracy using the $R^2$ score (`r2_score()`).
9. Plot actual vs. predicted values for visual comparison.

## Functions and Methods Used

| Category | Function / Method | Purpose / Description |
| :--- | :--- | :--- |   
| **Data Creation / Handling** | `pd.read_csv()` | Load the CSV dataset into a Pandas DataFrame |
| | `np.array()` / `pd.DataFrame()` | Create and manage numerical arrays and tabular data for regression |
| **Model Building (Scikit-learn)** | `LinearRegression()` | Initialize the Multiple Linear Regression model |
| | `model.fit()` | Train the regression model using multiple independent variables ($X$) and target ($Y$) |
| | `model.predict()` | Predict dependent variable values ($Y$) using the trained model |
| | `r2_score()` | Evaluate the accuracy of the regression model using the $R^2$ score |
| **Model Attributes** | `model.intercept_` | Retrieve the intercept (constant term) of the regression equation |
| | `model.coef_` | Retrieve the coefficients (slopes) for each independent variable |
| **Visualization (Matplotlib)** | `plt.plot()` | Plot actual and predicted weight values for comparison |
| | `plt.title()`, `plt.xlabel()`, `plt.ylabel()`, `plt.legend()`, `plt.show()` | Configure titles, axis labels, legend, and display the plotted figure |

## Program & Output
# Experiment 3: Regression Techniques in Business Data(Simple Linear Regression)

##  Aim
To implement Simple Linear Regression in Python to study and predict the relationship between two business-related variables.

## Dataset
A sample business dataset representing the relationship between **Advertising Expenditure** (in Lakhs) and **Sales Revenue** (in Crores). The goal is to analyze how changes in advertising investment affect sales performance.

| Index | Advertising (Lakhs) | Sales (Crores) |
| :---: | :---: | :---: |
| 0 | 18 | 12 |
| 1 | 22 | 18 |
| 2 | 25 | 20 |
| 3 | 30 | 24 |
| 4 | 35 | 28 |
| 5 | 40 | 35 |
| 6 | 45 | 38 |
| 7 | 50 | 40 |
| 8 | 55 | 42 |
| 9 | 60 | 45 |

## Algorithm / Steps Followed
1. Import required Python libraries (`numpy`, `pandas`, `matplotlib`, `scikit-learn`).
2. Create and load the dataset into a Pandas DataFrame.
3. Display the dataset.
4. Select independent ($X$) and dependent ($Y$) variables and reshape $X$ into a 2D array.
5. Build a `LinearRegression` model using `sklearn.linear_model`.
6. Fit the model and calculate the intercept ($a$) and slope ($b$).
7. Predict $Y$ values for given $X$ values and evaluate performance using the $R^2$ score.
8. Plot the actual data points alongside the fitted regression line and predict sales for a new advertising budget.

##  Functions and Methods Used

| Category | Function / Method | Purpose / Description |
| :--- | :--- | :--- |
| **Data Creation / Handling** | `np.array()` | Create numerical arrays for regression input data |
| | `pd.DataFrame()` | Create or manage tabular data for regression |
| **Model Building (Scikit-learn)** | `LinearRegression()` | Initialize the Simple Linear Regression model |
| | `model.fit()` | Train the linear regression model using $X$ and $Y$ values |
| | `model.predict()` | Predict $Y$ values for given $X$ inputs using the fitted model |
| | `model.score()` | Calculate model performance ($R^2$ score) |
| **Visualization (Matplotlib)** | `plt.scatter()` | Plot scatter points (actual data points) |
| | `plt.plot()` | Plot regression line (predicted relationship) |
| | `plt.title()`, `plt.xlabel()`, `plt.ylabel()`, `plt.show()` | Configure and display the regression plot |

##  Program & Output
```# REGRESSION TECHNIQUES IN BUSINESS DATA
# (Simple Linear Regression)

# Step 1: Import Required Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
```
## Input 1
```
# Step 2: Create Dataset
data = {
    'Advertising': [18, 22, 25, 30, 35, 40, 45, 50, 55, 60],
    'Sales': [12, 18, 20, 24, 28, 35, 38, 40, 42, 45]
}

# Create DataFrame
df = pd.DataFrame(data)

print("----- Dataset -----")
print(df)
```
## Output 1
```
----- Dataset -----
   Advertising  Sales
0           18     12
1           22     18
2           25     20
3           30     24
4           35     28
5           40     35
6           45     38
7           50     40
8           55     42
9           60     45
```
## Input 2 
```
# Step 3: Prepare Input (X) and Output (Y) Variables
X = np.array(df['Advertising']).reshape(-1, 1)
Y = np.array(df['Sales'])

# Step 4: Build and Train the Linear Regression Model
model = LinearRegression()
model.fit(X, Y)

# Step 5: Display Model Coefficients
print("\nIntercept (a):", model.intercept_)
print("Slope (b):", model.coef_[0])
```
## Output 2
```
Intercept (a): 0.5811563169164877
Slope (b): 0.7794432548179872
```
## Input 3
```
# Regression Equation
print("\nRegression Equation: Y = {:.2f} + {:.2f}X".format(
    model.intercept_, model.coef_[0]
))
```
## Output 3
```
Regression Equation: Y = 0.58 + 0.78X
```
## Input 4
```
# Step 6: Predict Y for Given X Values
Y_pred = model.predict(X)

print("\nPredicted Sales Values:")
print(Y_pred)
```
## Output 4
```
Predicted Sales Values:
[14.6111349  17.72890792 20.06723769 23.96445396 27.86167024 31.75888651
 35.65610278 39.55331906 43.45053533 47.34775161]

```
## Input 5
```
# Step 7: Evaluate Model Performance
r2 = model.score(X, Y)

print("\nModel Performance:")
print("R2 Score = {:.4f}".format(r2))
```
## Output 5
```
Model Performance:
R2 Score = 0.9736
```
## Input 6
```
# Step 8: Visualize Regression Line
plt.figure(figsize=(8, 6))

plt.scatter(X, Y, color='blue', label='Actual Data Points')
plt.plot(X, Y_pred, color='red', linewidth=2, label='Regression Line')

plt.title("Simple Linear Regression: Advertising vs Sales")
plt.xlabel("Advertising Budget (in ₹ Lakhs)")
plt.ylabel("Sales (in ₹ Crores)")
plt.legend()
plt.show()
```
## Output 6
<img width="686" height="547" alt="image" src="https://github.com/user-attachments/assets/6cbd9dad-8d2e-45b5-8b96-df41b6d56b4e" />

## Input 7
```
# Step 9: Example Prediction
new_value = np.array([[45]])
predicted_sales = model.predict(new_value)

print("\nPredicted Sales for Advertising ₹45 Lakhs = {:.2f} Crores".format(
    predicted_sales[0]
))
```
## Output 7
```
Predicted Sales for Advertising ₹45 Lakhs = 35.66 Crores

```

##  Result

The Simple Linear Regression model was successfully implemented using Python to predict Sales based on Advertising Expenditure.
The regression equation obtained is:
                                      Y=0.58+0.78X
This model shows a strong linear relationship between advertising and sales, with an R


## Result

Thus, Multiple Linear Regression was performed on a dataset imported from a CSV file using Python. The relationship between multiple independent variables and the dependent variable was analysed, and the objective was successfully achieved.

##  Result
