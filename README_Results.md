## Results

The Student Performance Prediction System was evaluated using nine regression models. The models were compared using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

### Model Performance Comparison

The Polynomial Regression model (Degree 2) achieved the lowest RMSE on the test dataset.

| Model | MAE | MSE | RMSE | R² |
|---|---:|---:|---:|---:|
| Polynomial Regression (Degree 2) | 1.2427 | 4.2127 | 2.0525 | 0.7946 |
| Mini-batch Gradient Descent | 1.2082 | 4.2157 | 2.0532 | 0.7944 |
| Simple Linear Regression | 1.2087 | 4.2162 | 2.0533 | 0.7944 |
| Batch Gradient Descent | 1.2087 | 4.2162 | 2.0533 | 0.7944 |
| SGDRegressor (sklearn) | 1.2087 | 4.2162 | 2.0533 | 0.7944 |
| Stochastic Gradient Descent | 1.2117 | 4.2191 | 2.0540 | 0.7942 |
| Lasso Regression | 1.3020 | 4.4537 | 2.1104 | 0.7828 |
| Ridge Regression | 1.3391 | 4.4645 | 2.1129 | 0.7823 |
| Multiple Linear Regression | 1.3394 | 4.4665 | 2.1134 | 0.7822 |

### Actual vs. Predicted Grades

The graph compares actual final grades with the grades predicted by the Polynomial Regression model. Points closer to the diagonal line indicate more accurate predictions.

![Actual vs Predicted Grades](results/actual_vs_predicted.png)

### Model Comparison Graph

![Model Comparison](results/model_comparison.png)

### Conclusion

Polynomial Regression (Degree 2) achieved the lowest test RMSE of approximately 2.0525 and an R² score of 0.7946 in this experiment. This indicates that the model explained approximately 79.46% of the variance in the test-set grades.

These results are based on one train/test split and may vary with a different dataset split.

