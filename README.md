# Spotify API top tracks analysis

With Last.fm we get to know what are our top listened artists and songs in Spotify

![Tracking_last_fm](lastfm.png)

Guessing is less funnier than looking through the real data. This are my top artist in Spotify:

![My Spotify Top artist](top_tracks.png)

Audio features analysis from my weekly top tracks from Spotify.

From the whole amount of audio features, I will analyze and compare between my Top most listened, only 2 of them:

```
danceability.append(audio_features['danceability'])
energy.append(audio_features['energy'])
key.append(audio_features['key'])
loudness.append(audio_features['loudness'])
mode.append(audio_features['mode'])
speechiness.append(audio_features['speechiness'])
acousticness.append(audio_features['acousticness'])
instrumentalness.append(audio_features['instrumentalness'])
liveness.append(audio_features['liveness'])
valence.append(audio_features['valence'])
tempo.append(audio_features['tempo'])
duration_ms.append(audio_features['duration_ms'])
```

Chart visualization of the Top 6 tracks danceability and liveness including La MODA, Harry Styles and Jarabe de Palo

![Danceability and Liveness Top 6](danceability_chart.png)
