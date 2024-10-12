# SCT_DS_2
Data Cleaning and Exploratory data analysis(EDA) on dataset

Here, I performing data cleaning and exploratory data analysis (EDA) on a dataset, such as the Titanic dataset from Kaggle. 

The goal is to prepare the data for analysis by handling missing values, removing duplicates, and correcting data types, among other data cleaning techniques. 

Once the data is clean, EDA is conducted to explore relationships between variables and gain insights into the dataset. 

This involves generating summary statistics, visualizing distributions, and examining correlations. 

The aim is to identify patterns, trends, and outliers in the data that can offer valuable information for further analysis. For example, in the Titanic dataset, this could involve analyzing survival rates based on passenger class, gender, and age.

Data Cleaning:-
  After loading the dataset, we need to understand the dataset clearly. So we need perform some methods to understand the data.

  1.df.info() --> It provides a concise summary of a DataFrame, displaying the total number of entries, column names, non-null counts, and data types.
  
  2.df.isnull().sum() --> This method is used to identify missing values in a DataFrame. It returns the total number of missing (null) values in each column, allowing you to easily spot which columns have missing   data and how many entries are affected.
  
  3.df.describe() --> It generates descriptive statistics for numerical columns in a DataFrame. It provides insights such as the count, mean, standard deviation, minimum, maximum, and etc.,
  
  4.df.dropna(inplace=True) --> This method is used to remove all rows in the DataFrame that contain any missing (NaN) values. However, use it with caution, as it can lead to a significant loss of data if many      rows have missing values.
  
  5.df['column_name'].fillna(df['column_name'].mean(), inplace=True)  --> It is used to fill missing (NaN) values in a specific column with the mean of that column. This technique is commonly applied to numerical 
  columns where you want to replace missing values with a meaningful statistical value, in this case, the column's average.
  
  6.df.drop_duplicates(inplace=True) --> This method removes duplicate rows from the DataFrame, keeping only the first occurrence of each duplicate.

Exploratory Data Analysis (EDA):-
  Once the data is clean, EDA is conducted to explore relationships between variables and gain insights into the dataset. This involves generating summary statistics, visualizing distributions, and examining     
  correlations. The aim is to identify patterns, trends, and outliers in the data that can offer valuable information for further analysis. For example, in the Titanic dataset, this could involve analyzing 
  survival rates based on passenger class, gender, and age.
  
  Exploratory Data Analysis (EDA) involves understanding and summarizing the key characteristics of a dataset through both descriptive statistics and visualizations. It starts by inspecting the structure, types, 
  and summary statistics of the data. Univariate analysis examines individual variables, using histograms and box plots for numerical data, and bar charts for categorical data.




