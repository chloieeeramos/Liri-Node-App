# Liri-Node-App

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

## How To Use 
Use node to run this program. Use node liri.js then run one of the following commands, then add search text:

* `concert-this`
* `spotify-this-song`
* `movie-this`
* `do-what-it-says`

### When running a command follow it by desired text/search.
Example:
node liri.js movie-this mr.nobody

### When no command has been entered:

Example:
![](https://github.com/chloieeeramos/Liri-Node-App/blob/master/screenshots/Screen%20Shot%202019-08-06%20at%2010.30.39%20PM.png)

### When spotify-this-song command is used you will be provided with:

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from
* If no song is provided then your program will default to "The Sign" by Ace of Base.

Example: 
![](https://github.com/chloieeeramos/Liri-Node-App/blob/master/screenshots/Screen%20Shot%202019-08-06%20at%2010.33.56%20PM.png)

### When movie-this command is used you will be provided with:

* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Rotten Tomatoes Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.
* If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.

Example:
![](https://github.com/chloieeeramos/Liri-Node-App/blob/master/screenshots/Screen%20Shot%202019-08-06%20at%2010.32.51%20PM.png)

### When do-what-it-says command:
A random.txt file with search for spotify-this-song "I want it that way." This will give you the spotify results of "I want it that way."

Example:
![](https://github.com/chloieeeramos/Liri-Node-App/blob/master/screenshots/Screen%20Shot%202019-08-06%20at%2010.50.00%20PM.png)

### Technologies Used
* JavaScript
* Node.js
* Spotify API
* Bands in Town API
* OMDB API
