# Heart-disease-prediction-using-random-forest
The data was obtained from a BRFSS survey, the Behavioral Risk Factor Surveillance System (BRFSS) is a collaborative project between all of 
the states in the United States and participating US territories and the Centers for Disease Control and Prevention (CDC). The dataset has 400000 rows 
and 279 columns.

Data cleaning
Since the dataset was obtained from a survey, we have a lot of it in text. The text data is made ordinal and the data containing yes or no 
answers are encoded to numerical values. The text data containing answers like ‘Don’t know’ or ‘Not sure’ are removed. To reduce the numerical 
values and increase the accuracy of the predictive model some columns are bucketized. Data binning or bucketing groups data in bins (or buckets), 
in the sense that it replaces values contained into a small interval with a single representative value for that interval. Data binning is a type of
data preprocessing, a mechanism which includes also dealing with missing values, formatting, normalization and standardization.
The columns bucketized in this dataset are Income, Drinking, Sleep hours. The next step in determining the attributes to be retained in the analysis
from the dataset is to determine the null percentage of the data in each column. The columns with a high percentage of null values are discarded and 
19 columns are retained for further analysis.

For the data set that we have, we selected Random Forest to predict heart disease based on the attributes available. 
The data set is divided into training and testing data sets. The training set 70% of data and test contains 30% of data. 
Then the training data set is used to create the model and the results obtained from the model are compared to the testing data set results. 
On comparing test results, we got an accuracy of 94%.
