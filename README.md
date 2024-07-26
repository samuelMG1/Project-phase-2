# Project-phase-2

Movie production Insights Project
Introduction
Welcome to the Movie production Insights Project! This project aims to provide a comprehensive analysis of current box office trends to guide the strategic decisions for our new movie studio. By leveraging data from multiple sources, we aim to identify the types of films that are currently performing best at the box office and translate these findings into actionable insights.

Objectives
Identify the Highest Grossing Films: Determine which movies are leading in box office earnings.
Determine the Most Common Genres Among Top-Grossing Movies: Analyze the prevalent genres among the highest-grossing films.
Analyze the Correlation Between Box Office Performance and Movie Ratings: Investigate how movie ratings correlate with their box office success.
Identify the Most Successful Film Studios: Recognize the studios that produce the most successful films.
Data Sources
The datasets used in this project are from various sources, including:

Box Office Mojo
IMDB
Rotten Tomatoes
TheMovieDB
The Numbers
Datasets Used
im.db.zip: Zipped SQLite database containing movie_basics and movie_ratings tables.
bom.movie_gross.csv.gz: Compressed CSV file with box office gross information.
Project Steps
1. Data Extraction and Cleaning
SQLite Database:
Extracted and cleaned data from movie_basics and movie_ratings tables.
Dropped rows with null values in crucial columns like original_title and genres.
Merged the tables on the movie_id column.
CSV File:
Loaded and cleaned bom.movie_gross.csv.gz.
Removed commas and converted the foreign_gross column to numeric.
Filled missing values in foreign_gross with the median of the column.
2. Data Merging
Merged the cleaned data from the SQLite database with the cleaned CSV data using the title and year columns.
3. Feature Engineering
Created new columns like total_gross by summing domestic_gross and foreign_gross.
Condensed filters using parameters for a more user-friendly dashboard experience.
4. Visualization and Analysis
Generated key visualizations to meet project objectives:
Bar charts and line graphs to identify highest-grossing films.
Pie charts and heat maps to determine common genres among top-grossing movies.
Scatter plots to analyze the correlation between box office performance and movie ratings.
Treemaps and bubble charts to identify the most successful film studios.
5. Dashboard Creation
Created an interactive dashboard in Tableau, including:
Key Performance Indicators (KPIs).
Dynamic filters using parameters.
Interactive visualizations to explore data insights.
Dashboard Title
Strategic Insights for Our New Movie Studio

Dashboard Caption
Unlocking Box Office Success: A Comprehensive Analysis of Top-Grossing Films

Welcome to our Strategic Insights Dashboard! This tool provides a deep dive into the current trends in the film industry, offering actionable insights to guide our new movie studio's strategic decisions. Explore the data to discover:

Highest Grossing Films: Identify the top-performing movies at the box office.
Popular Genres: Uncover the most common genres among high-grossing films.
Performance and Ratings Correlation: Analyze how box office success aligns with movie ratings.
Leading Film Studios: Recognize the studios behind the most successful films.
Navigate through the visualizations to understand the market dynamics and inform our production strategies for creating compelling, high-grossing content.

How to Use
Open the Tableau Dashboard: Load the provided Tableau workbook file.
Interact with Filters: Use the parameter-driven filters to switch between different filtering options like Genres, Year, and Studio.
Explore Visualizations: Click on different visualizations to dive deeper into the data and gain insights.
Conclusion
This project provides a solid foundation for understanding the current trends in the movie industry. By leveraging the insights gained from this analysis, our new movie studio can make informed decisions to produce content that resonates with audiences and achieves box office success.

Contact
For any questions or further information, please contact [Your Name] at [Your Email].
