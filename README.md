# Python-Spotify-Popular
This program uses the Pandas library to analyze the popularity of artists on Spotify's curated playlists.

Technologies Used: Python, Pandas, Jupyter Notebooks, Spotify API

In this program, the first notebook queries the [Spotify](https://developer.spotify.com/documentation/web-api/reference/) API to extract information about the hundreds of playlists that Spotify curates and promotes via its eponymous user account. The notebook then loads this information into a CSV database. Next, the second notebook extracts follower counts for each of these playlists, ranks the playlists by popularity, and loads a list of the most popular playlists into a second CSV database (top_100_playlists). Finally, the third notebook counts the number of times that each artist appears in the list of most popular playlists, ranks the artists accordingly, and loads a list of the most popular artists into a third CSV database (top_100_artists). The resulting databases provide insight into the current state of popular music on one of the world's most popular music streaming platforms.

When this program was run on March 30th, 2020, the five most popular spotify-curated playlists (and the five most popular artists within the top one hundred playlists) were as follows:

  Most popular playlists: Today's Top Hits, Global Top 50, RapCaviar, ¡Viva Latino!, Songs to Sing in the Car

  Most Popular Artists: The Beatles, Drake, Justin Bieber, Coldplay, Ed Sheeran
