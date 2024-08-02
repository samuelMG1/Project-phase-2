# Film production Insights 

## Introduction
Welcome to the Film production Insights  This project aims to provide a comprehensive analysis of current box office trends to guide the strategic decisions for our new movie studio. By leveraging data from multiple sources, we aim to identify the types of films that are currently performing best at the box office and translate these findings into actionable insights.


## Objectives
Identify the Highest Grossing Films: Determine which movies are leading in box office earnings.
Determine the Most Common Genres Among Top-Grossing Movies: Analyze the prevalent genres among the highest-grossing films.
Analyze the Correlation Between Box Office Performance and Movie Ratings: Investigate how movie ratings correlate with their box office success.
Identify the Most Successful Film Studios: Recognize the studios that produce the most successful films.

### Data Sources
The datasets used in this project are from various sources, including:

* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB
* The Numbers
#### Datasets Used
im.db.zip: Zipped SQLite database containing movie_basics and movie_ratings tables.
bom.movie_gross.csv.gz: Compressed CSV file with box office gross information.
Project Steps

1. Data Extraction and Cleaning

    -SQLite Database:
Extracted and cleaned data from movie_basics and movie_ratings tables.
Dropped rows with null values in crucial columns like original_title and genres.
Merged the tables on the movie_id column.

    -CSV File:
Loaded and cleaned bom.movie_gross.csv.gz.
Removed commas and converted the foreign_gross column to numeric.
Filled missing values in foreign_gross with the median of the column.

1. Data Merging
Merged the cleaned data from the SQLite database with the cleaned CSV data using the title and year columns.
1. Feature Engineering
Created new columns like total_gross by summing domestic_gross and foreign_gross.
Condensed filters using parameters for a more user-friendly dashboard experience.

![alt text](<Images/Interactive Filter.png>)

### 1. Dashboard Visualization and Analysis
Generated key visualizations to meet project objectives:
Bar charts and line graphs to identify highest-grossing films.
Pie charts and heat maps to determine common genres among top-grossing movies.
Scatter plots to analyze the correlation between box office performance and movie ratings.
Treemaps and bubble charts to identify the most successful film studios.

1. Dashboard Creation
    Created an interactive dashboard in Tableau, including:
    * Key Performance Indicators (KPIs).
    * Dynamic filters using parameters.
Interactive visualizations to explore data insights.
Dashboard Title
Strategic Insights for Our New Movie Studio

1. Dashboard Caption
Unlocking Box Office Success: A Comprehensive Analysis of Top-Grossing Films
/
A Kpi image:

![alt text](<Images/KPI Image.png>)

1. Top 20 genres with highest profit
   
   ![alt text](<Images/Top 20 genres with highest profit.png>)

2. top 5 successful filmstudio per year
   
   ![alt text](<Images/top 5 successful filmstudio per year.png>)
## Recommendations

1. Focus on Proven Genres
   * Prioritize production in high-performing genres such as Action, Adventure, and Animation. These genres have shown strong box office returns and audience appeal.
2. Certain film studios have a track record of producing high-grossing movies.

   * Recommendation: Establish partnerships or collaborations with successful studios identified in the analysis. This can help leverage their expertise and increase the likelihood of box office success.

Contact
 
=======
