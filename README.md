# liri-node-app

LIRI Bot

About
LIRI is a Language Interpretation and Recognition Interface. LIRI takes in command line paramete and gives back data.

What it does
Spotify
node liri.js spotify-this-song <insert song title>

After entering a selected song, the command line will show:

Artist(s)
  * The song's name
  * A preview link of the song from Spotify
  * The album that the song is from
  * If no song is provided then your program will default to "The Sign" by Ace of Base

Movies
node liri.js movie-this <insert movie title>

After entering a selected movie, the command line will show:

   * Title of the movie.
   * Year the movie came out.
   * IMDB Rating of the movie.
   * Rotten Tomatoes Rating of the movie.
   * Country where the movie was produced.
   * Language of the movie.
   * Plot of the movie.
   * Actors in the movie.

If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

Bands In Town
node liri.js concert-this <artist/band name here>

After entering a selected band, the command line will show:

  * Name of the venue
  * Venue location
  * Date of the Event (use moment to format this as "MM/DD/YYYY")

Do What It Says
node liri.js do-what-it-says

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

It will run spotify-this-song for "I Want it That Way,".

