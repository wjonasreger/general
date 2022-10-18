# Appendix to STAT 542 Project 1: Predict The Housing Prices in Ames
---
## Figures

### Figure 1.1

Error (RMSE) metrics of best regularized regression procedures chosen by median measure of performance across all test-train splits.

[](reg_plot.png)

Notable Procedures:
* X1 & Y13: Elastic Net model (alpha=0.1, lambda.min) fitted on variables selected by another Elastic Net model  (alpha=0.1, lambda.min).
* X9 & Y1: Elastic Net model (alpha=0.1, lambda.min) fitted on variables selected by another Elastic Net model  (alpha=0.2, lambda.min).
* X4 & Y9: Elastic Net model (alpha=0.2, lambda.min) fitted on all variables.
* X7 & Y7: Elastic Net model (alpha=0.3, lambda.min) fitted on all variables.

### Figure 1.2

Error (RMSE) metrics of best boosted tree procedures chosen by median measure of performance across all test-train splits.

[](tree_plot.png)

Notable Procedures:
* X1 & Y1: XGBoost Tree model (eta=0.01, max_depth=5, nrounds=5000, subsample=0.5)
* X2 & Y3: XGBoost Tree model (eta=0.01, max_depth=5, nrounds=5000, subsample=0.8)
* X3 & Y2: XGBoost Tree model (eta=0.01, max_depth=6, nrounds=5000, subsample=0.5)