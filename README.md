# Formative-Assessment---Data-Preprocessing

1. Data Exploration
   
Steps:

Load the dataset and examine its structure.

List down unique values in each feature and find their lengths.

Perform statistical analysis (mean, median, mode, standard deviation) of numerical columns.

Rename columns for clarity if necessary.

2. Data Cleaning

Steps:

Identify and treat missing values.

Use methods such as removal, replacement with mean/median/mode, or imputation techniques.

Remove duplicate rows to ensure data uniqueness.

Identify and handle outliers using methods like Z-score, IQR, or domain knowledge.

Replace age value 0 with NaN.

Consistently treat null values across all columns.

3. Data Analysis

Steps:

Filter the dataset for rows where age > 40 and salary < 5000.

Plot a chart to visualize the relationship between age and salary.

Count the number of people from each place and represent it visually using bar charts or pie charts.

4. Data Encoding

Steps:

Convert categorical variables to numerical values using:

One-hot encoding: Create binary columns for each category.

Label encoding: Convert categories to integer labels.

5. Feature Scaling

Steps:

After encoding categorical variables, scale the features using:

StandardScaler: Standardize features by removing the mean and scaling to unit variance.

MinMaxScaler: Scale features to a given range, typically 0 to 1.
