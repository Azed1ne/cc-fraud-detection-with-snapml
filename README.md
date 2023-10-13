# Credit Card fraud detection
As part of the IBM training I had, the dataset was augmented 10 times to 2848070 values with 31 variables.

The goal was to compare the training time with and without SnapML using different algorithms while still having the same performance (ROC-AUC Score and Hinge Loss).

The results were as follows:
|                | DecisionTreeClassifier | LinearSVC |
|----------------|:----------------------:|:---------:|
| without SnapML |         35.76s         |   49.88s  |
| with SnapML    |          2.20s         |   7.53s   |

## Dataset:
Download from [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data).
