## Falak Sher ##
## Roll no 097 ##
## Import pandas ##
This is the standard way of importing the pandas library, and the as pd part is just an alias to make it easier to reference. Instead of typing pandas.DataFrame, you can simply write pd.DataFrame.
## Read file ##
## Shape ##
In pandas, the "shape" of a DataFrame or a Series refers to its dimensions, i.e., how many rows and columns
## Sample ##
In pandas, the .sample() function allows you to randomly select a certain number of rows from a DataFrame or Series. It’s useful when you want to quickly look at a random subset of your data.
## Head ##
In pandas, the .head() function is used to view the first few rows of a DataFrame or Series. By default, it shows the first 5 rows, but you can specify a different number if you want to see more or fewer rows.
## Tail ##
In pandas, the .tail() function is used to view the last few rows of a DataFrame or Series. By default, it shows the last 5 rows, but you can specify a different number of rows if needed.
## Rename ##
In pandas, the .rename() function is used to change the names of columns or rows in a DataFrame.
## Slicing ##
Slicing in pandas means selecting specific rows, columns, or parts of a DataFrame or Series. It allows you to extract a portion of the data based on your requirements, just like slicing a list in Python.
## Discribe ##
In Pandas, the Df.describe() method is used to generate a statistical summary of a DataFrame. It provides insights into the data, such as count, mean, standard deviation, and more, depending on the type of data in the DataFrame (numeric, categorical.
## Iloc ##
iloc in pandas is used to select rows and columns by their positions (numeric index). Think of it as a way to pick data using numbers like you would with a list in Python.
## Loc ##
In Pandas, .loc[] is used to access data in a DataFrame by labels (row and column names) rather than integer positions. It is particularly useful when you want to filter or retrieve rows and columns based on their names or boolean conditions.
## columns ##
In Pandas, the Df.columns attribute is used to get or modify the column labels (i.e., column names) of a DataFrame
# Data cleaning #
## select_datatypes ##
In Pandas, the Df.select_dtypes() method is used to select columns based on their data types. It is particularly useful when working with DataFrames that contain a mix of numeric, categorical, and other types of data, allowing you to isolate specific types for analysis or processing.
## Dropna ##
In Pandas, the Df.dropna() method is used to remove missing (NaN) values from a DataFrame. It's commonly used for data cleaning when dealing with missing data, ensuring that the data is complete and ready for analysis or modeling.
## Fillna ##
In Pandas, the Df.fillna() method is used to fill missing (NaN) values in a DataFrame with specified values, such as a constant, the mean, or other values derived from the data. It is an essential tool for data cleaning and preprocessing when handling missing data.
## Isnull ##
isnull() in pandas is a simple method used to check if a value in a DataFrame or Series is missing (i.e., NaN).
## Duplicate ##
In Pandas, the Df.duplicated() method is used to identify duplicate rows in a DataFrame. It is helpful when you need to identify or filter out rows that are repeated in the dataset. This method returns a boolean Series indicating whether each row is a duplicate of a previous row.
## Drop_duplicate ##
In Pandas, the Df.drop_duplicates() method is used to remove duplicate rows from a DataFrame. This is an important method for data cleaning, as duplicate rows can skew your analysis, models, or computations.
## value_count ##
In Pandas, the Df.value_counts() method is used to count the occurrences of unique values in a DataFrame column (or Series). It is useful for understanding the distribution of data and identifying the frequency of each unique value in a dataset.
## Max ##
It seems like you're referring to Df.mix(), but there's no method called mix() in Pandas. It's likely that you meant to ask about Df.min(), Df.max(), or some other similar method.
## Min ##
In Pandas, the Df.min() method is used to find the minimum value in each column of a DataFrame or for a specific column. This method is useful for identifying the smallest values within a dataset, which is important in data analysis, statistical operations, or identifying outliers.
## Info ##
In Pandas, the Df.info() method is used to get a concise summary of a DataFrame. It provides important information about the structure of the DataFrame
## Mode ##
In Pandas, the Df.mode() method is used to find the mode(s) of each column in a DataFrame. The mode is the value that appears most frequently in a dataset.
## Sum ##
In Pandas, the Df.sum() method is used to calculate the sum of values across a DataFrame or Series.
## Median ##
In Pandas, the Df.median() method is used to calculate the median of the values in a DataFrame or Series. The median is the middle value in a dataset when it is sorted in ascending or descending order.