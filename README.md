# Task-4
Feature scaling is essential because many algorithms treat large numbers as more important than small ones.

For distance-based models (KNN, SVM), scaling is critical; without it, a feature like "Capital Gain" ($0–$99k) would mathematically overwhelm "Age" (17–90), leading to biased predictions. In Gradient Descent models (Logistic Regression, Neural Networks), scaling ensures a symmetric error landscape, allowing the optimizer to converge faster and more stably.

Conversely, tree-based models (Random Forest, XGBoost) are unaffected as they split data based on rank rather than magnitude. Ultimately, scaling creates a "level playing field" for all features.
