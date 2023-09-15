# Microsoft-Movie-Analysis

## Overview
***
###### Business Problem
Microsoft have decided to create a new movie studio and require more insight into which types of films are doing best at the box office in order to choose the genre of movies to produce that can generate the most profit.

This project uses descriptive statistical analysis on data gathered from [IMDb website](https://www.imdb.com/) to gain insight into which combination of genres topped the league in these areas.

Three seperate datasets were used for this analysis to gain insight into which combination genres of movies topped the domestic gross sales, foreign gross sales, had the top average ratings and number of votes.  The results of the top 20 combination genres in Domestic Sales, Foreign Sales and number of votes was clearly the combination Action, Adventure & Sci-Fi, with adventure being present in the majority of the top 20 of the 3 categories. My recommendation for which type of Movie to produce would be Action, Adventure & Sci-Fi as this is the most predominant combination in the analysis. In Domestic and Foreign gross the combination Adventure, Animation & Comedy also faired well which would be my second recommendation.I would also highly recommend that Adventure and Action paired with either Animation or Fantasy  is a successful combination.Adventure was clearly a strong genre for popular successful movies as it appeared in all combinations of genre for the top 3 highest domestic gross.

### Methods
***
#### Data
The data analysed came from IMDb website. IMDb (an acronym for Internet Movie Database) is a popular worldwide online database of infomation relating to all movies, television programs, video games and streaming content online. I used 3 files from IMDb to answer the question of which genres were most successful, mainly focusing on the Domestic and Foreign Gross sales along with average ratings given and number of votes received.

After checking the information on each table to see column names and null values, I joined the two datasets, movie_basics and movie_ratings together using the 'movie_id' column as it was a unique identifier creating a new dataframe called df. I then joined the dataset movie_gross with the new dataframe using the title as the unique identifier, creating a combined new dataset called merged_df.

Checking the information on the new dataframe merged_df, I then cleaned up the null values by removing them.

## Evaluation
#### Results
3 of the above graphs, Domestic Gross, Foreign Gross and Number of Votes clearly show that Adventure, Action and Sci-Fi combination are most successful in Domestic and Foreign Gross Sales. Its clear also to see that the adventure genre is popular across the board especially when elements of animation, action and or comedy are also included.

The graph showing Top 20 Average Ratings shows Adventure as a well received genre.

To improve confidence in the results next time I would:-

Include the movie classification This could have narrowed down the target audience the most successful movies were aimed at i.e PG etc.

Broken the data into the relevant years to see if there are changes year by year in the top genres of movies, see if audience tastes change over time.

### Conclusions

This analysis leads to three recommendations regarding types of movies that are successful:-

**Movies with the genre combination Action, Adventure & Sci-Fi** topped the leaderboard in both Domestic and Foreign Gross Sales, it is also a genre that has been voted for the most,this combination is obviously a hit at the box office worldwide, make this the first type of movie to produce for success. **Movies with Adventure, Animation and Comedy** were the next most successful in Foreign Gross and second in domestic gross, use this combination as the next or alternative type of movie to produce. Movies in the top 20 number of votes yielded slighly different results but Action, Adventure and Sci-Fi combination did come out 1st still. Adventure genre seems constant in all the above graphs so must be a key element of any movie to be produced. Questions to consider:

Limitations-Could the same movie be classified into different genres by different audiences? Who classifies the genres for each movie? Can the classification of genres be improved to provide a more benchmark approach? Future analysis could include the movie classification ie PG, MA etc to see which audience the most successful movies were made for.



