# Mini_Project-ETL
# House Price Prediction ETL Project

 # 1. Project Title
House Price Prediction – ETL Pipeline

# 2. Objective
The main objective of this project is to build an ETL (Extract, Transform, Load) pipeline using a House Price Prediction dataset. The project extracts the raw house price data, cleans and transforms the data, generates useful reports, and stores the processed data for further analysis.

# 3. Data Source
The dataset used in this project is the House Price Prediction Dataset. It contains information about houses such as area, number of bedrooms, bathrooms, floors, year built, location, condition, garage, and price.

The raw dataset is stored in the raw_data folder.

# 4. ETL Workflow
The ETL process consists of three main stages:

# Extract
- Read the House Price Prediction CSV dataset.
- Display the number of records and columns.
- Store the raw dataset.

# Transform
- Remove duplicate records.
- Handle missing values.
- Remove unwanted columns.
- Change required data types.
- Remove invalid values.
- Sort records based on price.
- Filter records based on price.
- Remove invalid values.

# Load
- Save the cleaned dataset.
- Save the generated reports in the reports folder.
- Store the processed output for further use.

# Workflow:

Raw Dataset → Extract → Transform → Reports → Load

# 5. List of Transformations
The following transformations were performed on the dataset:

1.Duplicate Removal – Removed duplicate house records.

2.Missing Value Handling – Filled missing numerical values using the median and categorical values using the mode.

3.Column Removal – Removed the Id column because it is only an identifier.

4.Data Type Conversion – Converted required numerical columns into suitable data types.

5.Invalid Value Removal – Removed records having invalid or zero values for important fields such as area and price.

6.Sorting – Sorted house records according to price.

7.Filtering – Filtered houses based on a selected price condition.

8.Invalid Value Removal – Removed records having invalid or zero values for important fields such as area and price.

# 6. Reports Generated
The following reports were generated:

1. Cleaned House Dataset

- cleaned_house_data.csv

2. Top 10 Expensive Houses

- top10_expensive_houses.csv

3. House Price Summary Statistics

- house_price_summary.csv

All reports are stored inside the reports folder.

# 7. Challenges Faced
Some challenges faced during the project were:

- Handling missing values in the dataset.
- Identifying and removing duplicate records.
- Selecting useful transformations for the dataset.
- Removing unwanted or invalid records.
- Organizing the ETL project into proper folders.
- Saving the processed data and reports in the correct locations.

# 8. Learning Outcomes
Through this project, I learned:

- The basic concept of ETL.
- How to extract data using Python and Pandas.
- How to clean and transform a dataset.
- How to handle missing and duplicate values.
- How to filter and sort data.
- How to create useful reports from processed data.
- How to organize an ETL project structure.
- How to save processed data using CSV files.

# 9. Future Improvements
The project can be improved in the future by:

- Adding more data validation checks.
- Using larger and more updated datasets.
- Creating more detailed reports and visualizations.
- Automating the ETL pipeline.
- Adding a user interface for viewing reports.
- Connecting the pipeline to a database instead of only using CSV files.
