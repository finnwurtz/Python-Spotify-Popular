# Python-Spotify-Popular
This program uses the Pandas library to identify the artists whose music appears most often in Spotify's editorial playlists.

Technologies Used: Python, Pandas, Jupyter Notebooks, Spotipy, Spotify API

This program includes three [Jupyter](https://jupyter.org/) notebooks. The [first notebook](https://github.com/finnwurtz/Python-Spotify-Popular/blob/master/Playlist_Finder.ipynb) uses the [Spotipy Library](https://spotipy.readthedocs.io/en/2.16.0/) to query the [Spotify API](https://developer.spotify.com/documentation/web-api/reference/), thereby extracting information about each of the [1500+ playlists](https://open.spotify.com/user/spotify/playlists) that Spotify curates and promotes with its [eponymous user account](https://open.spotify.com/user/spotify). It then loads this information into a CSV (comma-separated values) file ('all_playlists'). Next, the [second notebook](https://github.com/finnwurtz/Python-Spotify-Popular/blob/master/Playlist_Merge.ipynb) extracts follower counts for all of these playlists, ranks the playlists by follower count, and loads a list of the most followed playlists into a second CSV file ('top_100_playlists'). Finally, the [third notebook](https://github.com/finnwurtz/Python-Spotify-Popular/blob/master/Artist_Finder.ipynb) counts the number of tracks in the 100 most followed playlists that each of the artists in those playlists appears on, ranks those artists accordingly, and loads a list of the top 100 of those artists into a third CSV file ('top_100_artists'). The resulting sets of data provide a glimpse into the state of popular music on one of the world's largest music streaming platforms.

Listed below are outputs from this program on August 30th, 2021.

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
