Movies Data Analysis Project
This project is a data analysis of a movies dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. 
The aim is to extract insights about movie popularity, voting trends, genre distributions, and production trends over the years.
The dataset (`mymoviedb.csv`) contains information about ~9,800 movies, including:

- Release date
- Title
- Overview
- Popularity score
- Vote count
- Average vote rating
- Original language
- Genre(s)
- Poster URL
  
Data Cleaning
Steps performed:
- Removed unnecessary columns: `Overview`, `Original_Language`, `Poster_Url`
- Converted `Release_Date` to year
- Checked for and removed duplicate and null values
- Categorized `Vote_Average` into 4 levels:
  - `not_popular`, `below_avg`, `average`, `popular`
- Exploded multi-genre rows into single genre per row
  
   What’s Covered:

Cleaned a dataset of ~9,800 movies

Converted release dates to years

Removed unnecessary columns and duplicates

Categorized vote averages (popular, average, etc.)

Separated multiple genres per movie

  Tools Used:

Python
Pandas
Matplotlib
Seaborn
Google Collab

 Q1: Most Frequent Genre?
- **Thriller** is the most frequent genre.

 Q2: Which genres get the highest votes?
- **Drama** and **Thriller** receive the highest number of `popular` votes.

 Q3: Most Popular Movie?
- *Spider-Man: No Way Home* (Genres: Action, Adventure, Science Fiction)

 Q4: Least Popular Movie?
- *The United States vs. Billie Holiday* and *Threads*

 Q5: Which year had the most movie releases?
- **2020** had the highest number of movie releases.
