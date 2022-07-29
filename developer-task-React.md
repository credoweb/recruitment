## Web Development IMDb Task

We at CredoWeb are fans of the epic Game of Throne series.
Your task (should you choose to accept it) is to consume the public [IMDb API](https://imdb-api.com/) and display all the seasons and all episodes (with the poster of each episode) of the show according to this basic wireframe:

> ![mockup](wireframe-omdb.png)

We'd like to point out this is not the actual design just a wireframe to illustrate the basic view we aim.

SSome help for the IMDb API:

* Here you can [request](https://imdb-api.com/) a free API key to the IMDb
* It uses IMDb IDs - the Game Of Throne id is `tt0944947`
* The following Api endpoints should do the job, but there are many more you could use:
    * https://imdb-api.com/en/API/Title/{APIKey}/tt0944947 - to get data about the Series and its Seasons
    * https://imdb-api.com/en/API/SeasonEpisodes/{APIKey}/tt0944947/{seasonNumber} - to get data about episodes in a Season
    * https://imdb-api.com/en/API/Title/{APIKey}/{episodeID} - to get data about a single Episode


.. and just a few pointers below for the task:

* The development should be done using the React.
* You can use any UI library of your choice or write your own styles.
* Episodes are displayed in a listing. (As on the wireframe)
* The star icon (add/remove) is used to save the current episode to favorites (save in local storage)

If you feel like you want to show us what you're really capable of, here is a list of potential enhancements that we have come up with. 
You can always go the extra mile and do not limit yourself to it if you think of any other possible feature enhancement that you want to include in your submission. 

* Improve the speed of the page in terms of the images/content loading.
* Infinite scrolling (loading in more episodes as you scroll).
* A search functionality based on episode name.
