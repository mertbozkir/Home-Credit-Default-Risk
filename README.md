# Home-Credit-Default-Risk

## Results:
| Model         | Score         | How  |
| ------------- |:-------------:| -----:|
| RandomForest     | 0.67877      |   just model |
| LightGBM      | 0.73031       | just model |
| LightGBM | 0.71745      |    estimator=1000 |
| LightGBM        | 0.73132           | estimator = 75  |
| LightGBM |   0.73132 |Grid Search CV|
| LightGBM        | 0.73132           | with best_params  |
| LightGBM        | 0.72541           | someone's best_params  |
| LightGBM        | 0.73070           | is_unbalanced = True  |
| LightGBM        | 0.73075           | estimator=120  |
| StratifiedKFold LGBM        | 0.74904           | GridSearch CV  |
