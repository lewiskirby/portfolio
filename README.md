# Lewis Kirby
I am a final-year student at Loughborough University pursuing a newfound interest in data science following my industrial placement year.

## [Project 1: Pro Football Reference Webscrapers](https://github.com/lewiskirby/pfr-webscrapers)
#### Project Overview:
1. Created a webscraper using Python's BeautifulSoup module following the tutorial on the [Fantasy Football Data Pros website](https://www.fantasyfootballdatapros.com/) to find weekly fantasy data from 1999 onwards, based on the user's input
2. Using what I had learned, I then created an additional webscraper that is able to collect whole-season data for passing, rushing or receiving

## [Project 2: Todd Gurley Exploratory Data Analysis](https://github.com/lewiskirby/todd-gurley-EDA)
#### Project Overview:
1. Collected Todd Gurley's career game log data from [Pro Football Reference](https://www.pro-football-reference.com/)
2. Data cleaning
3. Creating new features
4. Visualisations

## [Project 3: Student Performance Regression Model](https://github.com/lewiskirby/student-performance)
#### Project Overview:
1. Collect data from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
2. Data cleaning and management
3. Exploratory data analysis
4. Model building
5. Model evaluation

## [Project 4: Fantasy Football Cheatsheet Creator](https://github.com/lewiskirby/ff-cheatsheet-creator)
#### Project Overview
1. Take input from user based on league settings
    - number of teams in the league
    - roster details
    - ppr rules
    - add details to dictionary for later use
2. Scraping ADP
    - use BeautifulSoup scrape player ADP for league's PPR format from [FantasyPros](https://www.fantasypros.com/)
    - create data frames for each positon, ordered by ADP
3. Find replacement players based on ADP
    - use the user's league details to find the ADP of the replacement player, ready to calculate value
4. Scraping player projections
    - use BeautifulSoup scrape player projections from [FantasyPros](https://www.fantasypros.com/)
    - create a data frame for all positions, ordered by prokected fantasy points
5. Calculate value over replacement and output cheatsheet
    - use replacement player dictionary and projection data frames to calculate each player's value over the replacement
    - create data frame ordered by value over replacement
    - save cheatsheet
