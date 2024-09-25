# Spotify Artist Explorer

This project is a web application built using Flask, which allows users to search
for their favorite artists on Spotify. The app retrieves artist information, popular songs, albums, related artists, 
and playlists using the Spotify API. Additionally, it integrates with the Genius API to fetch song lyrics.

## Features

- **Artist Search**: Users can search for an artist by name.
- ![image](https://github.com/user-attachments/assets/26e65343-fc91-4a84-b2a0-76acd996223d)

- **Artist Information**: Displays artist details such as name, genres, follower count, and images.
- **Popular Songs**: Lists the top 5 popular tracks by the artist.
- **Popular Albums**: Displays up to 3 popular albums by the artist.
- **Related Artists**: Provides recommendations for related artists.
- **Playlists**: Shows playlists associated with the artist.
- **Lyrics**: Fetches lyrics for the artist's songs using the Genius API.
- **Spotify Embed**: Embedded Spotify player for songs, albums, and playlists.

## Tech Stack

- **Flask**: Python web framework for the backend.
- **Spotify API**: Used for retrieving artist information, songs, albums, related artists, and playlists.
- **Genius API**: For fetching song lyrics.
- **Jinja2**: Templating engine for rendering HTML.
- **HTML/CSS/JavaScript**: Frontend components for the web interface.
- **dotenv**: For managing environment variables.

## Requirements

- Python 3.x
- Spotify Developer Account (to create an API key)
- Genius API key (for lyrics)
- Flask and required Python packages

## Setup Instructions

1. **Clone the repository:**
- Download the project
- You will have to find the CLIENT_ID, CLIENT_SECRET, and REDIRECT_URI through the setting in spotify and spotifyfordevelopers.com
- CLIENT_ID=your_spotify_client_id
- CLIENT_SECRET=your_spotify_client_secret
- REDIRECT_URI=http://localhost:8888/callback
