# Data-Science

| Model                   | Split Ratio | Scaled | Hyperparameter                  | R2   | MSE         |
|-------------------------|-------------|--------|----------------------------------|------|-------------|
| RandomForestRegressor   | 80, 20      | Yes    | Default                          | 1    | 1138028318  |
| RandomForestRegressor   | 80, 20      | Yes    | n_estimators=200                 | 1    | 1100125635  |
| DecisionTreeRegressor   | 80, 20      | Yes    | Default                          | 0.99 | 2326798675  |
| DecisionTreeRegressor   | 80, 20      | Yes    | max_depth=20                     | 0.99 | 2326798675  |
| AdaBoostRegressor       | 80, 20      | Yes    | Default                          | 0.99 | 2356192015  |
| AdaBoostRegressor       | 80, 20      | Yes    | max_depth=20, min_samples_split=5 | 0.99 | 2372801641  |

