# Data-Science-

import pandas as pd
import numpy as np 
import seaborn as sns
import matplotlib.pyplot as plt

data_set1= pd.read_csv("Titanic.csv")
print(data_set1)
pd.DataFrame(data_set1)
np.isnull(data_set1).sum().sum()
sns.scatter(data_set1["Age"], color="red")
