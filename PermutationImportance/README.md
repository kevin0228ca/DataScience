# Permutation Importance

To find the importance of each feature.

Its advantage is fast to calculate

## Reasoning
If we randomly shuffles one feature column of the validation set, if this column is important, than the accuracy should decrease.
If the feature is not important, not much change in accuracy will be observed.


## Steps
1. Train a model.
2. Shuffle one feature column of validation set, evaluate on validation set, measure accuracy deterioration.
3. Repeat step 2 with another feature column.