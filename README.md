# Python-Spotify-Popular
This program uses the Pandas library to identify the artists whose music appears most frequently in Spotify's curated playlists.

Technologies Used: Python, Pandas, Jupyter Notebooks, Spotipy, Spotify API

This program consists of three [Jupyter](https://jupyter.org/) notebooks. The first notebook uses the [Spotipy Library](https://spotipy.readthedocs.io/en/2.16.0/) to query the [Spotify API](https://developer.spotify.com/documentation/web-api/reference/), thereby extracting information about each of the playlists that Spotify curates and promotes using its [eponymous user account](https://open.spotify.com/user/spotify). It then loads this information into a CSV file (all_playlists). Next, the second notebook extracts follower counts for all of these playlists, ranks the playlists by follower count, and loads a list of the most followed playlists into a second CSV file (top_100_playlists). Finally, the third notebook counts the number of times that each artist appears in the list of most followed playlists, ranks the artists accordingly, and loads a list of the top 100 artists into a third CSV file (top_100_artists). The resulting data provide insight into the state of popular music on one of the world's most popular music streaming platforms.

Listed below are the outputs from this program on August 30th, 2021.

The 5 most popular Spotify-curated playlists were as follows:
1. Today's Top Hits
2. Top 50 - Global
3. RapCaviar
4. ¡Viva Latino!
5. Songs to Sing in the Car

The 5 most popular artists within the 100 most popular Spotify-curated playlists were as follows:
1. Drake
2. Justin Bieber
3. The Beatles
4. The Weeknd
5. Kanye West
