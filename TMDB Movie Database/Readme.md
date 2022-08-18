# Investigating a TMDB Movie Dataset

This project explores a TMDB movie database, a movie database that consists of about 10,000 movies collected from TMDB, inclusive of parameters such as movie titles, casts, genres, budget, revenue, user ratings, popularity and many more... An end to end analysis of the data from wrangling, cleaning, performing Exploratory data analysis, and making insights and conclusions on the data will be seen in this project, as well as limitations and future work to be done on the analysis.

## Dataset

The data set contains about 10,000 records and 21 columns. The data can be found via Kaggle [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), and documentation of the metadata and description for each column seen in the link.

## Code

I splitted the code various subsections and added a table of content to give better formatting to the notebook. The sections were:

- Introduction
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Conclusions

## Goal/Questions Answered

The goal of the project was to answer questions based on the data available, some of the questions asked and answered in the file include:

- Movie with Minimum and Maximum Profits
- Movie with highest and lowest Vote Average
- Most Occuring Genres produced over time
- Can highly rated movies be used to predict the success of a movie based on profits made
- Are longer movies more likely to be as profitable as average timed movies

## Dependencies/Libraries

Libraries used in this project include:

- pandas - for reading and exploring the dataset 
- numpy - allows for easy mathematical manipulations of dataset
- matplotlib - python plotting library to beautify visualizations
- seaborn - plotting library majorly for exploring visualizations as it does not have as much customizable features as matplotlib.
- %matplotlib inline - allows visualizations to be visible in notebook

## Summary of Findings

* **The Warrior's Way** movie has the highest budget, but it is also the same movie with the minimum profit. 
* **Avatar** is the movie with highest profit and revenue.
* **Drama** is the most produced movie genre.
* There is a positive relationship between rating and profit.
* Profit and vote averaged has a positive relationship, on the scatter plot, the highest profit fall among the highest vote rating.
* Vote average increases as the vote count increase.
* Popularity of movie is not dependent on the vote count.
* Movies with runtime generally greater than 200 minutes are not as popular as movies with shorter timeframe. 

## Limitations of Analysis

* The currency of the data was not given. There's a high probability that most of the financial column could be in different currency, meaning it would affect our analysis result.
* Our analysis is mainly descriptive, to get a better view of future predictions, we would want to explore the use of data science and machine learning algorithms


