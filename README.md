# EDA of Insurance Claims data

Analysis Steps:

Data Exploration:

The project starts with importing necessary libraries such as NumPy, Pandas, Matplotlib, and Seaborn.
The dataset is loaded using the Pandas read_csv() function and displayed to understand its structure.
The dataset comprises 1338 records with 9 features including age, sex, BMI, steps, children, smoker, region, insurance claim status, and claim amount.

Feature Overview:

A brief overview of the features is provided, highlighting both numerical and categorical variables.
Features are categorized based on their data types into numerical and categorical variables.

Data Quality Check:

The dataset is checked for null values using 'isnull().sum()', and no missing values are found.
Descriptive statistics including mean, standard deviation, minimum, maximum, and quartile values are calculated for numerical features.

Data Distribution:

Histograms are plotted to visualize the distribution of numerical features.
A box plot and count plot are created to explore the distribution of BMI and children's features, respectively.

Multivariate Analysis:

Pearson correlation coefficient is calculated to analyze the linear relationship between numerical features.
Heatmap and scatterplot matrices are used to visualize correlations between features.
Joint plots display the relationship between age and BMI, considering insurance claim status as a hue.

Advanced Visualization:

A bubble plot is generated to visualize the relationship between BMI, claim amount, smoking status, and the number of children.
The bubble plot highlights that smokers with higher BMIs tend to make larger insurance claims.

Conclusion:
The analysis provides insights into the relationships between different features and their impact on insurance claims. Through exploratory data analysis and advanced visualizations, patterns and trends within the dataset are identified, aiding in a better understanding of the factors influencing insurance claim amounts.

