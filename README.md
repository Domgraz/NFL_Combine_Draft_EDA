# Combine-Draft_data

## Table of Contents:
* [General info](#general-info)
* [Techologies and Libraries](#technologies-and-libraries)
* [Data Source](#data-source)
* [Data Explanation](#data-explanation)

## General Info
 This project mainly focuses on data cleaning with some analysis and visualizations included, through the NFL data that I have brought together. I wanted to see some of the relationship between the combine drills prospects run, where they are selected in the draft, and how productive they are as players in the NFL.

## Technologies and Libraries

* Python 3.9
* Pandas
* Matplotlib
* Glob


## Data Source
All of the datasets were csv files exported from the site pro football reference, with a combine and draft results dataset being taken for each year. I am listing the combine and draft result page for the most recent year below: 

Combine Results: https://aws.pro-football-reference.com/draft/2023-combine.htm

Draft Results: https://www.pro-football-reference.com/years/2023/draft.htm



## Data Explanation
The data that I have included falls between the years of 2010-2023 and there should be two csv files per year included in the data folder. 

 ### Combine Dataset:
This dataset goes into measurements of drills during the NFL combine for invited players, note that not all the drafted players would be included in this dataset. The data included:

* Player - players first and last name
* Pos - position of player
* School - last college they attended
* Ht - height measured at combine in   (ft-in) format
* Wt - weight measured at combine, in lbs
* 40yd - 40 yard dash timed in seconds
* Vertical - vertical jump measured in inches
* Bench -  number of bench press reps  measured
* Broad Jump - broad jump measurement in inches
* 3Cone - 3 cone drill measured in seconds
* Shuttle - short shuttle drill measured in seconds
* Drafted(tm-rnd-yr) - team, round, and pick if player was selected in draft

### Draft Dataset:
This dataset goes into career stats of players, with some repetitive data from the Combine dataset. The data included: 

* Rnd - round number player was drafted
* Pick - pick number player was drafted with
* Tm - team player was drafted by
* Pos - position of player
* Age - age of the player 
* To - last year the player was in the league
* AP1 - number of all pro awards
* PB - number of pro bowl awards
* St - number of years as starter
* wAV - weighted career approximate value
* DrAV - approximate value for the team that drafted the player 
* G - number of games played 

* Passing Stats:
    * Cmp - passes completed
    * Att - passes attempted
    * Yds - passing yards
    * TD - passing touchdowns
    * Int - thrown interceptions

* Rushing Stats:
    * Att - rushing attempts
    * Yds - rushing yards
    * TD - rushing touchdowns

* Recieving Stats:
    * Rec - number of receptions
    * Yds - recieving yards
    * TD - recieving touchdowns

* Defensive Stats:
    * Solo - number of solo tackles
    * Int - number of defensive interceptions
    * Sk - number of sacks

        