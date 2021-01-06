# Jammming

A React.js web application which utilises the Spotify developer API and enables uses to search for songs and create and save playlists which are available in their Spotify account. 

The four screenshots below visualise:
   1) The home screen;
   2) Searching for a song or artist, with the results appearing in the results component on the left;
   3) Populating the user's playlist by adding songs from the results component. The playlist name can also be edited in the component on the right before saving; and
   4) Viewing the created playlist using the Spotify desktop application. 

## Screenshots

### Home Screen

![](/screenshots/home%20screen.PNG?raw=true "Home Screen")

### Searching for a song or artist

![](/screenshots/search.PNG?raw=true "Searching for a song or artist")

### Creating a playlist

![](/screenshots/create%20playlist.PNG?raw=true "Creating a playlist")

### Accessing playlist in Spotify

![](/screenshots/spotify.PNG?raw=true "Viewing playlist in Spotify")

## Installation and Setup Instructions

Clone this repository. You will need `node` and `npm` installed globally on your machine.

Installation:

`npm install`

Creating your developer API:

Head to https://developer.spotify.com/dashboard/ and log in using your Spotify credentials. 

Click 'Create an App' and follow the on screen instructions.

When you have your Client ID, store it in the `clientId` variable found on line 3 in src -> util -> Spotify.js

To Start Server:

`npm start`

To Visit App:

`localhost:3000/`

## Enjoy!
