Bayesian Linear Regression Model for Predicting Basketball Player Performance

Project Overview-
This project focuses on building a Bayesian Linear Regression model from scratch using TensorFlow for predicting basketball players' points (`pts`). The dataset used contains various player statistics and attributes. The key steps involved in this project include exploratory data analysis, data preprocessing, model implementation, prediction, and evaluation.

Dataset
The dataset used in this project is `Dataset_1000.csv`, which includes the following columns:
- `player_height`: Height of the player
- `player_weight`: Weight of the player
- `pts`: Points scored by the player
- `ts_pct`: True shooting percentage
- `oreb_pct`: Offensive rebound percentage
- `dreb_pct`: Defensive rebound percentage
- `gp`: Games played
- `reb`: Total rebounds
- `usg_pct`: Usage percentage
- `ast_pct`: Assist percentage

 Exploratory Data Analysis
Initial data analysis was performed to understand the relationships between different features. A pair plot was generated for a subset of columns to visualize these relationships.

 Data Preprocessing
- Feature Selection: The features selected for training the model are `player_height`, `player_weight`, `oreb_pct`, `gp`, `ts_pct`, `reb`, `usg_pct`, and `ast_pct`.
- Standardization: StandardScaler was used to scale the features.
- Train-Test Split: The dataset was split into training and testing sets with a test size of 50%.

 Bayesian Linear Regression Model
A Bayesian Linear Regression model was implemented from scratch using TensorFlow. The model includes the following key methods:
- `fit(X, y)`: Fits the model to the training data by calculating the posterior distribution of the weights.
- `predict(X)`: Predicts the target variable for the given input data.

 Model Training and Prediction
The model was trained on the training data and predictions were made on the test data.

 Model Evaluation
The performance of the model was evaluated using the following metrics:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared score (R²)

 Results Visualization
Two visualizations were generated:
1. Scatter plot showing actual vs predicted values with an ideal line.
2. Histogram showing the distribution of predicted values.

 Results
- Mean Squared Error: 6.520397734513684
- Mean Absolute Error: 1.9011167902587787
- Root Mean Squared Error: 2.5535069482015675
- R-squared score: 0.8040152592841063

Conclusion
The Bayesian Linear Regression model was successfully implemented and provided reasonable predictions for basketball players' points. Further improvements can be made by experimenting with different features, hyperparameters, and more advanced models.

 Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- tensorflow
- scikit-learn

 How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook or Python script to execute the entire workflow.

