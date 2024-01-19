# Data Cleaning and Modeling for Telecom Churn Analysis :bar_chart:

## Project Overview
This project involved cleaning and modeling telecom company churn data. Notable techniques include the use of OneHotEncoder and Ordinal Encoder, enhancing predictive accuracy. Evaluation focused on the dependency of features on 'Churn Value'.

## Libraries Used :books:
```python
import numpy as np
import pandas as pd
from pandas_profiling import ProfileReport

import seaborn as sns
import matplotlib.pyplot as plt

from sklearn import metrics
from sklearn.pipeline import Pipeline
from sklearn.impute import SimpleImputer
from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import scale, StandardScaler, OneHotEncoder, OrdinalEncoder
