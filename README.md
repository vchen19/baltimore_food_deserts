# baltimore_walk_score_and_income

## Introduction
According to a study performed by the [Johns Hopkins Center for a Livable Future](https://clf.jhsph.edu/about-us/news/news-2015/1-4-baltimore-residents-live-food-desert), nearly 1 in 4 Baltimore residents live in areas with limited access to healthy foods, or areas commonly known as food deserts. Factors like distance to the nearest food store, poverty level, and healthy food availability index are considered when designating a community a food desert. Furthermore, racial disparities exist in food insecurity, with 34% of Baltimore’s Black residents living in such areas compared to only 8% of white residents. For policymakers, it will be important to understand how various factors relating to living in a food desert can impact life outcomes. This project is concerned with determining how factors that designate a community a food desert relate to life expectancy.

## Business question

How do healthy food availability, walk score, and income predict life expectancy?

## Analysis

All analysis was performed in Python with Google Colaboratory. The notebook can be found [here](https://github.com/vchen19/baltimore_food_deserts/blob/main/MiniProject5.ipynb). All data was taken from [Baltimore Open Data](https://data.baltimorecity.gov/). Life expectancy data can be found [here](https://github.com/vchen19/baltimore_food_deserts/blob/main/Life_Expectancy.csv), median household income data can be found [here](https://github.com/vchen19/baltimore_food_deserts/blob/main/Median_Household_Income.csv), healthy food availability index data can be found [here](https://github.com/vchen19/baltimore_food_deserts/blob/main/Average_Healthy_Food_Availability_Index.csv), and walk score data can be found [here](https://github.com/vchen19/baltimore_food_deserts/blob/main/Walk_Score.csv). The goal of the analysis was to gain a visual understanding of the relationship between the variables and how they relate to life expectancy, then to use multiple regression analysis to determine whether or not they can predict life expectancy.

## Results

![MHHI, HFAI, LE](https://github.com/vchen19/baltimore_food_deserts/blob/main/Median%20Household%20Income%2C%20Healthy%20Food%20Availability%20Index%2C%20and%20Life%20Expectancy.png)

![WS, HFAI, LE](https://github.com/vchen19/baltimore_food_deserts/blob/main/Walk%20Score%2C%20Healthy%20Food%20Availability%20Index%2C%20and%20Life%20Expectancy.png)

![WS, MHHI, LE](https://github.com/vchen19/baltimore_food_deserts/blob/main/Walk%20Score%2C%20Median%20Household%20Income%2C%20Life%20Expectancy.png)

![Multiple Regression](https://github.com/vchen19/baltimore_food_deserts/blob/main/Regression%20Analysis.png)

## Discussion

Both the visualizations and the multiple regression analysis indicate that the variables do not predict life expectancy very strongly. Thus, it may be more useful to divide the neighborhoods into clusters to determine if there are multiple different trends taking place in Baltimore, since it is clear that no single trend can accurately describe all of the neighborhoods.
