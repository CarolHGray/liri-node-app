# liri-node-app
Vanderbilt Trilogy Bootcamp - Homework 8

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



