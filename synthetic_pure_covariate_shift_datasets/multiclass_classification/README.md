# Multiclass Classification Pure Covariate Shift Dataset

This pure covariate shift dataset has been created to test performance estimation and calculation for custom metrics for binary classification.
The dataset consists of:

- 5 numerical features: `['feature1', 'feature2', 'feature3', 'feature4', 'feature5', 'feature6', 'feature7']`
- Target column: `y_true`
- Model prediction column: `y_pred`
- Model predicted probabilities: `['y_pred_proba_0', 'y_pred_proba_1', 'y_pred_proba_2', 'y_pred_proba_3', 'y_pred_proba_4',]`
- A timestamp column: `timestamp`
- An identifier column: `identifier`
- The oracle probabilities from which the target values have been sampled: `['estimated_target_probabilities_0', 'estimated_target_probabilities_1', 'estimated_target_probabilities_2', 'estimated_target_probabilities_3', 'estimated_target_probabilities_4',]`

Columns such as timestamp and identifier are there to make it easier to test this dataset in [NannyML Cloud](https://docs.nannyml.com/cloud).
