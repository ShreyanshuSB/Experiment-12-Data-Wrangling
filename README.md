** Experiment-12 **

** Name: Shreyanshu Behera **

** PRN: 25070123149 **

** Batch: ENTC A1 **

** Title **

Implementation of Data Wrangling Techniques in Python

** Aim **

To learn and implement data wrangling methods for cleaning, transforming, and organizing datasets for analysis using the Pandas and NumPy libraries.

** Objectives **

To understand the role of data wrangling in the data science workflow.
To manage missing and inconsistent data within datasets.
To carry out data transformation and feature scaling.
To combine multiple datasets for integrated analysis.
To utilize grouping and aggregation techniques for data summarization.

** Theory on Data Wrangling **

Data Wrangling, also known as data munging, refers to the process of converting raw data into a structured and usable format. This transformation makes the data more suitable for analysis and helps in extracting meaningful insights.

** Key Components of Data Wrangling **

Data Cleaning: Detecting and correcting errors such as missing values (NaN) and duplicate entries.
Data Transformation: Changing the structure or format of data (for example, converting data types or normalizing values).
Data Integration: Merging data from various sources like CSV files, databases, or dictionaries into a single dataset.
Data Aggregation: Summarizing data to identify patterns, such as calculating averages, medians, or category frequencies.

** Data Wrangling Operations **

Based on the procedures performed during lab sessions, the following techniques were applied:

Handling Missing Data

In practical datasets like Cars93 or Student Database, missing values are frequently encountered. The following approaches were used:

Identification: Using functions such as info() to detect non-null values.

Action: Removing rows with missing entries or replacing them with statistical values like mean or median.

Data Modification and Cleaning

Renaming and Dropping: Eliminating irrelevant columns (such as 'Gender' or 'Grade' in certain cases) to focus on important attributes.

Value Updating: Modifying specific data entries using indexing methods like loc or iloc.

Transformation and Grouping

Type Conversion: Ensuring that columns have appropriate data types (for example, converting 'CGPA' to float) for accurate calculations.

Grouping: Applying groupby() to categorize data (such as by 'Department') and using aggregation functions to summarize results.

Applications of Data Wrangling

Preprocessing for Machine Learning: Preparing clean and properly scaled data before model training.

Financial Auditing: Matching transaction records and eliminating duplicates.

Academic Analytics: Organizing student data by summarizing performance across departments.

Market Research: Combining customer data from different regions into a unified dataset.

** Conclusion **

This experiment highlights the importance of data wrangling as a foundational step in data analysis. By handling missing values, transforming data, and summarizing information effectively, raw data can be converted into a structured and insightful format. Proficiency in Pandas and NumPy for data wrangling ensures accuracy, consistency, and reliability in practical data-driven applications.
