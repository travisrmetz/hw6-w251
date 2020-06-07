
### W251 - HW06
#### Travis Metz
#### June 2020

Results of various models:

This repo includes three different notebooks.
1.  Model trained on p100a with one epoch of training.
2.  Model trained on v100a with one epoch of training.
3.  Model trained on v100a with TWO epochs of training.

| Processor | Epochs | Training Time | Train Accuracy | Validation Accuracy
|---|---|---|---|---|
p100a | 1 | 6:07 | .952 | .9700
v100a | 1 | 1:50 | .952 | .9699
v100a | 2 | 3:40 | .961 | .9697
