# Machine Learning

<img src="https://www.iberdrola.com/documents/20125/40921/machine_learning_746x419.jpg/15ff7571-4cfc-d9f0-5ef4-9c2e9306ad88?t=1627968463400" width=550 height=300>

### What is Machine Learning ?
Machine Learning is the science of programming computers so they can learn from data.

### How do they learn from data ?
Through machine learning algorithms.

### Will I have to learn to create these algorithms ?
No, they are already invented ( by very smart people) and we will only need to know how and when to use them.

### What is a model ?
A model is a trained machine learning algorithm that has been adjusted to generalize the best way to make accurate predictions.

### What are the algorithms that I will need to know?
The most popular machine learning algorithms are:

- Linear Regression
- Logistic Regression
- kNN
- Decision Tree
- Random Forest
- SVM
- K-means
- Gradient Boosting/AdaBoosting

### Should I go and just dive now into learning each algorithm?
Before diving in you must understand that the above algorithms can not be used to predict all types of problems.

Machine learning algorithms can be classified into 2 main categories:

- Supervised: algorithms are trained using labeled examples, such as an input where the desired output is known.
- Unsupervised: data is unlabeled.

### How do I know if my model has perfomed well?

Classification metrics:
- Accuracy:
    - Accuracy in classification problems is the **number of correct predictions** made by the model divided by the **total number of predictions.** Useful when target classes are well balanced. Imagine we have 99 ham (legitimate) messages and 1 spam. If our model was simply a line that always predicted ham we would get 99% accuracy. In that case we should turn into recall and precision.

- Recall:
    - Abilitiy of a model to find **all** the relevant cases within a dataset.
    - The precise definition: **number of true positives divided by the number of true positives plus the number of false negatives.**
- Precision:
    - Abilitiy of a classification model to identify **only** the relevant data points.
    - Precision is defined as the number of **true positives divided by the number of true positivest plus the number of false positives**.

Often you have a trade-off between Recall and Precision.

While recall expresses the ability to find all relevant instances. ina dataset, precision expresses the proportion of the data points our model says was relevant actually were relevant.

In cases we want to find an optimal blend of precision and recall we can combine the two metrics using what is called the F1socre.

- Fi-Score: harmonic mean (because it punishes extreme values) of precision. andrecall taking both metrics into account in the following equation:  F1 = 2 * (precision*recall)/precicion+ recall

The main point to remember with the confusion matrix and the various calculated metrics is that they are all fundamentally ways of comparing the predicted values versus the true values.
What constitues "good" metrics, will really depend on the specific situation!
