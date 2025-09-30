
# Exploring Survival Patterns on the Titanic

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover key factors that influenced passenger survival. Using Python and data visualization libraries, we analyze relationships and trends between age, fare, class, gender, family size, and survival outcomes.

# Project Overview

The goal of this analysis is to:

Understand how different features relate to survival (Survived).

Visualize distributions and patterns in the dataset.

Identify key survival trends (e.g., class, gender, age, fare).

Summarize findings in a structured and interpretable way.

# Tools & Libraries Used

Python 3.x

Pandas – data manipulation and cleaning

Matplotlib & Seaborn – data visualization

Jupyter Notebook – interactive analysis

# Visualizations & Insights

Key plots generated in this project include:

Histograms with KDE – Age and Fare distributions

Boxplots – Survival trends across Age, Fare, and Pclass

Scatterplots – Fare vs Age by Survival

Pairplot – Relationships among numerical features colored by Survival

Heatmap – Correlation matrix of numerical variables

# How to Run

Clone the repository

git clone https://github.com/aarlapudi/Exploring-Survival-Patterns-on-the-Titanic.git


Navigate into the project folder

cd Exploring-Survival-Patterns-on-the-Titanic


Install dependencies (if not already installed)

pip install pandas numpy matplotlib seaborn jupyter


Open the Jupyter Notebook

jupyter notebook titanic.ipynb


The notebook will open in your browser. Run each cell to see the data cleaning, visualizations, and insights.


# Conclusion 
### Summary of Survival Factors:
The visualizations collectively suggest that financial status (Fare/Pclass) was a much stronger predictor of survival than age.

### The Role of Age and Survival
Age was not a dominant predictor: The box plot of "Age Distribution by Survival" showed that the median age for both survivors and non-survivors was nearly identical (around 28-29 years).
Outliers: While both groups had age outliers, there was a slightly wider range of ages and a greater number of older outliers among those who did not survive.
### The Dominance of Fare and Class
Fare Correlates Strongly with Survival: The "Fare Distribution by Survival" box plot revealed a significant difference: the median fare paid by survivors (Group 1) was substantially higher (around 30) than the median fare paid by non-survivors (around 10-15).
Fare vs. Age: The "Fare vs Age by Survival" scatter plot reinforced this, showing that at higher fares (above 100), the points representing survivors (orange) heavily outnumbered the non-survivors, regardless of the passenger's age.
Fare and Class Hierarchy: The "Fare Distribution by Passenger Class" box plot confirmed the clear financial hierarchy: 1st Class paid the highest fares, followed by 2nd Class, with 3rd Class paying the lowest, which directly links fare and class to the previously observed survival advantage.
# Ticket Group Size and Fare
Higher Fare = Higher Survival in Groups: The "Ticket Group Size vs Fare by Survival" scatter plot indicated that for passengers traveling in small groups (size 2, 3, and 4), those who survived consistently paid the highest fares within those group categories. This suggests that even when traveling together, the cost of the ticket (and thus class) was the crucial survival advantage.

