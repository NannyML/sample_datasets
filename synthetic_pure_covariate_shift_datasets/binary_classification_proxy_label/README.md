# Binary Classification Pure Covariate Shift Dataset

This pure covariate shift dataset has been created to test performance estimation and calculation for custom metrics for binary classification.
The dataset consists of:

- 5 numerical features: `['feature1', 'feature2', 'feature3', 'feature4', 'feature5',]`
- Target column: `y_true`
- The proxy label column: `y_true_1/2`
- Model prediction column: `y_pred`
- Model predicted probability: `y_pred_proba`
- A timestamp column: `timestamp`
- An identifier column: `identifier`
- The oracle probabilities from which the target values have been sampled: `estimated_target_probabilities`

Columns such as timestamp and identifier are there to make it easier to test this dataset in [NannyML Cloud](https://docs.nannyml.com/cloud).
