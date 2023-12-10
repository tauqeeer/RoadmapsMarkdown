# Machine Learning

Machine learning comes under the umbrella term of Artificial Intelligence. It uses data sets to train and create models using different algorithms to perform certain tasks.

Some of these tasks can be categorization of data or predicting the outcome of a given situation based on the data it was trained on. 

The machine learning model improves overtime as it trains on more and more data. The accuracy of the model increases as time passes.

## Difference Between AI and ML

Arificial Intelligence is an umbrella term which basically means the implementation of logic and technologies to teach the computer to perform human brain like functions such as ability to read, understand, analyze the data and make recommendations or predict an outcome.

Machine Learning is an application of Artificial Intelligence in which the model is trained in such a way to gain knowledge from the predicted outcomes and make itself learn from it to increase it's accuracy.

To conclude, AI is known as creating machines able to process human brain level instructions while ML uses algorithms to create such machines.

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/6e56c200-f53f-43a8-84e0-f9865e3ddd48)

# Machine Learning In Python

Machine Learning in python can be achieved through understanding basic concepts of programming and data, which we have already learned in the previous chapters.

Carrying it forward, we have some basic libraries that we need to learn first in order to understand machine learning in python.

## NumPy

NumPy library is used for performing mathematical operations, such as matrix multiplication or array calculations. Major linear algebra operations such as Fourier transformation can be applied through this library and it is essential to learn.

NumPy already comes built in for Google Colab but in case it doesn't, try to install it by using:

```python
!pip install numpy
```

Import NumPy as library using:

```python
import numpy as np
```

You can now store and create arrays using NumPy library by using `.np` after your array name:

```python
myArray = np.array([9,7,3])
```

## Pandas

Pandas library is used in machine learning to manipulate and edit data. It is used to store data files and make changes to it accordingly.

Pandas already comes built in for Google Colab but in case it doesn't, try to install it by using:

```python
!pip install pandas
```

Import pandas as library using:

```python
import numpy as np
```

You can now add files using pandas library:

```python
df = pd.read_csv('file.csv')
```

## Scikit-Learn

Scikit-learn (also known as Sklearn) library is used in machine learning by providing different statistical models such as regression, classification and clustering all by using simple commands.

Scikit-learn library can be installed using:

```python
!pip install -U scikit-learn
```

Import Scikit-learn:

```python
import sklearn
```

Loading a dataset:

```python
from sklearn.datasets import load_iris
iris = load_iris()
```
---

These were some of the basic machine learning libraries you can use to import and upload data sets onto your model. They are know for their well known readability and usability, also they can be run on any python platform or enviorment. </br>
</br>
</br>


# Machine Learning Algorithms

Here `X_train` and `y_train` are the training datasets. `X_test` is the dataset we want to make predictions on and `y_pred` is the variable in which we will store the predicted values.

## Linear Regression

Linear regression is a statistical method which compares two variables with one another. This algorithm works mainly upon two variables `x` and `y` where `x` is the independent variable which is usually known as the predictor or the input. We use the values of `x` to determine the value of `y` which is known as dependant variable or the output.


```python
from sklearn.linear_model import LinearRegression
lr = LinearRegression()
lr.fit(X_train, y_train)
y_pred = lr.predict(X_test)
```

## Logistic Regression

Logistic regression is a classifier which works on giving boolean values like 1 or 0 which determines whether the given independent variables match a certain criteria or not.

```python
from sklearn.linear_model import LogisticRegression
logr = LogisticRegression()
logr.fit(X_train, y_train)
y_pred = logr.predict(X_test)
```

## Decision Tree

Decision tree uses a logistic approach to classify a certain element by predicting the value of a target variable through learning the data features.

```python
from sklearn import tree
model = tree.DecisionTreeClassifier()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

## K-Nearest Neighbours

Also known as KNN, this algorithm uses it's nearest neighbours to determine the classisfication of an element. If the target variable has similar features as it's neigbour, they will be classified together. This algorithm can be used to create recommendation systems.

```python
from sklearn.neighbors import KNeighborsClassifier
model = KNeighborsClassifier(n_neighbors=3)
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

## Support Vector Machines

Also known as SVM, this alorithm draws a vector in a n-dimensional space where n is the number of features of the dataset. This algorithm is used mainly for outlier detection and classification. If the target varaible lies outside the vector, it is considered as an outlier.

```python
from sklearn import svm
svc = svm.SVC()
svc.fit(X_train, y_train)
y_pred = svc.predict(X_test)
```


