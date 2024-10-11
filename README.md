# Summer-Olympics-2016

### Summary and Recommendations

#### 1. Overview

This Python code is part of a project aimed at analyzing a dataset related to NBA player performance. The goal of the project is to explore player statistics, identify trends in performance, and visualize key insights using Exploratory Data Analysis (EDA) techniques. The code uses Pandas for data manipulation and Seaborn/Matplotlib for data visualization.



Use pandas to answer the following questions, then replicate the given visualizations using Matplotlib and seaborn:

    What is the total number of athletes in each game?
    What is the total number of male vs. female athletes in each game?
    What is the growth rate of female participation over years
    Who are the top medal winning athletes?
    Who are the top medal winning countries?
    What is the age distribution of males vs. females
    What are the top summer sporting events?
    What are the top summer sporting events?

#### 2. Data

In this project you will analyze and visualize data on the modern Olympic Games, from the first games in Athens in 1896 to the Summer Olympics of Rio in 2016.

The dataset include Summer and Winter Olympics data. You will work with 2 files:

    athlete_events.csv
    noc_regions.csv



#### 3. Data Analysis Steps

1. Initial Data Exploration
2. Data Cleaning
3. Outlier Detection
4. Data Visualization

#### 4. Data Cleaning 

- Columns with excessive missing values (e.g., Minutes Per Game, Offensive Rebounds, and Defensive Rebounds) were removed to maintain data quality.
- Missing values in numerical columns were filled with the column mean.
- Team names were standardized from abbreviations (e.g., MIL to Milwaukee Bucks).

#### 5. Data Visualization

- Athlete Participation Over Time: Bar plot showing the number of athletes participating in each Olympic game from 1896 to 2016.
- Male vs. Female Representation: Bar plot comparing male and female athlete representation over time.
- Top 20 Athletes by Medals: Horizontal bar plot showing the top athletes with the most Olympic medals.
- Top 10 Countries by Medals: Bar plot showing the top 10 countries with the highest total medal counts.
- Age Distribution: Box plot showing the distribution of athlete ages over time.
- Top Events by Gender: Bar plots showing the top Summer and Winter Olympic events by male and female athlete participation.

#### 6. Key Findings
      
Relationship Between Assists and Turnovers: Guards tend to have higher assists but also accumulate more turnovers due to their ball-handling role, as shown in the scatter plot.

Average Assists Per Game by Position: Guards had the highest average assists per game, followed by forwards and centers, as shown in the bar plot.

Outliers in Assists and Turnovers: Boxplots of assists and turnovers indicate potential outliers in the dataset. These could represent standout performances or data inconsistencies that may need further investigation.

Correlation Between Player Metrics: The correlation matrix reveals that certain metrics, like points and assists, are positively correlated, suggesting that players who pass the ball effectively may also score more points.

#### 7.  Source

https://www.kaggle.com/datasets/thedevastator/unlocking-the-secrets-of-nba-player-performance

