# Overview

Computing Vision sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t have much background in creating movies. You are charged with exploring what types of films are currently doing the best at the box office using different samples of available data. You then will translate those findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create.

# Business Understanding

Computing Vision is looking to become engaged in creating video content, but are unsure how to create successful movies. In order to  analyze available data and determine market trends, there are a few important questions that must be asked:

What are the current trends in the movie industry in terms of popular film genres and film review scores?

What types of films are performing well based on overall rating, and what characteristics make them successful?

How can Computing Vision's new movie studio leverage existing data to adjust their decisions on film production?

What key risks are involved in the movie industry?

How can Computing Vision's new movie studio measure and track performance over time and what metrics should be used to evaluate performance?

# Data Understanding and Analysis

Today, data understanding and analysis are essential as they enable both individuals and businesses to make informed decisions based on existing insights. However, without a solid foundation for identifying and analysing data, misinterpreting information can lead to poor decisions and easily avoided mistakes. Using a strong understanding of the relation of data to a problem, as well as relevant details within the data, we are able to identify patterns, trends, and relationships in order to provide insight for Computing Vision's decision making going forward.

## Data Sources

The primary data used for sourcing our information will be [The Movies DB](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Data/tmdb.movies.csv).

## Data Description

This is due to the database's tracking of genre, movie name, overall rating, and number of reviews submitted for each rating. Using this information, we are able to determine popularity by analysing the number of reviews, determine reception by analysing the overall rating, and create correlations between that information and different movie genres.

## Visualizations

An important aspect of analyzing data is charting the relationship between multiple variables in order to determine the relationship between those variables. Visualizations are a powerful tool for gaining insights and understanding from data. They allow us to see patterns, relationships, and outliers that may not be immediately obvious from raw data, and can help communicate insights and findings to others.

### Income by Rating and Genre
![Income by Rating and Genre](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Visualizations/heatmap.png)

This heatmap indicates the impact Genre and Rating has on Income. A general visible trend is that some genre's income are more impacted by rating, while some are consistent regardless of rating. It is important to note that ratings were limited between 5.7 and 8.3, for two important reasons. Ratings below 5.7 had a similar trend to ratings between 6.0 and 5.7, making any visible trends below that redundant. Ratings above 8.3 were visible outliers with very little volume of movies and thus when averaged within each genre the maximum average rating was 8.3.

### Income by Budget
![Income by Budget](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Visualizations/scatterplot.png)

This scatter plot displays the relationship between Income and Budget. A general visible trend is how increasing the films budget generally increases income and popularity. 

### Ratings by Top Directors
![Ratings by Top Directors](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Visualizations/bargraph.png)

This bar chart correlates the certain directors with higher ratings. A general visible trend of this chart shows that certain directors tend to average a higher rating on their films. It is important to note that directors that worked on less than 10 movies were omitted as their average ratings could be skewed by a low volume of data.

# Statistical Communication

Statistical Communication is an important part of ensuring that statistical information is used effectively and responsibly. It is essential for building trust in data and ensuring that decisions are based on the best available evidence.

## Inferenced Results

### Animation, Fantasy, and Adventure Are Typically Top Performing Genres

Within the heatmap, the general trend is that the genres 'Animation' and 'Fantasy' tend to have consistently high income, regardless of rating. Additionally, 'Fantasy' and 'Adventure' tend to have the highest potential for income dependant on genre. It is also important to note that regardless of reception, 'Documentary' and 'History' tend to have perform poorly when viewing average income at each rating.

### Generally Higher Budget Movies Produce Higher Revenues

Within the scatter plot, the general trend is that high budget films tend to have higher income and also a higher level of popularity. However, a budget of $100 million appears to be a general point where popularity and income begins to trend upwards, while a budget higher than $300 million tends to bring dimishing returns with certain outliers showing potential for higher and lower income at budgets over $400 million despite popularity trending lower than films at a $300 million budget.

### Choosing the Right Director Can Also Improve the Movie Ratings

Within the bar graph, the general trend is that 10 directors consistently perform well regarding ratings, with 3 in particular averaging a rating above 9.0 for their movies. However, it is important to note that even the worst performing director of the measured 10 tends to average above 8.4 for their ratings, indicating all of these directors may be valuable in creating a high performing movie.

## Interpretation

From these inferenced results, we can infer that six genres tend to profit best at a wider variety of ratings and recommend Computing Vision produce films within these genres. These genres are:

1. Animation
2. Adventure
3. Fantasy
4. Family
5. Science Fiction
6. Action

Additionally, we can see that as production budget increases, so does income. With this, we recommend that Computing Vision maintain a budget range between $100 million and $300 million, with low priority projects ranging between $100 million and $200 million and high priority projects ranign between $200 million and $300 million.

Lastly, there are 5 directors that we recommend Computing Vision pursues for their films in order to maximize their potential ratings for their films. These directors are:

1. Nm5083382
2. Nm6179119
3. Nm6179118
4. Nm6179115
5. Nm0331653

# Conclusion

Going forward, these general trends indicate a good start point for Computing Vision to pursue. However, we recommend Computing Vision collects more data, further clean the data of noise and outliers, work further with industry experts, and run regression analysis. We believe that with these next steps, computing vision will be able to fully optimize their decision making and perform successfully within the film industry.

# Appendix
[Final Presentation](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Final%20Presentation.pptx)

[Final Notebook](https://github.com/Jhuue/Flatiron-Capstone1/blob/main/Final%20Notebook.ipynb)