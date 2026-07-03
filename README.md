### Linear Regression from Scratch (NumPy)

- A complete implementation of Linear Regression from Scratch using only NumPy, without using ML libraries.
- Two different method are used in this project:-
- 1.Normal equation
- 2.Gradient Decent

### Features
- Linear Regression using the Normal Equation
- Linear Regression using Gradient Descent
- Automatic Bias (Intercept) Handling
- Feature Standardization (Gradient Descent version)
- Scalling for better gradient
- Cost history reset on every fit().
- Cost vs Epoch Graph

### 1.Normal Equation

- θ=(X^T X)^{-1} X^T y\) 
- No learning rate required
- No epochs required
- Fast for small datasets

### 2.Gradient Decent

- θ=X^T(Xθ-y)/m
- pameter update
- θ=θ-α*GD


### Gradient Descent Workflow
- Initialize Theta
-         ↓
- Prediction
-         ↓
- Error
-         ↓
- Cost (MSE)
-         ↓
- Gradient
-         ↓
- Theta Update
-        ↓
- Repeat for all Epochs

### cost_plot()

Plots the training Cost vs Epoch graph

### Model Methods

### fit(X_train, y_train)

Trains the Linear Regression model.

### predict(X_test)

Returns predictions for unseen data.

Supports:

- NumPy arrays
- Pandas DataFrames
- Single sample input
- Multiple samples
- 
### mean_squared_error(X_test, y_test)

Returns the Mean Squared Error.

### mean_absolute_error(X_test, y_test)

Returns the Mean Absolute Error.

### r2_score(X_test, y_test)

Returns the coefficient of determination (R² Score).

### score(X_test, y_test)

Returns the R² Score (similar to scikit-learn).


### Evaluation Metrics

The implementation includes:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score
