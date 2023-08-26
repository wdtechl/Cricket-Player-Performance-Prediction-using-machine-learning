# Cricket-Player-Performance-Prediction-using-machine-learning
import pandas as pd

# for data manipulation

import numpy as np

# for mathematical calculations

import seaborn as sns

# for data visualization

import matplotlib.pyplot as plt #for graphical analysis

matplotlib inline

from scipy.stats import zscore # to remove outliers

from sklearn.preprocessing import StandardScaler # for normalize the model

from sklearn.preprocessing import LabelEncoder to convert object into int

from sklearn.model_selection import train_test_split for train and test model

import warnings

warnings.filterwarnings("ignore")

# to ignore any warnings

from sklearn import metrics for model evaluation

from sklearn.metrics import accuracy score, classification_report, confusion_matrix
