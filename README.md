Weather report prediction
here i am predicted future maximum temparature using past temparature values.
library i used
import pandas
import numpy
import warnings
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn import metrics
import matplotlib.pyplot
import seaborn 
started by importing the libraries
after that to read the csv  i wrote pd.read_csv()
according to problem statement i checked for null values using isna().apply(pd.values_count)
after filling the null values using fillna()
and then splitted my train data and test data
after that by importing the linear Regressin model created object and then using this model object trained the model to caliculate linear regression,after predicted the maximmum temperature values using previous Temperature values.
finding the coefficient using model.coeef_
finding the interccept model.interccept_
compared actual value with the predited values.
after that to find the accuracy using the MSE,R2,Adjusted R2 
after that i plot the graph

