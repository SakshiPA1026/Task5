# Task5
#Titanic Dataset - Exploratory Data Analysis (EDA)
This project performs a complete exploratory data analysis on the Titanic dataset using Python libraries like Pandas, Matplotlib, and Seaborn. 
The aim is to uncover meaningful insights, relationships, and patterns related to passenger survival.

✅ Steps Followed:
1. Basic Data Exploration
Used .info() to understand the structure, column types, and missing values.
Used .describe() to generate summary statistics of numerical and categorical data.
Applied .value_counts() on categorical columns (e.g., Sex, Pclass, Embarked) to examine distributions.

2. Visual Analysis
a. sns.pairplot()
Created pairwise scatter plots to explore interactions between numerical features, colored by survival status.
b. sns.heatmap()
Generated a correlation heatmap to visualize the strength of relationships between variables like Age, Fare, Pclass, etc.
3. Trend & Relationship Identification
Analyzed survival rates across gender, age, class, and family size.

Identified key trends such as:
Higher survival among females and first-class passengers.
Younger passengers had slightly better survival chances.

4. Additional Visualizations
Histograms: Showed distributions of Age, Fare, etc.
Boxplots: Compared variable spread and outliers (e.g., Age by Survived).
Scatterplots: Revealed relationships between variables like Fare and Age, colored by survival.

5. Observations from Visuals
Females had a significantly higher survival rate than males.
Passengers in 1st class were more likely to survive compared to those in 3rd class.
Survival was not random—clear patterns emerged based on socio-economic factors and demographics.

6. Summary of Findings
Key Influencing Features: Gender, Passenger Class, Fare, and Age.
Insights: Socioeconomic status and gender were strong indicators of survival.
Next Steps: These findings can guide predictive modeling, feature engineering, or decision tree analysis.

