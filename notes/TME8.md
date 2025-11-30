# TME8

## Model Comparison
- **SVM:** Sensitive to scale. **Requires normalization** (e.g., StandardScaler) because it relies on distances. RBF kernel is strong for geometric patterns.
- **Trees (Random Forest / Gradient Boosting):** **Invariant to scale**. Robust on complex tabular data without preprocessing.

## Evaluation Metrics
- **Accuracy:** Good for balanced classes, but **misleading** on imbalanced data.
- **Precision:** "Quality" (of the positives predicted, how many are true?).
- **Recall:** "Coverage" (of the actual positives, how many did we find?).
- **F1 Score:** Harmonic mean of Precision and Recall. Use this when you need to balance both.

## Imbalanced Data
- **The Trap:** A model can get high accuracy by ignoring the minority class completely.
- **Symptom:** Often results in high Precision but **low Recall** (hard-to-find minority samples are missed).

## Bonus
- To better understand *why* models differ, try to **interpret** them (e.g., feature importance in trees vs. support vectors in SVM).
