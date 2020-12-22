# SpotifyRecommendation

## Purpose:
The vision of this app is to generate recommendations from Spotify for a user. Given a user's listening habits this app maps a listener's top genres and provides notifications on a recurring basis when new music is released that matches their listening habits.
Spotify describes music with several features: acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, valence, and tempo.
Given a users top songs we would see if any of these traits are significantly grouped and generate recommendations in the future based off those.
[Spotify Documentation for Audio Features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)

![Music Genre Breakdown](https://images.squarespace-cdn.com/content/v1/54b81352e4b09cb81d7d881f/1480795224008-3NJK7B5SGEK4QGP7DOGS/ke17ZwdGBToddI8pDm48kKFUTfJKiWntuLkQ6FHrTmRZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PI1g7eh4SYGT9nmgi0A8JEYxjJCx5bk948F0jYJ7L5nG4KMshLAGzx4R3EDFOm1kBS/image-asset.jpeg?format=750w)

## Functionality:
- [ ] Login user
- [ ] Fetch top songs / artists
- [ ] Analyze favourite songs and most listened to songs of top artists to find commoon musical characteristics
- Loop
  - [ ] Check new songs on spotify
  - [ ] Search through users for strong matches
  - [ ] Recommend songs to users

## Next Steps:
- Serverless Architecture
> The design lends itself well to a serverless design as the main program is a recurring search on spotify for new music recommendations.
- React client integration
> React seems a strong choice for designing the frontend
- Machine Learning for recommendations
> Another obvious next step would be to implement a similar algorithm with machine learning
