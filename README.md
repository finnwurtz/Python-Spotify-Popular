# Python-Spotify-Popular
This program uses the Pandas library to identify the artists whose music dominates Spotify's curated playlists.

Technologies Used: Python, Pandas, Jupyter Notebooks, Spotipy, Spotify API

This program consists of three Jupyter notebooks. The first notebook uses the [Spotipy Library](https://spotipy.readthedocs.io/en/2.16.0/) to query the [Spotify API](https://developer.spotify.com/documentation/web-api/reference/) so that it can extract information about the hundreds of playlists that Spotify curates and promotes via its eponymous user account. This notebook then loads this information into a CSV database (all_playlists). Next, the second notebook extracts follower counts for each of these playlists, ranks the playlists by follower count, and loads a list of the most followed playlists into a second CSV database (top_100_playlists). Finally, the third notebook counts the number of times that each artist appears in the list of most followed playlists, ranks the artists accordingly, and loads a list of the top 100 artists into a third CSV database (top_100_artists). The resulting data sheds light on the state of popular music on one of the world's most widely used music streaming platforms.

Listed below are the outputs from this program on October 12th, 2020.

The 5 most popular Spotify-curated playlists were as follows:
1. Today's Top Hits
2. RapCaviar
3. Hot Country
4. ¡Viva Latino!
5. New Music Friday

The 5 most popular artists within the 100 most popular Spotify-curated playlists were as follows:
1. Drake
2. The Beatles
3. The Weeknd
4. Justin Bieber
5. Coldplay
