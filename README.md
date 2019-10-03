# liri-node-app introduction
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

[Link to app demo](file:///Users/naldojozze/Downloads/Oct%202,%202019%2010_12%20PM.webm)

# How to Use
Use node to run this program. Use node liri.js then run one of the following comands, then add search text:

- "concert-this" Artist
   - Will call the Bands In Town API and return the first result of a concert matching the artist that you entered.
- "spotify-this-song" Song
   - Will call the Spotify API and return the first result matching the song you entered.
- "movie-this" Movie
   - Will call the IMBD API and display the details of the movie you searched for.
- "do-what-it-says" n/a
   - No search filter accepted, just call liri.js with this command and it will read in a search term from the file "random.txt" and search Spotify for the term that was read into the file. Random.txt is structured as a comma delimited file so the search term is always idex 1 on the array created using the javascript "split()" function.

# Technology Used
* JavaScript
* Node.js
* Spotify API
* Bands in Town API
* OMDB API

