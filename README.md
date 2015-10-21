#Magic Playlist
// Get the playlist of your dreams based on a song

Start with a seed song, the algoritm will search top relational tracks and make a playlist.
Magic Playlist let you play 30 second of preview for each song. Edit the playlist and save in you profile.
Only using the Spotify API.

Type the name of your favourite song and see how the algoritm return you a playlist.

#Features
- Create an Awesome playlist based on a song
- Play audio preview (30 seconds)
- Save playlist in Spotify
- Share playlist

#Algorithm Overview
- Given a Track extract his `popularity`
- Get related Artists form a Track
- Get top tracks(max:20) from each related Artist
- Sort all Tracks from popularity(ASC)
- Alternate 1:1
- Select the batch(30) based in the first Track popularity
- Sort by popularity
- Alternate
- Enjoy the playlist

#Stack
- ES6
- Flux
- React
- Spotify-SDK

#Spotify API


Made with :heart: from Córdoba, Argentina.
