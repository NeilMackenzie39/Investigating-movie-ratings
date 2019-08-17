# Investigating-movie-ratings
Use of basic statistics principles to investigate Fandango's response to inflated movie ratings

## Getting Started
This repository contains a jupyter notebook of the code to execute this project as well as the .csv files required to run the notebook.

## Project Information
This guided project was completed at the end of a 'Statistics Fundamentals' [course](https://www.dataquest.io/course/statistics-fundamentals/) on Dataquest.io. Some of the steps followed in this project were guided but the analysis and conclusions are my own work. 

## Dataset contents
The two datasets included in this repository are:
- fandango_score_comparison.csv which contains rating information for movies released in 2014 and 2015.
- movie_ratings_16_17.csv which contains rating information for movies released in 2016 and 2017

A description of the columns contained in each of the datasets listed above is given below

### Columns in fandango_score_comparison.csv

Column|Definition
|---|---|
FILM|The film in question
RottenTomatoes|The Rotten Tomatoes Tomatometer score for the film
RottenTomatoes_User|The Rotten Tomatoes user score for the film
Metacritic|The Metacritic critic score for the film
Metacritic_User|The Metacritic user score for the film
IMDB|The IMDb user score for the film
Fandango_Stars|The number of stars the film had on its Fandango movie page
Fandango_Ratingvalue|The Fandango ratingValue for the film, as pulled from the HTML of each page. This is the actual average score the movie obtained.
RT_norm|The Rotten Tomatoes Tomatometer score for the film , normalized to a 0 to 5 point system
RT_user_norm|The Rotten Tomatoes user score for the film , normalized to a 0 to 5 point system
Metacritic_norm|The Metacritic critic score for the film, normalized to a 0 to 5 point system
Metacritic_user_nom|The Metacritic user score for the film, normalized to a 0 to 5 point system
IMDB_norm|The IMDb user score for the film, normalized to a 0 to 5 point system
RT_norm_round|The Rotten Tomatoes Tomatometer score for the film , normalized to a 0 to 5 point system and rounded to the nearest half-star
RT_user_norm_round|The Rotten Tomatoes user score for the film , normalized to a 0 to 5 point system and rounded to the nearest half-star
Metacritic_norm_round|The Metacritic critic score for the film, normalized to a 0 to 5 point system and rounded to the nearest half-star
Metacritic_user_norm_round|The Metacritic user score for the film, normalized to a 0 to 5 point system and rounded to the nearest half-star
IMDB_norm_roundThe IMDb user score for the film, normalized to a 0 to 5 point system and rounded to the nearest half-star
Metacritic_user_vote_count|The number of user votes the film had on Metacritic
IMDB_user_vote_count|The number of user votes the film had on IMDb
Fandango_votes|The number of user votes the film had on Fandango
Fandango_Difference|The difference between the presented Fandango_Stars and the actual Fandango_Ratingvalue

### Columns in movie_ratings_16_17.csv

Column|Description
|---|---|
movie|Name of the movie
year|Release year of the movie
metascore|Metacritic rating of the movie (the "metascore" - critic score)
imdb|IMDB rating of the movie (user score)
tmeter|Rotten Tomatoes rating of the movie (the "tomatometer" - critic score)
audience|Rotten Tomatoes rating of the movie (user score)
fandango|Fandango rating of the movie (user score)
n_metascore|Metascore normalized to a 0-5 scale
n_imdb|IMDB rating normalized to a 0-5 scale
n_tmeter|Tomatometer normalized to a 0-5 scale
n_audience|Rotten Tomatoes user score normalized to a 0-5 scale
nr_metascore|Metascore normalized to a 0-5 scale and rounded to the nearest 0.5
nr_imdb|IMDB rating normalized to a 0-5 scale and rounded to the nearest 0.5
nr_tmeter|Tomatometer normalized to a 0-5 scale and rounded to the nearest 0.5
nr_audience|Rotten Tomatoes user score normalized to a 0-5 scale and rounded to the nearest 0.5


