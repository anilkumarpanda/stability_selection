# Stability Selection

Comarison of Stability Selection methods with other Feature selection(FS) methods.AUC is used as the score.

## Results

1. [UCI Credit card dataset](http://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

| FS Method     | Mean Train Score| Mean Test Score  | Mean Overfit |
| ------------- |:-------------:| :-----:|:---------:|
| Stability Selection         | 0.776     | 0.766  |0.010  |
| Mlxtend SFS(Floating)       | 0.820     | 0.779  | 0.040 |
| SHAP                        | 0.779     | 0.769  | 0.090 |
| FS combined                 | 0.778     | 0.776  | 0.007 |

2. [LnT Vehical Default dataset](https://www.kaggle.com/avikpaul4u/vehicle-loan-default-prediction) 

| FS Method     | Mean Train Score| Mean Test Score  | Mean Overfit |
| ------------- |:-------------:| :-----:|:---------:|
| Stability Selection         | 0.657     | 0.628  |0.028  |
| Mlxtend SFS(Floating)       | 0.669     | 0.635  | 0.033 |
| SHAP                        | 0.709     | 0.629  | 0.080 |
| FS combined                 | 0.671     | 0.636  | 0.035 |

Some additional thoughts and best practises about feature selection can be found [here](https://github.com/anilkumarpanda/stability_selection/blob/master/Thoughts%20on%20Feature%20Selection.md)
