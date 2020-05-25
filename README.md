# spotifynd

UI for the Spotify [recommendations API](https://developer.spotify.com/documentation/web-api/reference/browse/get-recommendations/). User provides seed artists and tweaks track attribute values for acousticness, danceability, energy, instrumentalness, liveness, and valence, and gets a list of recommended tracks. Tracks that support preview URLs can be previewed immediately.

### Building & Running
`npm install`

`npm start`

App is yet to support Spotify login, so you need to manually generate a key and add it to `/api/spotify.js`.

### Screenshot
![spotifynd](https://i.imgur.com/k56L5k6.png)