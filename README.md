# Tree-Based Models: Random Forests

## Objective

I compared linear models, a decision tree, and random forests to predict California housing values and evaluate model performance and feature importance.

## Methodology

- Compared a single tree, OLS, Ridge, and a random forest using the same train-test split.
- Evaluated training and test RMSE and R².
- Compared impurity-based and permutation feature importance.
- Tuned forest depth and feature selection using cross-validation.
- Used two AI-prompt rounds to create and verify a reusable feature-importance function.

## Key Findings

The single tree had a test R² of 0.6161, Ridge had 0.5758, and the random forest had 0.8044. The tuned forest improved test R² to 0.8116.

Latitude received an MDI importance of 0.0889 and a permutation importance of 0.4427, showing that the two methods measure importance differently. My AI-generated function passed every numerical, ordering, and generalization check after two rounds, with all checked values 0% apart.
