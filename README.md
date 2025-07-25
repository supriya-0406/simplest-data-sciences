import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from google.colab import files
uploaded = files.upload()
df = pd.read_csv('customers.csv')
df.head()
df.shape        # Rows and columns
df.info()       # Data types and non-null values
df.describe()   # Summary statistics
df.columns
