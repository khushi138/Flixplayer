# Movie Recommendation System (Content based filtering)


Content Based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions.

Movie details are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api.

## API key

Use this website https://www.themoviedb.org/, to get the api key.

## How to run the project?

1. Clone this repository .
2. Install all the libraries mentioned in the [requirements.txt] with the command `pip install -r requirements.txt`
3. Get API key from https://www.themoviedb.org/.
4. Replace YOUR_API_KEY in **both** the places (line no. 15 and 29) of `static/recommend.js` file and save the file.
5. Run the file `main.py` using command `python main.py` from  the terminal of your project directory.
6. Type this url `http://127.0.0.1:5000/` in the address bar of your browser.



## Similarity Score : 
To recommend movies to a user, similarity score is used. It is a machine learning method that uses a nearest neighbour approach to identify the similarity of two or more objects to each other based on algorithmic distance function.


### Dataset Resources

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

