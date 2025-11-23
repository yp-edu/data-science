# TME7

## ML Protocol

Reproducibility
- Set random seeds (`np.random.seed()`) for reproducible results

Train/Test Split
- Split data: 80% train, 20% test
- Test set must never be seen during training

Cross-Validation
- Use k-fold CV for robust performance estimation
- More data -> more stable estimates

Overfitting:
- Too many parameters -> memorizes training data
- Always evaluate on test set, not training set

Regularization:
- Ridge (L2): penalizes large parameters
- Lasso (L1): encourages sparsity
- Prevents overfitting by constraining complexity
