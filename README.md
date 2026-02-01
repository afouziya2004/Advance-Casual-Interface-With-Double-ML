## Advance-Casual-Interface-With-Double-ML
# The objective of this project is to estimate the causal effect of a treatment variable on an outcome variable using Double Machine Learning (DML). Traditional regression techniques often produce biased estimates when there are many confounding variables or when relationships are non-linear. To overcome these limitations, this project applies DML, which combines machine learning methods with econometric principles to provide unbiased causal estimates.

# In this project, a synthetic dataset is created where the treatment assignment depends on multiple confounding variables. The outcome variable is influenced by both the treatment and the confounders. Machine learning models, specifically Random Forest Regressors, are used to estimate the nuisance functions: the expected outcome given the confounders and the expected treatment given the confounders.

# The DML framework applies cross-fitting, which splits the data into folds to prevent overfitting and reduce bias introduced by machine learning models. After removing the effect of confounders through residualization, the causal effect of the treatment is estimated using a linear model.

# The Average Treatment Effect (ATE) is computed along with its confidence interval, providing a robust and statistically reliable causal estimate. A comparison is also made with a naive Ordinary Least Squares (OLS) regression, demonstrating that DML produces more accurate and unbiased results in the presence of confounding.

# This project highlights how Double Machine Learning can be effectively used for advanced causal inference, especially in high-dimensional and complex data settings, making it suitable for real-world decision-making applications.
