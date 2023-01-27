
# Heart Disease Prediction Model

This is a machine learning based heart disease prediction project. Here we were given a set of problems with various attributes and data, we then figured out a dataset from kaggle, visualized it, prprocessed it, gave training and testing inputs and outputs, splitted the data into training and testing data sets, took an algoritm, in this case, decision tree classifier and tested the data while plotting it using dictionories like matplotlib, plotly, cufflinks, seaburn, etc. and finallly compared our predictions with actual results one by one individually.
The lemghth of the dataset is 303
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





![basic template](https://user-images.githubusercontent.com/92213377/215019428-c58aee1a-b92f-44bd-bc57-ddad8223ca4a.png)


## Running Tests

To run tests, run the following command

```bash
  npm run test
```

We got an accuracy of 72.7 % in this model


## Output
![image](https://user-images.githubusercontent.com/92213377/215019340-a6ef790c-5541-4817-b6a9-0dd4c22ab46f.png)

![image](https://user-images.githubusercontent.com/92213377/215019060-04b496b5-1b28-4803-bdf6-5065fc88c7ae.png)
![image](https://user-images.githubusercontent.com/92213377/215019110-0b55d724-8dd5-45a0-9aab-d1e99f270ac2.png)
