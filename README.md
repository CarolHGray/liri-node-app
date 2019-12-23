# liri-node-app
Homework 8 
Vanderbilt Trilogy Bootcamp
  
Technologies used:  Javascript, Node.js, moment.js, Bandsintown API, Spotify API and OMBd API.


## LIRI

LIRI is a node.js command line application that takes in user-entered parameters and returns information, sort of like
a speechless SIRI.  The user enters "node.js" onto the command line in terminal, followed by a specific command and a search parameter.  

There are four available commands:
* concert-this
* spotify-this-song
* movie-this
* do-what-it-says

## concert-this :guitar:

The "concert-this" command uses the Bandintown API to find upcoming concerts for the selected band/artist.  Venue, location and dates are provided for all results - if the artist has concerts scheduled.  The dates are formatted using moment.js.

Here's an example of a search for concerts by guitar artist Peter Frampton:

![Image of concert-this](https://github.com/CarolHGray/liri-node-app/blob/master/Screenshot%202019-12-23%20at%2001.36.56.png)

## spotify-this-song :notes:

The "spotify-this-song" command uses Spotify API to return data about the selected song.  Each result gives the name of the song and an artist who recorded it, a link to preview the song and an album name. 

This example shows the result of a search for "All I want for Christmas":

![Image of movie-this](https://github.com/CarolHGray/liri-node-app/blob/master/Screenshot%202019-12-23%20at%2001.39.47.png)

## movie-this :film_projector:

The "movie-this" command uses the OMBd API to get information about the movie entered in the search parameter.  It returns the title, release year, IMBd rating, rotten tomato rating, country of production, languages, plot summary, actors and actresses in the film.

Here is a screen shot for a user search of the movie "The Report":

![Image of movie-this](https://github.com/CarolHGray/liri-node-app/blob/master/Screenshot%202019-12-23%20at%2001.40.15.png)

## do-what-it-says

The "do-what-it-says" command reads the random.txt file.  In this application, it defaults to a spotify-this-song data return for the BackStreet Boys song, "I Want It That Way".

![Image of do-what-it-says](https://github.com/CarolHGray/liri-node-app/blob/master/Screenshot%202019-12-23%20at%2001.41.58.png)


All results are captured and appended in a log.txt file.  
