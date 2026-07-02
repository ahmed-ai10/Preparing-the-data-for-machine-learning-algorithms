The California Housing Dataset was prepared and cleaned to be ready for 
use in machine learning models and data analysis,
with the application of a range of data preprocessing and feature engineering techniques.

What was done:

Imported data using Pandas.

Checked the data and ensured the quality of columns and values.

Detected missing values.
Replaced missing values ​​using median imputation via SimpleImputer.
Converted categorical variables to numeric variables using one-hot encoding.
Deleted the original column after encoding to maintain data cleanliness.
Renamed the resulting columns for clarity.
Created new features (feature engineering), such as:
rooms_per_house
bedrooms_ratio
people_per_house
Rounded some derived values ​​where needed using Python functions.
Calculated the correlation matrix between all numeric variables.
Analyzed the relationship between each variable and the median house value to identify the most influential features. Preparing the final dataset to be suitable for building Machine Learning models.

Tools used:
Python
Pandas
NumPy
Scikit-learn
SimpleImputer
OneHotEncoder

Skills used:
Data Cleaning
Data Preprocessing
Missing Values ​​Handling
Feature Engineering
Feature Encoding
Correlation Analysis
Pandas
Scikit-learn
