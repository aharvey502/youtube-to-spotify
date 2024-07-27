# Instantly transfer a YouTube music Playlist to a Spotify music playlist

## Description
A Python program to automate the transfer of a YouTube music playlist to a Spotify playlist. 

Typically, transferring music from YouTube to Spotify would require a user to find the song in their
YouTube playlist, copy the song title, paste the song title into Spotify, go through the search results, and add the correct song to a Spotify playlist. This process has to be repeated for each individual song in a playlist, which can be quite time consuming. This program eliminates this individual manual transfer by allowing users to automatically populate a Spotify playlist with however many songs from a YouTube playlist in one go.

## Instructions
### Getting Spotify Authentication token
1. You will first need to authenticate with the Spotify web API. To do this, you will need an access token. To get an access token, follow the instructions under “Getting Started” here: https://developer.spotify.com/documentation/web-api. Make sure to save this token.
### Downloading files
2. Download the files `run.py`, `spotify_client.py`, `youtube_client.py` and put them all in one directory.
### Adding the Spotify Authentication token
3. Open the terminal, and cd to the same directory with all the other project files.
4. In the terminal write `export SPOTIFY_AUTH_TOKEN=<PASTE AUTH TOKEN HERE>` (paste your spotify auth token after the `=`), and press enter.
### Running the program
5. In the terminal, run the `run.py` file by typing `python run.py` and press enter.
6. There should now be a URL in the terminal. Visit the URL to authorize your Google account for the YouTube data API. Sign in with the Google account, and click continue until you see an authorization code.
7. Once you see an authorization code, copy and paste it into your terminal where it prompts `Enter the authorization code:` and press enter.
8. A numbered list of your YouTube playlists should appear (Ex. `0 My Music`). Type the number of the playlist you would like to transfer songs from where prompted `Enter your choice:` and press enter. The program will output which songs it added to the Spotify playlist.
9. Open Spotify and your YouTube songs should now be added to your Spotify liked songs playlist!

