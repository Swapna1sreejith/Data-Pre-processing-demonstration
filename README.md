# Data-Pre-processing-demonstration
This repository shows Preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise.

## Employee-Data-Preprocessing
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Dataset adding here Employee Dataset

Key Components fulfilled in Data preprocessing:

### Data Exploration:
● Explore the data

● List down the unique values in each feature and finding its length.

● Perform the statistical analysis and renaming of the columns.

### Data Cleaning:
● Finding the missing and inappropriate values, treating them appropriately.

● Removing all duplicate rows.

● Finding the outliers.

● Replacing the value 0 in age as NaN

● Treating the null values in all columns using any measures(removing/ replace the values with mean/median/mode)

### Data Analysis:
● Filtering the data with age >40 and salary<5000

● Plotted a chart with age and salary coloumns which shows that employees aged 35 to 45 receive the highest salaries, with a peak around 40 years old. Salaries decrease for employees younger than 35 and older than 45.

● Counting the number of people from each place and represented it visually shows Mumbai has the highest count of employees, followed by Calcutta and Chennai. Nagpur and Bhopal has the lowest count among the listed locations.

### Data Encoding:
● Converting categorical variables such as Employer, Employee_Location and Employee_country into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.

### Feature Scaling:
After the process of encoding, performed the scaling of the features using:

● Standardscaler  

● Minmaxscaler.
