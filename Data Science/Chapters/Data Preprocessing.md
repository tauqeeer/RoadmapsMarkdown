# Data Pre-Processing

Before we dive deep into machine learning algorithms, we need to understand data preprocessing and why it is so important for our model's efficieny.

The world we live in contains mostly garbage or unwanted data. Imaging what impact it would have on your machine learning model if we apply algorithms on unwanted data. The results would be very inaccurate and it would throw you off. 

To overcome this problem, we implement some data preprocessing steps to <b><i>clean</i></b> the data.

Getting your data ready for machine learning algorithms is super important, and that’s where data preprocessing comes in. If you don’t do it right, your model might not give you the best results. 

## Data Cleaning

### Noisy Data

Most of the data contains duplicate, null, missing, corrupted and irrelevant data which can really mess up with your model. 

Think of a company database where employees' data is stored. The <b>age</b> column contains negative values such as -50. This makes the data of that column irrelevant because age cannot be negative.

We perform <i><b>smoothing</b></i> where we group data in bins with equal weight and then apply mean to that bin. Taking mean will normalize the irrelevant data and the model will now be accurate than before.

---

### Missing Data

Often times you will come accross data which contains nothing, that means the data there has been missing. If you put the dataset as it is on the machine learning model, there is strong chance you will come accross multiple errors and inaccurate results.

Removing the data is one of the solutions to this problem if you have large dataset. But if you cannot afford to remove the entire data because of small volume of data, then we need to try a different approach. 

KNN algorithm is also one of the ways to deal with missing data, this algorithm basically predicts the values of a variable by observing the values of it's neigbours. You can learn more about KNN algorithm on [chapter 7](/Data%20Science/Chapters/Machine%20Learning.md).

---

### Dimensionality Reduction

Some datasets contain a large number of columns and rows mostly which we won't need to train and test our model. The removal of these rows and columns from the dataset is known as dimensionality reduction.

If we train our model with a huge volume of irrelevant data, it can become overfit. This basically means the model has been trained more than it's capacity and will now produce inaccurate results due to overloading the data.

---

### Data Transformation

Some machine learning algorithms like logistic regression work on 0 and 1. Have you ever wondered what would happen if the wrong type of input is given to your model? It will generate errors as it was expecting a different input and will eventually tell you to change your input.

To overcome this problem, the data is transformed into an acceptable input. For example, the given data set contains either male or female, but your model needs input as 0 and 1. You will first need to change the values and assign 0 to male and 1 to female or vice versa.

---

Before you start applying these techniques, make sure you’ve split your dataset into training and test sets. Here’s the trick - you only use the training set for learning and then apply what you’ve learned to the test set.
