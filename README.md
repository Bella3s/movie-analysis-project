# Movie Performance Analysis Overview

**Author:** Isabella Scribner

## Overview

This project takes in movie data from four different sources in order to analyze what movies have been successful. The analysis shows that (actionable suggestions here). Microsoft can utilize this data in its consideration of the new movie studio venture.


## Business Problem

Microsoft would like some initial data one what movies have been "recently successful in the box office."  In this analysis we explore in depth specifically what genres have done well on average over the past twenty years.  Furthermore, this analysis focuses on domestic results as the venture would most likely be tested here prior to being released internationally.  In order to see what genres have been sucessful, both measures of monitary success and popularity will be taken into consideration.


## Data

Four sources of movie data was provided for this analysis:
* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDatabase](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

While the data from Rotten Tomatoes is disregared in this analysis due to the smaller sample size, the rest of the four sources are utilized. The data includes swaths of information including movie title names, domestic gross income, production budget, genre, vote count, vote average, etc.


## Methods

Python, with the pandas, sqlite3, and matplotlib libraries, along with descriptive statistics are utilized to show what genres have been most successful on average over the past twenty years. As this analysis focuses on genres, the data (after being cleaned) is all grouped by this variable, and then then the top ten most 'sucessful' are graphed for each measure of success. 

## Results

The analysis goes over four main questions using the extracted data:

> 1. What genres of movies make the most domestic gross income?

The striking outlier was the `Family, Fantasy, Musical` genre that spiked high above the rest of the data. Furthermore, the Action and Adventure genres were present as aspects of many of the genres that made the most domestic gross income on average over the past 20 years.
    
> 2. What genres of movies are the most expensive to make?

Action and Adventure genres pop up as aspects in the genres with the highest production budgets.  The other notable genre that appears as an aspect in many of the top ten is Science Fiction.

> 3. What genres of movies make the most amount of profit?

Again, the `Family, Fantasy, Musical` genre far surpases any other genre in terms of average net incomme over the past 20 years. The other notable genres included Action, Adventure, Drama, and Comedy.

> 4. What genres of movies are the most popular?

The Action, Adventure, and Drama genres are all highly rated. The `Action, Adventure, Sci-Fi` genre specifically had more interaction from audiences (more votes) than any other genre from the TMDB data, however even that outlier had substantially less interaction than the top ten from the IMDB data; Drama was the most interacted with from this data set, which can be explained in part as it is the genre that has the most amount of movies total.  Lastly, we see that drama, documentary, and comedy movies are all quite popular.

## Conclusions

Putting the results all together, there are a few different directions Microsoft could direct their movie studio to.  The surest best seems to be to pursue movies in the action and adventure genres. While they are on the higher end of the budget spectrum, movies with these two categories incorporated in their genres have been popular and made profits over the past 20 years. 

They could also look into creating dramas, as they would cost less money to make, would still make decent profit and gain traction and interaction with audiences as they tend to be quite popular.  Although they would be competing with a wide scope of movies already in this genre.

If interested in more of a niche market, Documentaries would be the way to go as they would be generally very well received by viewers, and would not be as expensive to create, even if profits would also be less as well.  

Lastly, Microsoft could pursue the family-friendly types of movies.  The positives of going in this direction is that these movies tend to be very popular, and have the potential to garner the highest net income by leaps and bounds.  However, this would also be a rather competitive market, going up against companies like Disney and Pixar that have, and continue to dominate the market.

### Next Steps

Further research and planning of course must be completed prior to the launch of this new venture. Other than just a genre study, information on what directors and writers have been successful would be imperative to see who to potentially hire. Furthermore, investigation on trends over time would be helpful, both in identifying trends genres that do well when released in a specific time of year (such as releasing a holiday themed drama in November or December rather than in March or June), and in historical trends over the years.  It would also be good to dig into more recent data as well, looking only at the past five years rather than averages over the past 20. Lastly, investigating how all of these results change when talking on an international level rather than only domestically would need to be investigated prior to expanding business in this direction as well.

## For More Information

See the full analysis of the genre results in the [Jupyter Notebook](https://github.com/Bella3s/movie-analysis-project/blob/master/movie_performance_analysis.ipynb), or review in this [presentation](https://github.com/Bella3s/movie-analysis-project/blob/master/pdfs/presentation.pdf).

## Repository Structure


```
├── images
├── pdfs
├── zippedData
├── README.md
├── movie_performance_analysis.ipynb
```