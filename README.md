# Netflix Movies Analysis (1980 - 2020)

## Project Overview
This project analyzes Netflix movies released in the United States between 1980 and 2020. The aim  of this analysis is to explore, in order to understand trends and navigation in the production of movies under Netflix company in the United States for over 4 decades ; as regards genres, budgets and revenues. The project involves data cleaning in Excel, generating insights using SQL, and visualizing results with PowerBI.

## Dataset
The dataset consists of information about movies available on Netflix, including:
- **Title**: The name of the movie.
- **Release Date**: The year the movie was released.
- **Production Company**: The company that produced the movie.
- **Genre**: The genre(s) of the movies.

- **Budget**: The budget for the  production. 

- **Gross**: The total earnings from the movie.
- **Directors**: The directors of the various movies. 
- **Writers**: The movie writers. 
- - **Stars**: The main star of each movie. 
    
### Data Source
- The data was sourced from Kaggle. 
## Data Cleaning
The raw data was cleaned and transformed using Microsoft Excel to:
- Remove duplicates.
- Fill in missing values.
- Standardize genre names.
- Convert data types where necessary (e.g., dates budgets and revenues).
- Updating some missing values as it regard to names of directors, stars and writers.

The cleaned data file can be found in the `/data` folder as `cleaned_netflix_data.xlsx`.

## SQL Insights
SQL queries were executed to extract meaningful insights from the cleaned dataset. Key insights include:

1. **Top 5 Movies with the Highest Revenue Generation over 4 decades**:
   - Analysis of gross revenues to identify the movies with the highest earnings. 

2. **Top 5 Most Profitable Movie Companies**:
   - Analysis of gross revenues to identify the companies with the highest earnings from their movies.

3. **Genre Trends**:
   - Insights into the popularity of different genres over the years, with respect to its revenue generation. 

4. **Decade Movie Release Trends**:
   - A breakdown of how many movies were released each decade over the past four decades.

The SQL queries used for this analysis can be found in the `/sql` folder.

## Visualizations
PowerBI was utilized to create interactive visualizations based on the insights generated from the SQL queries. Key visualizations include:

- **Profitable Genre**: A visual representation of the genres with the highest revenue generation over decades.
- **Revenue Trends**: A line chart showing the gross revenue trends from 1980 to 2020.
- **Top Companies by Revenue**: A chart highlighting the top movie companies based on total gross revenues.

Visualizations can be found in the `/visualizations` folder.

## How to Use This Repository
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-DanteTheXplorer/netflix-movies-analysis.git
