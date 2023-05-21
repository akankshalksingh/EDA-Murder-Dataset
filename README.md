# EDA Murder Dataset

In this project, I explored the existing datasets in R to conduct exploratory data analysis (EDA). I primarily focused on the "murders" dataset and performed various data examination and visualization tasks using R functions and libraries. As a learner, the project focuses on the following:

1. Data loading and examination: We loaded the "murders" dataset and examined its column names using the names() function.

2. Data examination using str(), head(), and tail(): We used these functions to get insights into the structure, first few rows, and last few rows of the "murders" dataset. These functions help in understanding the data types, variable names, and overall structure of the dataset.

3. Descriptive data analysis: We determined the state with the maximum number of murders by using the which.max() function. Additionally, we suggested other potential data examination options, such as calculating summary statistics, identifying correlations between variables, and exploring patterns across different variables.

4. Data visualization: We used the plot() function to create a scatter plot, comparing total murders with population by dividing population by a million to achieve an appropriate scale. Proper labeling of the plot axes ensures clarity in understanding the relationship between these variables.

5. Histogram visualization: We utilized the hist() function to create a histogram, depicting the murder rate per 100,000 people using the formula (total / population) * 100000. Histograms provide a visual summary of the distribution of values, allowing us to observe patterns and variations in the murder rate across different states.

6. Boxplot visualization: We employed the boxplot() function to compare the murder rates across different regions. Boxplots provide a concise summary of the distribution of values and allow for easy comparisons between groups or categories.

7. Exploratory data analysis (EDA): We suggested exploring other data examination and visualization techniques to gain further insights into the dataset. This might include calculating summary statistics, identifying outliers, creating bar plots, scatter plots with different variables, or conducting statistical tests for hypothesis testing.

Throughout the project, we utilized various R functions and libraries such as dplyr, ggplot2, and ggpubr to manipulate, analyze, and visualize the data. These tools and techniques enable us to gain a deeper understanding of the dataset, identify patterns, and communicate insights effectively.

