# Mod1Project
Module 1 Project
Cary Mosley & Collin Loo
Our repository includes:

DataScrapeClean.ipynb - This file scrapes IMDB and box office mojo, pulls data from the Movie DB using an API call. It also cleans the data and merges the dataframes before exporting to a .csv that can be used for the data analysis.
DataAnalysis.ipynb- data analysis and visualizations

For this project we wanted to help determine a few factors that could impact movie profitability. We first checked some metrics to make sure that the movie industry has been consistently profitable. We then look at how movie stars, directors and genre could impact profitability. 

Our process started from scraping dating from IMDB.com, Box Office Mojo, and using an API call to get data from the Movie DB. We then cleaned and merged the different data before beginning our exploration.

The first thing we wanted to check was whether the movie industry has been profitable! Below we can see the average movie revenue versus movie budget over they years. 

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/ProfitabilityYear.png">

The average ROI was 2.8 with a standard deviation of 1.8 so we can be relatively confident that the movie industry as a whole has postiive ROI.

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/ROIoverTime.png">

Now, we want to know whether a movies "quality' based on either IMDB rating, metacritic score, or the Movie DB popularity has a strong correlation with the gross revenue for a movie. Surpisingly it doesn't! The correlations we found were all quite low between each of these quality metrics and the movie's gross. We looked at Log of the gross to make sure the correlation wasn't being ruined by outliers and found the same results. We looked at this versus ROI also and found a similar low level of correlation. There was a significantly higher correlation between popularity and box office revenue which makes sense as it is an indicator for people going to see the film versus it just being highly rated. The correlation between quality and gross was below 0.2 while the correlation between Popularity and Gross was almost 0.5!

Next we looked at whether the choice of director and movie star could have an impact!


<img src="https://github.com/CaryMosley/Mod1Project/blob/master/ROIStar.png">

Theres a huge spread in ROI grouped by star! Finding a star that grosses in the 75th percentile would result in 100% more profit than a median grossing star.The chart below shows the top 25 highest grossing stars.

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/25Stars.png">

If movie stars are the soul the movie, then directors are its brain. Naturally, the next question is should we hire less well know directors to save on costs and maximize return on investment. Or should we hire high caliber directors for the project to ensure better chance of success of the film? Equipped with the track records of the directors from the plot, we can make the appropriate selection to plan for a sound budget allocation.

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/25Directors.png">

The final area we examined was movie genre. By plotting out the performances of each movie genre for the last ten years, we can get a sense of our audience movie genre preferences. This is an important factor to consider when making a new movie. Animation, action and adventure movies have had the highest average gross since 2010.

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/GrossGenre.png">

This next chart is a supplement to the Top Box Office Grossing Movie by Genres graph. By evaluating both charts, we can see that the animation genre is on the rise, which might explain why it is the top on the Gross Mean Revenue chart. On the other hand, both action and adventure titles seem to be on a decline yet they still perform well in the market, based on the Gross Mean Revenue chart. To avoid a saturated market, it might be a better choice to produce action or adventure movie.

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/GenreYear.png">

Throughout this project we have accomplished a few things. We pulled data via webscraping and an API pull. Next we cleaned and merged this data. Finally we analyzed whether the movie industry was profitable and then looked at some factors that could influence profitability. We found that director and star choice as well as genre could have a large impact on movie revenue. Finally we bucketd the budget and looked at ROI by budget finding that films in the 10-20MM budget had the highest ROI

<img src="https://github.com/CaryMosley/Mod1Project/blob/master/Buckets.png">

