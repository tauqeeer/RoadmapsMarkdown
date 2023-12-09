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

`!pip install numpy`

Import NumPy as library using:

`import numpy as np`

You can now store and create arrays using NumPy library by using `.np` after your array name:

`myArray = np.array([9,7,3])`

## Pandas

Pandas library is used in machine learning to manipulate and edit data. It is used to store data files and make changes to it accordingly.

Pandas already comes built in for Google Colab but in case it doesn't, try to install it by using:

`!pip install pandas`

Import pandas as library using:

`import numpy as np`

You can now add files using pandas library:

`df = pd.read_csv('file.csv')`

## Scikit-Learn

Scikit-learn (also known as Sklearn) library is used in machine learning by providing different statistical models such as regression, classification and clustering all by using simple commands.

Scikit-learn library can be installed using:

`!pip install -U scikit-learn`

Import Scikit-learn:

`import sklearn`

Loading a dataset:

`from sklearn.datasets import load_iris`</br>
`iris = load_iris()`

---

These were some of the basic machine learning libraries you can use to import and upload data sets onto your model. They are know for their well known readability and usability, also they can be run on any python platform or enviorment. 

