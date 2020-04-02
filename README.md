# Python-ETL-Spotify
This program uses the Pandas library to analyze the popularity of artists on Spotify's curated playlists.

In this program, the first notebook queries each of the hundreds of playlists that spotify curates and promotes via its eponymous user account. A database of these playlists is then saved as CSV file. Next, the second notebook obtains the follower counts for each of these playlists before creating another CSV database holding the one hundred most popular of these playlists when measured by follower count. Finally, the third notebook counts the number of times that each artist appears in these one hundred playlists before creating a third CSV database that ranks the most popular artists by number of appearances. The resulting databases provide insights into the popularity of music on one of the world’s most popular streaming platforms.

When this program was run on March 30th, 2020, the top five most popular spotify-curated playlists (and the top five most popular artists within the top one hundred playlists) were as follows:

  Most popular playlists: Today's Top Hits, Global Top 50, RapCaviar, ¡Viva Latino!, Songs to Sing in the Car

  Most Popular Artists: The Beatles, Drake, Justin Bieber, Coldplay, Ed Sheeran
