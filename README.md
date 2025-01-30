# wbcd
Wisconsin breast cancer dataset research. Using Python to develop training and testing data sets.

Python supplies us with various libraries of tools for data testing tasks, a commonly chosen method for data testing with neural networks and deep learning applications.  

I have pre-processed the Wisconsin breast cancer data set to use in the testing. Using the sklearn imports I was able to normalise the numerical features using standard scaler and created a train-test split using the train_test_split function. A validation split of 20% is used in this training. In terms of optimization, I have used the Adam optimizer. I have programmed the model to develop two confusion matrixs and learning curve. My overall test accuracy using python was 95.61%, a marginal decrease in accuracy in comparison to the testing in Weka. The differential in training split could be the cause of this decrease in accuracy as the model has more training data to work off.  

Using this code I have developed will develop a significantly more accurate result in comparison to exisitng tools such as Weka, however due to the nature of a small dataset, the percentage is marginal.
