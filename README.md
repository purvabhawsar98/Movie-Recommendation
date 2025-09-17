# Movie-Recommendation
Movie recommendation project using pandas
# Overview
This project implements a basic movie recommendation system using the MovieLens dataset. It leverages collaborative filtering techniques (or content-based filtering, depending on extensions) to suggest movies based on user ratings and movie genres. The analysis is performed in a Jupyter Notebook environment, making it easy to explore and visualize the data.

# Key features:
- Data loading and exploration from MovieLens datasets.
- Basic data preprocessing (e.g., handling genres, ratings).
- Potential for building a recommendation engine (extendable with libraries like Surprise or scikit-learn).
This is an educational project for DSCI 501 (Data Science course), focusing on pandas for data manipulation and analysis.

# Dataset
The project uses the MovieLens 100K dataset from Kaggle, which includes:

- movies.csv: Movie metadata (ID, title, genres) – 3,883 rows.
- ratings.csv: User ratings (user ID, movie ID, rating, timestamp) – ~1,000,209 rows (note: large file; may need Git LFS or external download).
- users.csv: User demographics (ID, gender, age, occupation, zip code) – 6,040 rows.

# Requirements
Python: 3.8 or higher

# Libraries:
- numpy
- pandas
- jupyter (for running the notebook)
