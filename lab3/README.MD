# Lab 3 – Exploratory Data Analysis

## Dataset Description
In this lab, I performed exploratory data analysis (EDA) on the Titanic dataset. The goal was to understand the structure of the data, explore relationships between variables, and identify basic patterns before any advanced analysis.
The dataset contains information about Titanic passengers such as:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Data Preparation
First, I loaded the dataset and checked the data types using df.dtypes. I reviewed the columns and identified numeric and categorical variables. Then I selected appropriate columns for visualization and analysis.


### Univariate Analysis
I explored individual variables such as Age and Fare to understand their distributions.

### Bivariate Analysis
I examined relationships between variables using plots. For example, I created scatter plots to study the relationship between Age and Fare.

### Correlation Analysis
I generated a correlation matrix using a heatmap to analyze relationships between numeric features.

## Observations
The correlation between Age and Fare appears weak. Passenger class seems to influence ticket fare. The dataset includes both numeric and categorical variables which require different analysis approaches.

## Tools Used
Python, Pandas, Matplotlib, and Seaborn.

## Conclusion
Exploratory data analysis helped me understand the dataset structure and key patterns. This step is important before moving to further analysis or machine learning tasks.