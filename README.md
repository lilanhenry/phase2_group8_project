# Project to Determine Important Factors to Consider when Venturing into Movie Production Business

## Overview

Use exploratory data analysis to generate insights for a business stakeholder who wants to venture into the business of creating video content through a new movie studio. The task at hand is to explore what types of films are currently doing the best at the box office and the translate those findings into actionable insights that the head of your company's new movie studio can use to help decide what type of films to create.

## Business Understanding
Our company plans to enter the original video content space by launching a film studio, despite limited experience in film production. To support this venture, we need to analyze box office trends and pinpoint high-performing film genres. These insights will guide leadership on strategic genre focus.
## Problem Statement
Analyze and identify top-performing genres, directors, optimal runtimes, release timing, audience ratings, and MPAA classifications across demographic segments. This analysis aims to provide insights into box office dynamics and assess key factors influencing movie success.

## Data Understanding And Data Analysis
The files, sourced from various locations, come in multiple formats: some are compressed CSV or TSV files, accessible with spreadsheet tools or pd.read_csv, while IMDB data is stored in a SQLite database. Links to access the data are provided below.
#### Data Source
https://www.boxofficemojo.com/
https://www.imdb.com/
https://www.rottentomatoes.com/
https://www.themoviedb.org/
https://www.the-numbers.com/
### The Libraries 
* Pandas - Enables us to manipulate imported datasets saved as dataframes.
* Numpy - Enables us to compute mathematical functions as well as perform array operations.
* Seaborn - Enables us to visualise the data.
* Matplotlib - Additional library to assist in visualising the data.
* Scipy.stats - Assists in performing statistical calculations.
* Sqlite3 - Allows us to perform SQL operations and access database data in this Jupyter notebook.
*  %matplotlib inline - displays matplotlib plots directly within the notebook cells, making visualization outputs appear inline with code.


- After importing libraries, we load and review each dataset to identify those relevant for analysis.Then we consolidated them based on a common attribute into a single master dataset for streamlined analysis.
- Data cleaning, handling missing values and duplicates
- Finally, we performed exploratory data analysis to address the following objectives.

###### Objectives
* Analyze correlation between runtime and genre, and their impact on average ratings.
* Evaluate release date influence on genre ratings to identify high-performing genres over time.
* Assess directors’ ROI performance by genre.
* Identify directors known for critically acclaimed films in top-rated genres.
* Determine highest ROI movie based on production costs and box office earnings.
## Conclusion / Recommendation
* January shows the lowest movie ratings across all genres. To optimize audience reception, we recommend avoiding major releases during this month.
* Focus investment on high-ROI genres—Horror, Mystery, Documentary, Drama, and Animation—while expanding into Comedy, Crime, Biography, Thriller, Adventure, and Action to maximize returns.
* To attract a wider audience, the company should focus on high-rated genres: Adventure, Action, Drama, and Comedy. Additionally, runtime has no effect on ratings and should not be a production priority.
* Certain genres tend to align closely with specific MPAA ratings. For instance from the above analysis Action and Adventure films are often rated PG-13 or R, suggesting they cater to both younger viewers and adults. Films rated G or PG typically generate higher revenues due to their family-friendly appeal, particularly in genres such as Animation and Family. Similarly, genres like Action and Adventure and Drama tend to exhibit higher box office revenues.
 
* Focus investment on high-ROI genres—Horror, Mystery, Documentary, Drama, and Animation—while expanding into Comedy, Crime, Biography, Thriller, Adventure, and Action to maximize returns.