# MuseBot

This is a Facebook Messenger Chatbot that asks about the user's mood today in the morning, afternoon, and evening.
It implements sentiment analysis on the recorded responses through IBM Watson API, returning numerical scales of basic emotions such as joy, sadness, and anger.
Based on the results, the chatbot creates user-specific music playlists on Spotify. This is done through Spotify API that enables creating new playlists based on audio features such as liveliness, danceability, acousticness, loudness, speechiness, energy, and tempo.
We are still working on the Authorization to enable generating playlists without any token that expires after a certain time that would deny the user's access to the playlist.
Also, we are planning to make the Chatbot's responses more diverse rather than just automatic copy-and-paste versions of the user's input.
