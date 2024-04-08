# Mobile_Usage_Impact_on_Visual_Search_Performance_Analysis

## Overview

The goal of this project is to better understand how mobile usage habits affect cognitive function, specifically when it comes to visual search tasks. The goal of the study is to determine how age, gender, and daily mobile usage affect cognitive response times by applying a thorough statistical analysis approach.

## Mathematics and Statistics

To extract useful insights from the dataset, the project makes use of a number of statistical methods and mathematical ideas, such as frequency distribution analysis, linear and multiple regression, data preprocessing, and ANOVA tests.

# Implementation

## Libraries and Packages

Pandas and NumPy: Data manipulation.

Seaborn and Matplotlib: Data visualization.

Scikit-Learn: Linear regression modeling.

SciPy and StatsModels: Statistical testing and ANOVA.

## Logic and Methodology

Focused on data preprocessing, prediction modeling, and hypothesis testing to investigate the impact of mobile usage on cognitive tasks.

# Outcomes

Comprehensive findings from every sub-task, such as variance analysis between groups, prediction modeling, data quality assurance, and mobile usage patterns.

# Challenges and Resolutions

## Challenges

Addressing problems with data quality.

Choosing appropriate statistical testing.

Analyzing intricate data relationships.

## Decisions

Used methods for cleaning data.

Reviewed the literature and tested out different statistical techniques.

Used statistical summaries and visualizations to aid in interpretation.
    
# Summary of Insights

The main conclusions and interpretations from the data analysis are summarized in this section. It emphasizes the ways in which age, gender, and regular use of a mobile device affect one's ability to think clearly when performing visual search activities.

Insight 1: Frequency Table Analysis

There were gender differences in the frequency of pickups, with one gender group clearly dominating.
Zero counts in particular daily average pickups point to possible problems with data gathering or periods of unusually low activity.
Daily pickup variability seems to be focused around certain count values, suggesting possible peak activity periods for the dominant gender group.

Insight 2: Kernel Density Estimate Plot

It was determined that the range of 100–200 daily average minutes was the key activity range.
The distribution is right-skewed, indicating that usage is occasionally far above the usual range.
Additional research into data input procedures and activity patterns is necessary in light of the presence of negative values and several peaks within the distribution.

Insight 3: Age vs. Response Time Analysis

Higher age groups were associated with longer response times, which may indicate that visual search speed decreases with age.
Response times were more consistent among younger and older age groups, but more variable across senior age groups.
Significant outliers in the age ranges '41-60' and '61-80' suggest that there may be individual variances in visual search skills.
            
Insight 4: Gender vs. Response Time Violin Plot
            
Different gender group response time distributions were observed, with Gender 2 exhibiting the fastest median response time.
Gender 3 displayed a flatter distribution with a higher median response time, whereas Gender 1 had a typical distribution shape that was slightly tilted to the right.
            
Insight 5: Correlation and Linear Regression

Age-related increases in the duration of visual search tasks are suggested by a slightly positive connection between age and reaction time.
For "DailyAvgMins," the regression coefficient and negative correlation point to a weakly inverse association with response time.
            
Insight 6: Multiple Regression

Even with several variables, the model was only able to account for around 21.88% of the variation in response times, indicating the presence of additional significant components.
Age had a greater impact on response time than the average number of minutes spent using a mobile device each day.
            
Insight 7: Scenario 1 Statistical Analysis

Significant differences in reaction times across age groups were shown by the ANOVA results, but not between groups that used mobile devices.
Contrary to the original hypothesis, the post-hoc analysis did not show any significant variations in reaction times related to cellphone usage.
            
Insight 8: Scenario 2 Statistical Analysis

There was no significant interaction between brain training and mobile usage, according to a two-way ANOVA, nor was there a significant effect of brain training on reaction times.
The lack of significant improvements in reaction times was confirmed by post-hoc tests, indicating that brain training was unsuccessful in this particular situation.
            
Every insight supports the study's tested hypotheses and is supported by statistical evidence. The goal of this part is to give readers a succinct yet thorough grasp of the project's findings.

## References

1.Davis, M. (2022). Data Analysis in Research: Methods and Applications. Cambridge University Press.
        
2.Ilhan, A. (2023). Advanced Statistics. [GitHub](https://github.com/22036435/Advanced_Statistics.git).
        
3.Lewinson, E. Pandas-dev, Data Analysis Toolkit. [GitHub](https://github.com/pandas-dev/pandas.git).
        
4.Lopez, G. (2020). Reporting in Data Science: Best Practices. Journal of Data Science, 18(3), 234-249.
        
5.What Factors Predicts Someone's Anxiety? (2021). [ML Project which uses data preprocesing and visualizations as a part of the project](https://www.kaggle.com/code/davidleeee/what-factors-predicts-someone-s-anxiety/notebook#Visualizing-Survey-Result-Difference-Between-Each-Class-For-Each-Category).

6.Lewinson, E. (2019). Verifying the Assumptions of Linear Regression in Python and R. [GitHub](https://github.com/erykml/medium_articles/blob/fa0f32b140f844275f52f06ac6666aa8f45173f8/Statistics/linear_regression_assumptions.ipynb).
