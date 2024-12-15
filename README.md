# pandas-challenge
 Module 4 Challenge

This assignment focuses on analyzing school performance data to derive key metrics and insights. The analysis begins by classifying schools by type, calculating the total student count, per capita spending, and average test scores. It identifies the number of schools achieving math and reading scores of 70 or higher and calculates overall passing rates. A summary DataFrame consolidates these metrics. The assignment further identifies the highest and lowest-performing schools based on overall passing rates, saving and displaying the top and bottom five schools. It explores relationships between performance and spending, school size, and type by binning data into ranges using pd.cut, calculating averages, and creating summary DataFrames. The goal is to evaluate factors influencing school performance through data-driven insights.

The data reveals a surprising trend: schools that spend less money per student tend to have better performance outcomes. For example, schools in the lower spending range (less than $585 per student) demonstrate an average overall passing rate of 90.36%, while those in the highest spending range ($645-$680 per student) show a lower average passing rate of 53.52%. This suggests that efficient resource allocation or other factors may play a significant role in student success.

Conversely, school size appears to negatively impact performance results. Smaller schools, with fewer than 2000 students, achieve an average overall passing rate of 90%, whereas larger schools, with more than 2000 students, show a significantly lower passing rate of 58.28%. This trend indicates that larger student populations may face challenges such as less individualized attention, which could hinder academic achievement.