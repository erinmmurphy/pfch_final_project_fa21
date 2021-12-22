
PROJECT TITLE
Charting Mood Over the Pandemic Using Spotify Listening Trends

PROJECT DESCRIPTION
This project looks at Spotify listening trends as an indicator of mood over the pandemic so far (March 2020 - December 2021) using the Spotify Web API and the Spotipy Python library.

Spotify provides audio features data for tracks through their web API. Audio features are measurements of various musical qualities within a track including: danceability, valence, energy, tempo, loudness, and instrumentalness. This project will look at the valence of the top tracks of 2020 and 2021. 

Valence is defined by Spotify as "a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)."

PROCESS
I set up a Spotify developer account, registered an app, then generated the access keys needed to make requests to the web API in Python. To access the audio feature data for top tracks, I used the Spotipy Python library to request 2 playlists (top tracks of 2020 and 2021) created by Spotify (based on number of streams) using the playlist IDs. Then I was able to generate audio features data for each track on the playlists, which I saved to CSV to visualize in Tableau.