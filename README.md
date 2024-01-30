## CA02 - Spam eMail Detection using Naive Bayes Classification Algorithm

### Overview

This is a Python script for classifying emails as spam or not spam using the Naive Bayes algorithm.

We trained the model with a set of emails labeled as either from Spam or Not Spam. 
There are 702 emails, equally divided into spam and non-spam categories. 
Next, we tested the model on 260 emails. 
Lastly, We asked the model to predict the category of these emails and compare the accuracy with the correct classification that we already know.

### Data

The training and testing data are located in the *train-mails* and *test-mails* directories.

### Libraries
In this code, we used different libraries.
Please import them as part before you run any other code
- os
- numpy (np)
- collections (Counter)
- sklearn.naive_bayes (GaussianNB)
- sklearn.metrics (accuracy_score)


### Results

The accuracy of the classifier on the test data is: **[Accuracy Score]**

![Spam Email](https://i.imgflip.com/12ab5o.jpg)
