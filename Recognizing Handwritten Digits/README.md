### In this article, I built my first machine learning project in two ways:
1st Simple Code and 2nd Advance Code to recognize handwritten
digits using Scikit-learn (sklearn) python library and use dataset
digits.

Digits contain 1797 images of handwritten digits: 1257 for training and 540 for testing. The
images are grayscale, 8x8 pixels.

Scikit-learn is a free machine learning library for Python. It features various algorithms
like support vector machine, random forests, and k-neighbours, and it also supports Python numerical
and scientific libraries like NumPy and SciPy. 

Let’s get started by Simple Code.

First I come up with a simple code for clarification as this is my first machine learning project.

> upload the code

After loading data I have started training the model and predicting the digits code by using
the SVM library of scikit-learn with gamma= 0.1 but that was not accurate so I tried
gamma= 0.0001 which increased the accuracy.

I have tried my machine with different test examples and different training examples like:

**Training:** x,y= digits.data[:-1], digits.target[:-1]
**Testing:** x_pre= digits.data[-1].reshape(1, -1)
     x_pre= digits.data[-4].reshape(1, -1)
And at the end, output the prediction of machine and image for using the matplotlib library.

> upload the code

Now I got the idea of how to train a model using the scikit-learn library. So I developed the
Advance code, which is divided into 6 Step they are:

1. Importing Libraries
2. Loading In-built Data
3. Visualizing Loaded Data
4. Splitting Data Using train_test_split
5. Training And Predicting
6. Checking Accuracy

**Step 1: Importing Libraries**

Here, three new functions are added classifiction_report, confusion_martix, train_test_split.

**classicfiction_report:** The classification report visualizer displays the precision, recall, F1, and
  support scores for the model.
**confusion_matrix:** It is used to evaluate the accuracy of classification. By definition, a confusion
  matrix is such that is equal to the number of observations known to be in a group but predicted to
  be in a group.
**train_test_split:** It is a function in **Sklearn model selection** for splitting data arrays into **two
  subsets:** for training data and for testing data. With this function, you don't need to divide the
  dataset manually. By default, Sklearn train_test_split will make random partitions for the two
  subsets. However, you can also specify a random state for the operation.

**Step 2: Loading In-built Data**

A dataset is a collection of data. In the case of tabular data, a data set corresponds to one or
more database tables, where every column of a table represents a particular variable, and
each row corresponds to a given record of the data set in question. In this scenario, we are
going to read weather History data.

**Step 3: Visualizing Loaded Data***

The purpose of plotting data is to show the viewer and to understand the dataset and
building relationships between them.

**Step 4: Splitting Data Using train_test_split**
Separating data into training and testing sets is an important part of evaluating data mining
models. Typically, when you separate a data set into a training set and testing set, most of
the data is used for training, and a smaller portion of the data is used for testing. Analysis
Services randomly samples the data to help ensure that the testing and training sets are
similar. By using similar data for training and testing, you can minimize the effects of data
discrepancies and better understand the characteristics of the model. So here I used the
recommended split ratio which is 70% for training and 30% for testing.

**Step 5: Training And Predicting**

The test set is a set of observations used to evaluate the performance of the model using
some performance metric. No observations from the training set must be included in the test
set. If the test set does contain examples from the training set, it will be difficult to assess
whether the algorithm has learned to generalize from the training set or has simply memorized it.

**Step 6: Checking Accuracy**

The three main metrics used to evaluate a classification **model** are **accuracy**, **precision**, and
**recall**. **Accuracy** is defined as the percentage of correct predictions for the test data. It can
be calculated easily by dividing the number of correct predictions by the number of total predictions.

## Conclusion:

Here I learned the major use of the scikit-learn library, I understood that fit() and predict()
functions are the two main functions for machine learning, How to find accuracy, what is
the classification report, SVM, and confusion matrix.

I am thankful to mentors at https://internship.suvenconsultants.com for providing awesome
problem statements and giving many of us a Coding Internship Experience. Thank you
www.suvenconsultants.com

> **Note:** you can refer my blog https://data-analytic-internship.blogspot.com/2021/05/data-analytics-internship.html 




