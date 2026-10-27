# Netflix Movie Data Analysis

Exploratory Data Analysis (EDA) on around 9,800 Netflix movies using Python, Pandas, Matplotlib and Seaborn, to find out which genres, movies and years stand out.

## What this project does
I cleaned a raw movies dataset and used it to answer five questions:
1. Which genre appears most often?
2. How are movies spread across the rating categories?
3. Which movie has the highest popularity?
4. Which movie has the lowest popularity?
5. Which year had the most movie releases?

## Key findings
- Drama is the most common genre (about 14.5% of entries)
- Spider-Man: No Way Home has the highest popularity score
- The number of releases has grown sharply since the 1990s

## Steps I followed
- Checked for missing values and duplicates (none found)
- Converted `Release_Date` to a datetime and extracted the year
- Dropped columns I didn't need (`Overview`, `Original_Language`, `Poster_Url`)
- Grouped `Vote_Average` into 4 categories: not_popular, below_avg, average, popular
- Split multi-genre entries so each movie-genre pair gets its own row
- Made charts with Seaborn and Matplotlib to answer the questions

## Tools used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## What I learned
- How to clean a messy dataset step by step: dates, unused columns, and a genre column with several values in one cell
- That running a cell twice can break things. I got an error when I ran the year-extraction cell a second time
- That charts with many labels get cluttered, so axis choice and label rotation matter

## How to view
Open `Netflix_Movie_Data_Analysis_Project.ipynb` in this repo. GitHub shows the code and charts directly. The dataset (`mymoviedb.csv`) is included, so the notebook can be run as is.

## Credit
This is my first data analysis project. I took help from YouTube tutorials while building it.
