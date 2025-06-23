# ujwal-task1
Task Summary: Data Cleaning & Preprocessing (Arabica Dataset)
Loaded the dataset
We loaded the Arabica CSV file in order to find out what type of data it contained.

Checked the data
We checked the number of rows, columns, data types, and missing values.

Filled missing values
For numbers, we filled in missing values with the median (middle value).

For text columns, we filled in missing values with the most common value (mode).

Converted text to numbers
We converted all text data (such as country names or types) into numerical codes so that a machine learning model can interpret them.

Normalized the numbers
We normalized all numeric values to be between 0 and 1 so all features are on equal terms.

Checked for outliers
We employed boxplots to discover values that were too distant from the rest.

Removed outliers
We removed the extreme values by using a technique known as IQR (Interquartile Range).

Saved the cleaned data
We saved the cleaned one as a new CSV file so that it can be utilized for machine learning.
