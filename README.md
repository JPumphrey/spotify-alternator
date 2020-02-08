# Spotify Alternator

The other day, I graduated from listening to a song on repeat to listening to the artists best-of playlist. However, I found myself repeatedly queueing up my favourite song.

I wondered, could that be automated? Could Spotify alternate between playing my current favourite, and playing from a playlist?

The answer is, kind of. Here's an implementation that creates a copy of the playlist with the song inserted at every second position.

## Instructions

You will need to get your own auth token with the scopes `playlist-read-private`and `playlist-modify-private`. The variable `token` should point to it.