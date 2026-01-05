# Customer Churn Analysis

## Objective
The objective of this project is to analyze customer churn behavior and identify key drivers of churn using structured exploratory data analysis.

The focus is on understanding **feature dominance, interactions, and limitations** before any modeling decisions are made.

---

## Dataset
The dataset contains customer-level attributes including:
- Contract type
- Lifecycle segment
- Customer value segment
- Pricing flag
- Region
- Churn label (target)

The dataset is relatively small and exhibits structural dependencies between features.
Sensitive raw data is not included.

---

## Approach
The analysis follows a disciplined EDA workflow:
1. Univariate analysis to understand individual feature distributions
2. Bivariate analysis to examine feature–churn relationships
3. Multivariate analysis to identify dominant and conditional features
4. Translation of findings into business-safe insights

---

## Key Findings
- **Contract type** is the dominant driver of churn
- Lifecycle and value segments refine churn risk but do not override contract effects
- Pricing could not be evaluated independently due to structural feature dependencies
- Region shows weak standalone association with churn

---

## Limitations
- Small sample size
- Missing feature combinations resulting in NaN values
- Observed patterns should be treated as hypotheses, not causal conclusions

---

## Next Steps
- Feature encoding and scaling
- Model training and validation
- Performance evaluation and robustness checks

