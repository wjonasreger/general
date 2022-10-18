# Appendix to STAT 542 Project 1: Predict The Housing Prices in Ames
---
## Figures

### Figure 1.1

Error (RMSE) metrics of best regularized regression procedures chosen by median measure of performance across all test-train splits.

![Optimal Regularized Regression Procedures](https://user-images.githubusercontent.com/19893082/196309318-182eebd7-a993-48ff-a4e8-4f545e1a4041.png)

Notable Procedures:
* X1 & Y13: Elastic Net model (alpha=0.1, lambda.min) fitted on variables selected by another Elastic Net model  (alpha=0.1, lambda.min).
* X9 & Y1: Elastic Net model (alpha=0.1, lambda.min) fitted on variables selected by another Elastic Net model  (alpha=0.2, lambda.min).
* X4 & Y9: Elastic Net model (alpha=0.2, lambda.min) fitted on all variables.
* X7 & Y7: Elastic Net model (alpha=0.3, lambda.min) fitted on all variables.

### Figure 1.2

Error (RMSE) metrics of best boosted tree procedures chosen by median measure of performance across all test-train splits.

![Optimal Boosted Tree Procedures](https://user-images.githubusercontent.com/19893082/196309421-c165fa2c-c0c8-4166-98df-7699e06d92d1.png)

Notable Procedures:
* X1 & Y1: XGBoost Tree model (eta=0.01, max_depth=5, nrounds=5000, subsample=0.5)
* X2 & Y3: XGBoost Tree model (eta=0.01, max_depth=5, nrounds=5000, subsample=0.8)
* X3 & Y2: XGBoost Tree model (eta=0.01, max_depth=6, nrounds=5000, subsample=0.5)
