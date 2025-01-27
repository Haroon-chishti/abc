# abc

## Haroon Chishti
#### Roll No: 151
#### BsAi- 1C

1. **Importing Libraries**
    - Imported the pandas library for data manipulation and analysis.
    - Imported matplotlib and seaborn libraries for data visualization.

2. **Loading the Dataset**
    - Loaded the dataset from the CSV file using `pd.read_csv()` and stored it in the variable `df`.

3. **Initial Data Inspection**
    - Displayed the entire dataframe using `df`.
    - Displayed the first few rows of the dataframe using `df.head()`.
    - Displayed the last few rows of the dataframe using `df.tail()`.

4. **Basic Data Analysis**
    - Checked the minimum index value using `df.index.min()`.
    - Generated descriptive statistics of the dataframe using `df.describe()`.
    - Checked the shape of the dataframe using `df.shape`.
    - Displayed the data types of each column using `df.dtypes`.
    - Displayed the column names using `df.columns`.
    - Displayed the information about the dataframe using `df.info()`.

5. **Missing Values and Duplicates**
    - Checked for missing values in each column using `df.isnull().sum()`.
    - Dropped rows with missing values using `df.dropna()`.
    - Checked for duplicate rows using `df.duplicated().sum()`.

6. **Data Aggregation and Grouping**
    - Counted the occurrences of each value in the 'Traffic Volume' column using `df['Traffic Volume'].value_counts()`.
    - Calculated the mean traffic volume per year using `df.groupby('Year')['Traffic Volume'].mean()`.

7. **Sorting Data**
    - Sorted the dataframe by the 'Road Condition' column using `df.sort_values(by='Road Condition')`.

8. **Data Visualization**
    - Installed and imported the matplotlib library.
    - Plotted a histogram of the 'Accident Cause' column using `df['Accident Cause'].value_counts().plot(kind='hist')`.
    - Plotted a bar chart of the 'Region' column using `df['Region'].value_counts().plot(kind='bar')`.
    - Installed and imported the seaborn library.
    - Plotted a count plot of the 'Region' column using seaborn's `sns.countplot()`.

9. **Summary of Charts**
    - **Accident Cause Histogram**
        - Shows the distribution of different accident causes.
        - Helps in identifying the most common causes of accidents.
    - **Region Frequency Bar Chart**
        - Shows the frequency of accidents in different regions.
        - Helps in understanding which regions have higher accident rates.
    - **Region Count Plot**
        - Shows the count of accidents in different regions.
        - Provides a visual representation of accident distribution across regions.







# github Link
https://github.com/Haroon-chishti/pf-presentation.git