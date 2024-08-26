Project Overview
This project aims to explore and analyze a Netflix dataset to gain insights into specific movie characteristics. The analysis focuses on:

The most frequent duration of movies released in the 1990s.
The count of short action movies, defined as action movies with a duration of 90 minutes or less.
Dataset
The dataset used for this analysis is a publicly available Netflix dataset, which includes information on various shows and movies, such as:

title: The title of the movie or show.
duration: The duration of the movie or show.
release_year: The year the movie or show was released.
type: The type of content (e.g., Movie, TV Show).
genre: The genre of the movie or show (e.g., Action, Comedy)

Here's an updated README that focuses on analyzing the duration of movies from the 1990s and counting short action movies:

Netflix Dataset Analysis
This repository contains a Python-based analysis of a Netflix dataset. The analysis is focused on extracting key insights, specifically the duration of movies released in the 1990s and the count of short action movies in the dataset.

Table of Contents
Project Overview
Dataset
Data Processing
Key Analysis
Results
Installation
Usage
Contributing
License
Project Overview
This project aims to explore and analyze a Netflix dataset to gain insights into specific movie characteristics. The analysis focuses on:

The duration of movies released in the 1990s.
The count of short action movies, defined as action movies with a duration of 40 minutes or less.
Dataset
The dataset used for this analysis is a publicly available Netflix dataset, which includes information on various shows and movies, such as:

title: The title of the movie or show.
duration: The duration of the movie or show.
release_year: The year the movie or show was released.
type: The type of content (e.g., Movie, TV Show).
genre: The genre of the movie or show (e.g., Action, Comedy).
Data Source
The dataset can be accessed from Kaggle's Netflix Dataset.
Data Processing
1. Subsetting Duration of 1990s Movies
We filter the dataset to include only movies released between 1990 and 1999 and analyze their duration to understand the typical length of movies from that decade.
2. Counting Short Action Movies
We define short action movies as those with a duration of 90 minutes or less and the genre 'Action'. We then count the total number of such movies in the dataset.
Key Analysis
Duration of 1990s Movies
We analyze the duration of movies released in the 1990s to identify trends in movie length during that decade, including average duration, most common duration ranges, and outliers.

Count of Short Action Movies
By filtering for action movies with a duration of 90 minutes or less, we determine the number of short action films available on Netflix.

Results
Summary of Findings:
1990s Movie Durations: The analysis reveals the range and distribution of movie durations for films released in the 1990s, providing insights into the typical length of movies from that era with the most frequent being 94mins.
Short Action Movies: A total of 7 short action movies (90 minutes or less) were identified in the dataset.
