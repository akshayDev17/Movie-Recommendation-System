# Functionalities implemented<a name="funcitonalities"></a>

1. searching of movies
2. on matching any results
   1. display the poster, name, IMDB rating, title of the movie, overview, genre, release date, total-running time, and status(whether released or yet to release)
   2. main cast for that movie, i.e. faces+names+actor description(**actor biography**) for each actor belonging to this cast can be seen
   3. top reviews on the movie(a balance between good and bad movies for a holistic view) are also shown
   4. on the bottom, a list of recommended movies, based on matching genre/IMDB rating/cast members represented by their respective posters is also present.





# Dataset used<a name="dataset"></a>

* [IMDB 5000 movie](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset) dataset was used as part of this project
* this is a publicly available `.csv` file containing information about many movies, such as 
  * color type - whether the movie is available in colored format or if its available only in black and white.
  * Director name
  * Movie Duration
  * Director's Facebook page
  * Gross earnings of the movie
  * Genre(s)
  * Name of each actor,their facebook pages(if they exist) and their position in the poster(facenumber) belonging to the main cast of the movie
  * IMDB link, rating of the movie
  * Country the movie is from
  * Budget
  * Release Date
  * number of users who have voted
  * total facebook likes for this movie
* [the movies dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) also available publicly on Kaggle
  * contains the end-credits information, i.e. main-cast and background crew details, as well as ID of the movie, w.r.t. **[The Movies Database](https://www.themoviedb.org/)**.