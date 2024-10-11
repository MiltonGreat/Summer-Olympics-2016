# Summer-Olympics-2016

### Summary and Recommendations

#### 1. Overview

This project analyzes data from the modern Olympic Games, covering the period from 1896 to 2016. The analysis explores trends in athlete participation, gender representation, top-performing athletes and countries, and the popularity of various Olympic events over time. The goal is to use Exploratory Data Analysis (EDA) to uncover insights into the history and evolution of the Olympic Games.

These are the questions that are explored:

    What is the total number of athletes in each game?
    What is the total number of male vs. female athletes in each game?
    What is the growth rate of female participation over years
    Who are the top medal winning athletes?
    Who are the top medal winning countries?
    What is the age distribution of males vs. females
    What are the top summer sporting events?
    What are the top summer sporting events?

#### 2. Data

In this project you will analyze and visualize data on the modern Olympic Games, from the first games in Athens in 1896 to the Summer Olympics of Rio in 2016. The dataset include Summer and Winter Olympics data. You will work with 2 files:

- athlete_events.csv: Contains detailed information about athletes, the events they participated in, and the medals they won.

- noc_regions.csv: Contains information about National Olympic Committees (NOCs) and their corresponding regions/countries.

#### 3. Data Analysis Steps

1. Initial Data Exploration
2. Data Cleaning
3. Outlier Detection
4. Data Visualization

#### 4. Data Cleaning 

- Missing values for key attributes such as Age, Height, and Weight were filled using the mean, grouped by gender (male/female).
- Missing region data in the noc_regions dataset was filled using the notes column.
- The athlete and NOC datasets were merged to associate athletes with their respective regions.

#### 5. Data Visualization

- Athlete Participation Over Time: Bar plot showing the number of athletes participating in each Olympic game from 1896 to 2016.
- Male vs. Female Representation: Bar plot comparing male and female athlete representation over time.
- Top 20 Athletes by Medals: Horizontal bar plot showing the top athletes with the most Olympic medals.
- Top 10 Countries by Medals: Bar plot showing the top 10 countries with the highest total medal counts.
- Age Distribution: Box plot showing the distribution of athlete ages over time.
- Top Events by Gender: Bar plots showing the top Summer and Winter Olympic events by male and female athlete participation.

#### 6. Key Findings
      
Growth in Athlete Participation: The number of athletes in the Olympics has grown significantly over time, from a few hundred in the early games to over 10,000 in recent years.

Gender Representation: The Olympics have seen a steady increase in female representation, particularly in the latter half of the 20th century. Female participation now approaches parity with male athletes.

Top Athletes: Athletes like Michael Phelps and Larisa Latynina stand out as some of the most successful Olympians, having won record numbers of medals.

Top Countries: Countries like the United States, Soviet Union, and Germany have historically dominated the medal tables, winning thousands of Olympic medals.

Age Distribution: Olympic athletes tend to be in their 20s and 30s, but some sports like gymnastics feature younger athletes, while endurance events see a broader age range.

Popular Events: Football, Hockey, and Gymnastics are among the most popular Summer Olympic events, while Ice Hockey and Alpine Skiing dominate the Winter Olympics.

#### 7.  Source

https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results
