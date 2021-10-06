# movies-recommender-system
An app which tells the similar movies to which you select

Hey friends This web app tells the similar movies to the movie you select.
***
I made this app with the help of streamlit library. This library helps to deploy the web app very easily and with a good interface.

The logic used behind the app is
1. Clean the datasets and get the useful insights
2. Create the tags from the datasets. 
3. Doing vectorization on the tags so that we can get the similarity among the different tags. 
4. Arranging the similarity in descending order and getting the top 5 movies TMDB id.
5. Fetching the poster from TMDB data base using the movie ID.
***
_And Finally we display the top 5 similar movies related to the moview selected by the user_
[website link](https://movie-mohit.herokuapp.com/)
