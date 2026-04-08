# Logistic Regression Project – Advertising Dataset

## About This Project

In this project, I worked with a dataset related to online advertisements. The goal was to predict whether a user will click on an ad based on their behavior and basic information such as age, time spent on a website, and internet usage.

## What I Did

* Explored the dataset using different visualizations
* Analyzed patterns between users who clicked ads and those who did not
* Built a Logistic Regression model
* Evaluated the model’s performance

## About the Data

The dataset includes information such as:

* Daily time spent on the website
* Age
* Area income
* Daily internet usage
* Whether the user clicked on an ad

Some columns like city, country, and ad text were not used in the model because they are not suitable for this type of analysis.

## Data Exploration

I used visualization tools to better understand the data:

* A histogram to examine age distribution
* Joint plots to explore relationships between variables
* A pairplot to compare all features

One key observation was that users who spend more time on the website tend to be less likely to click on ads.

## The Model

I used Logistic Regression since this is a classification problem (clicked or not clicked).

Steps followed:

1. Selected relevant features
2. Split the data into training and testing sets
3. Trained the model
4. Generated predictions

## Results

The model achieved an accuracy of about 91%, which indicates strong performance. It was able to predict both classes (clicked and not clicked) effectively.

## What I Learned

* How to explore and understand a dataset using visualization
* How Logistic Regression works in a real application
* The importance of selecting appropriate features

## Tools Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn

## Final Thoughts

This project provided a solid introduction to classification using Logistic Regression. The results were good, and further improvements could be made by testing other models or tuning parameters.

