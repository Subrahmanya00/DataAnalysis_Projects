**The Weather Dataset**

Here, The Weather Dataset is a time-senes data set with per-hour information about the weather conditions at a particular location. it records Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Conditions.

# How to Analyze Dataframes?

**.head()**
it shows the first N rows in the data(by default, N=5).

**.shape**
it shows the total no.of rows and no.of columns of the dataframe.

**.index**
This attribute provides the index of the dataframe.

**.columns**
it shows the name of each coulmn.

**.dtypes**
it shows the data-type of each column.

**.unique()**
In a column, it shows all the unique values. it can be applied on a single column as well as on whole dataframe.

**.nunique()**
It shows the total no.of unique values in each column.It can be applied on a single column as well as on a whole dataframe.

**.count**
It shows the total no.of non-null in each column. It can be applied on a single column as well as on whole dataframe.

**.value_counts**
In a column, it shows all the unique values with their count. It can be applied on single column only.

**.info()**
Provides basic information about the dataframe.

