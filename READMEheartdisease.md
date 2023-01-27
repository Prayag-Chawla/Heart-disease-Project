
# Heart Disease Prediction Model

This is a machine learning based heart disease prediction project. Here we were given a set of problems with various attributes and data, we then figured out a dataset from kaggle, visualized it, prprocessed it, gave training and testing inputs and outputs, splitted the data into training and testing data sets, took an algoritm, in this case, decision tree classifier and tested the data while plotting it using dictionories like matplotlib, plotly, cufflinks, seaburn, etc. and finallly compared our predictions with actual results one by one individually.
## Description

- We used Decision Tree Classifier for this project.
A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.



- various graphical approach to visualise data after the step of data cleansing and data reading.


## Usage and Installation

```import numpy as np
import pandas as pd
import plotly as plot
import plotly.express as px
import plotly.graph_objs as go
import matplotlib.pyplot as plt
import sklearn 
import cufflinks as cf
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score
import plotly.offline as pyo
from plotly.offline import init_notebook_mode, plot, iplot
decision_tree = DecisionTreeClassifier()
decision_tree.fit(x_train, y_train)
```


## Running Tests

To run tests, run the following command

```bash
  npm run test
```

We got an accuracy of 72.7 % in this model
