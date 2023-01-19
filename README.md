# 2022-Forbes-Billionaire-Analysis
------
# Project Overview

In this project, I analysed Forbes 2022 Billionaire list  with the objective of drawing out interesting facts such as the most richest man and woman, youngest billionaire and the industry with the top billionaires.

------

# Data Sourcing and Cleaning

The Forbes Billionaire dataset was obtained online from Kaggle and comprised 2268 rows and over 20 columns. I imported the dataset into powerbi's power query window and analysed the dataset for errors and inconsistences. Columns with irrelevant metadata such as the about were removed while other columns with disjointed names were changed into something more comprehensible. Examples of such columns are personName which was changed to Name, finalWorth changed to Worth and Category changed to Industry. The worth column which was in text datatype was changed to an integer datatype to enable calculations to be done on it. When all errors were cleaned up, the dataset was uploaded to powerbi for further analysis and visualization.

-----


# Analysis

The total number of Billionares was gotten using the COUNTROWS DAX function while the total number of male and female billionaires were calculated using the CALCULATE and COUNTA function. Next, the total sum of billioniare worth was calculated using the SUM function and billionaires ages were grouped into bins for easy analysis of the age with the most billionaires. Next results and interesting datapoints were visualized using cards, barcharts and tables while a histogram was used to visualize the age bins.

------

# Conclusion

Analysis of the Forbes Billionaire list for 2022 showed a total of 2268 billionares of which 88% (2341) were males and 12% (311) were females showing a significant gender disparity. The country with the most billionaires was the United States and the industry with the most billionaires Finance and Investment. The age-group with the most billionaires is the 50 - 55 years age group and 70% of billionaires were self-made as against 29% who inherited their wealth. The youngest billionaire was 19 year old Kevin David Lehman while the oldest billionaire was Wang Yanqing. Finally, the richest man and woman for 2022 were Elon Musk and Francoise Bettencott with a networth of $219 billion and $75 billion respectively. 
