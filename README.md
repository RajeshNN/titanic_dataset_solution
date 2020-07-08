
This solution to the popular survivor classification contest on Kaggle uses Neural Networks to solve the problem with 77.5% accuracy.
The solution uses two datasets:
one train dataset to train the model on and the test dataset to test the model's performance.

A third dataset is also provided to tally the outcomes predicted by the model in the test set. It has been named the titanic dataset.

All datasets are in .csv format.

The training set is first to be transformed to be made "learnable" and then a model is designed that trains on the transformed dataset.
Making the dataset learnable involves filling in missing data, categorizing data into various classes and feature normalization.

The trained model is then tested on test set and the result tallied with known values in titanic dataset to calculate the accuracy in performance of the model.
