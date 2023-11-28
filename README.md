# Mobile_Usage_Impact_on_Visual_Search_Performance_Analysis

    #Overview

        This project investigates the relationship between mobile usage patterns and cognitive performance, particularly in visual search tasks. By utilizing a comprehensive statistical analysis approach, the study aims to understand how factors like age, gender, and daily mobile usage impact cognitive response times.

    #Mathematics and Statistics

        The project employs various statistical techniques and mathematical concepts, including data preprocessing, frequency distribution analysis, linear and multiple regression, and ANOVA tests, to derive meaningful insights from the dataset.

    #Implementation

        #Libraries and Packages
            Pandas and NumPy: Data manipulation.
            Seaborn and Matplotlib: Data visualization.
            Scikit-Learn: Linear regression modeling.
            SciPy and StatsModels: Statistical testing and ANOVA.
            Logic and Methodology
            Focused on data preprocessing, prediction modeling, and hypothesis testing to investigate the impact of mobile usage on cognitive tasks.

        #Outcomes

            Detailed insights from each sub-task, including data quality assurance, pattern revelation in mobile usage, prediction modeling, and variance analysis across different groups.

    #Challenges and Resolutions

        #Challenges
            Addressing data quality issues.
            Selecting suitable statistical tests.
            Interpreting complex data relationships.
            Resolutions
            Employed data cleaning techniques.
            Conducted a literature review and experimented with various statistical methods.
            Utilized visualizations and statistical summaries for interpretation.
    
        #Summary of Insights

            This section encapsulates the key findings and interpretations derived from the data analysis. It highlights how various factors such as age, gender, and daily mobile usage influence cognitive performance in visual search tasks.

            Insight 1: Frequency Table Analysis
            Gender disparities in pickup frequencies were observed, with one gender group notably dominating.
            Zero counts in specific daily average pickups suggest potential data collection issues or uncommonly low activity periods.
            Variability in daily pickups appears concentrated around specific count values, indicating potential peak activity times for the predominant gender group.
            
            Insight 2: Kernel Density Estimate Plot
            A primary activity range was identified between 100-200 daily average minutes.
            The right-skewed distribution suggests occasional extended usage well beyond the typical range.
            Presence of negative values and multiple peaks within the distribution calls for further investigation into data entry practices and activity patterns.

            Insight 3: Age vs. Response Time Analysis
            An increase in response times was correlated with higher age groups, suggesting a decline in visual search speed with age.
            Lower age groups showed greater consistency in response times, while older age groups displayed increased variability.
            Significant outliers in the '41-60' and '61-80' age groups indicate potential individual differences in visual search abilities.
            
            Insight 4: Gender vs. Response Time Violin Plot
            Distinct response time distributions across gender groups were noted, with Gender 2 showing the fastest median response time.
            The distribution shape for Gender 1 was traditional and slightly right-skewed, while Gender 3 showed a flatter distribution with a higher median response time.
            
            Insight 5: Correlation and Linear Regression
            A mild positive correlation between age and response time suggests an age-related increase in visual search task duration.
            Negative correlation and regression coefficient for 'DailyAvgMins' indicate an inverse but weak relationship with response time.
            
            Insight 6: Multiple Regression
            The model included multiple predictors but only explained approximately 21.88% of the variability in response times, suggesting other influential factors are at play.
            Age showed a more pronounced effect on response time than daily average minutes of mobile use.
            
            Insight 7: Scenario 1 Statistical Analysis
            ANOVA results highlighted significant differences in reaction times across age groups but not mobile usage groups.
            The post-hoc analysis did not reveal significant differences in reaction times attributed to mobile usage, contradicting the initial hypothesis.
            
            Insight 8: Scenario 2 Statistical Analysis
            Two-Way ANOVA indicated no significant effect of brain training on reaction times, nor a significant interaction between brain training and mobile usage.
            Post-hoc tests affirmed the lack of significant differences in reaction times, suggesting brain training's ineffectiveness in this scenario.
            
            Each insight is backed by statistical evidence and aligns with the hypotheses tested in the study. This section is intended to provide a concise yet comprehensive understanding of the project's findings.

    #References

        1.Davis, M. (2022). Data Analysis in Research: Methods and Applications. Cambridge University Press.
        
        2.Ilhan, A. (2023). Advanced Statistics. GitHub.
        https://github.com/22036435/Advanced_Statistics.git
        
        2.Lewinson, E. Pandas-dev, Data Analysis Toolkit. GitHub.
        https://github.com/pandas-dev/pandas.git
        
        3.Lopez, G. (2020). Reporting in Data Science: Best Practices. Journal of Data Science, 18(3), 234-249.
        
        4.What Factors Predicts Someone's Anxiety? (2021). ML Project which uses data preprocesing and visualizations as a part of the project. [Code].
        https://www.kaggle.com/code/davidleeee/what-factors-predicts-someone-s-anxiety/notebook#Visualizing-Survey-Result-Difference-Between-Each-Class-For-Each-Category

        5.Lewinson, E. (2019). Verifying the Assumptions of Linear Regression in Python and R. GitHub. https://github.com/erykml/medium_articles/blob/fa0f32b140f844275f52f06ac6666aa8f45173f8/Statistics/linear_regression_assumptions.ipynb