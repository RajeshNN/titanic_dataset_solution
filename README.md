# Titanic Dataset Survivor Classification (Using Keras)
![](/images/titanic-sinking-photos.jpg)
:--:
**Titanic setting out to sea**
### This solution to the popular survivor classification contest on Kaggle uses Neural Networks to solve the problem with 77.27% accuracy.

### The solution uses:
##### 1. *train.csv*, that contains training dataset to train our model,
##### 2. *test.csv*, that contains the test dataset to test the model's performance. test.csv is exactly like train.csv except it doesn't have the information on survival of passengers.
##### 3. A third dataset, *test_real_outcomes.csv* is also provided to tally the outcomes predicted by the model on the test set. It contains only information of survival of passengers in the *test.csv*

### To design a Titanic survivor classifier:

- [x] The training set is first to be transformed to be made "learnable" through stepwise data cleaning.
- [x] Then a model is designed using keras library that trains on the cleaned dataset. For cleaning the dataset, I have filled in missing data, categorized data into various classes and have done feature normalization.
- [x] The trained model is then tested on test set and the result tallied with known values in titanic dataset to calculate the accuracy in performance of the model.

![](/images/titanic-lifeboat.jpg)
:--:
**Titanic survivors in a lifeboat**

:ship:
