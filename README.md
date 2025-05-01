# MLT01

## User Instructions

** Environment Setup **
To run this program, it is recommended that you use either Jupyter Notebook in an Anaconda environment. Anaconda provides a comprehensive package management system and comes pre-installed with many essential data science libraries. Due to the size of the data, you will need to download the 311 csv file from this website and change 'test2' in Data Cleaning file to the file name of 311 csv in your folder. Link to the 311 data: https://data.wprdc.org/dataset/311-data/resource/29462525-62a6-45bf-9b5e-ad2e1c06348d 

** Required Libraries **

import pandas as pd

import numpy as np

import seaborn as sns

import matplotlib.pyplot as plt

from sklearn.model_selection import StratifiedKFold, GridSearchCV

from sklearn.preprocessing import OneHotEncoder, StandardScaler

from sklearn.compose import ColumnTransformer

from sklearn.pipeline import Pipeline

from sklearn.linear_model import LogisticRegression

from sklearn.naive_bayes import GaussianNB

from sklearn.ensemble import RandomForestClassifier

from sklearn.svm import SVC

from sklearn.metrics import precision_score, recall_score, f1_score, accuracy_score

from sklearn.ensemble import VotingClassifier

from sklearn.model_selection import GridSearchCV

from sklearn.metrics import classification_report

from sklearn.metrics import confusion_matrix

from sklearn.metrics import roc_curve, auc, precision_recall_curve

** Files **
1. clean2.csv - cleaned file before NA imputation
2. clean3.csv - cleaned file without missing data
3. codebook.csv - codebook provided by WRPDC
4. Data Cleaning.ipynb - code for data cleaning
5. Missing_Vals.ipynb - code for dealing with missing data
6. modeling.ipynb - code for modeling 
7. modeling.ipynb - code for modeling and evaluation 
8. Data Dictionary.md - data dictionary

To ensure a smooth story to explain the processes and findings, our team highly recommend downloading and running the files in the order specified below.

To run the Data Cleaning.ipynb:
1. Download 311 data from website 
2. Change 'test2.csv' to saved 311 data file name
3. Download codebook.csv

To run modeling.ipynb or modeling_extended.ipynb:
1. Download the cleaned csv file - clean3.csv
