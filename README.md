## To Execute:
```python pretrain.py```

This is a simple file for both pre pruning training and testing.
The global variable ```TEST``` is set to 1 for testing the model.
The compressed weights are stored in the pickle file.

These values would be printed out:
- Pruning information: tells how many weights have been pruned out at each layer
- Contents in the conv1 layer: you would have a chance to see how weights are pruned and how they are grouped into clustered values.
- Prediction results for the first 64 images in the test set.
- test accuracy: 0.99250
