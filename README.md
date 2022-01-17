# DMFT_ML

# Summary 
## The two  python notebook utilized neural network to train the data from DMFT and exact diagonalization to predict the more accurate green's functions which furyher can be  used to calculate the different physical property.
### Installation
```bash
git clone https://github.com/kumarjnc/DMFT_ML.git
```
```python
import numpy as np
import pandas as pd
import tensorflow
import tensorflow.keras
from keras.models import Sequential
from keras.layers import Dense, Dropout, Flatten
from tensorflow.keras.optimizers import Adam, SGD, RMSprop
from tensorflow.keras.utils import to_categorical
from tensorflow.keras import initializers
from tensorflow.keras import regularizers
from tensorflow.keras.regularizers import l2
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from scipy.stats import multivariate_normal
from scipy.special import softmax
from scipy import sparse
from scipy.optimize import leastsq
from keras.wrappers.scikit_learn import KerasRegressor
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import KFold
from sklearn.preprocessing import StandardScaler
from sklearn.pipeline import Pipeline
import math
pi=math.pi
exp=math.exp
```
