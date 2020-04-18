# Python-Spotify-Popular
This program uses the Pandas library to analyze the popularity of artists on Spotify's curated playlists.

Technologies Used: Python, Pandas, Jupyter Notebooks, Spotify API

In this program, the first notebook queries the [Spotify](https://developer.spotify.com/documentation/web-api/reference/) API to extract each of the hundreds of playlists that Spotify curates and promotes via its eponymous user account. A database of these playlists is then loaded into a CSV file. Next, the second notebook extracts follower counts for each of these playlists before loading them into another CSV database (top_100_playlists), which ranks the one hundred most popular of these playlists by follower count. Finally, the third notebook counts the number of times that each artist appears in the one hundred most popular playlists, then loads the artists into a third CSV database (top_100_artists) that ranks them accordingly. The resulting databases provide insights into the popularity of music on one of the world’s most popular streaming platforms.

When this program was run on March 30th, 2020, the top five most popular spotify-curated playlists (and the top five most popular artists within the top one hundred playlists) were as follows:

  Most popular playlists: Today's Top Hits, Global Top 50, RapCaviar, ¡Viva Latino!, Songs to Sing in the Car

  Most Popular Artists: The Beatles, Drake, Justin Bieber, Coldplay, Ed Sheeran
