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



## Conclusions



### Next Steps

Just with the data provide, so much more analysis can be done; for example, what directors were the most successful by all the measures of success? What writers were most successful? Furthermore, analysis of how successful genres, directors, and writers are over time would be very helpful in identifiying trends or cycles of success (both seasonally within a single year, as well as over a span of years).  Additionally, it would be usfuly to dig into more recent data -- the information provided was lacking sufficient entries for acceptable generalizations for just the past 5 years. 

Lastly, all of this analysis, while extremely useful in pointing the company in the right direction for the venture, must be put in context with what exactly the company is aiming to achieve, what their values are in creating content (for example what messages would they like to put out into the world), and what their budget looks like.

## For More Information

See the full analysis of the genre results in the Jupyter Notebook, or review in this presentation.

## Repository Structure

**pretty sure I need a folder with the presentation + jupyter notebook in PDF format ???**

```
├── images
├── zippedData
├── movie_performance_analysis.ipynb
├── README.md
├── Movie_Performance_Presentation.pdf (???)
```



Examples of some different things in text for when put this overview together for final submission:

Insert a picture:
![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/awesome.gif)

Insert an image:
![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

Bulleted list with Sub Bullets
* `im.db.zip`
  * Zipped SQLite database (you will need to unzip then query using SQLite)
  * `movie_basics` and `movie_ratings` tables are most relevant
* `bom.movie_gross.csv.gz`
  * Compressed CSV file (you can open without expanding the file using `pd.read_csv`)



The text below is in a indedted box seperat from the normal text:

> Communicating basic data analysis results to diverse audiences via writing and live presentation

> Refer to the [repository readability reading](https://github.com/learn-co-curriculum/dsc-repo-readability-v2-2) for more tips on best practices
