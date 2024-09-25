# Spotify Artist Explorer

This project is a web application built using Flask, which allows users to search
for their favorite artists on Spotify. The app retrieves artist information, popular songs, albums, related artists, 
and playlists using the Spotify API. Additionally, it integrates with the Genius API to fetch song lyrics.

## Features

- **Artist Search**: Users can search for an artist by name.
 ![image](https://github.com/user-attachments/assets/26e65343-fc91-4a84-b2a0-76acd996223d)
- **Artist Information**: Displays artist details such as name, genres, follower count, and images.
![image](https://github.com/user-attachments/assets/3bb2922e-8320-476e-a0c4-6dbf446710ac)
- **Popular Songs**: Lists the top 5 popular tracks by the artist.
![image](https://github.com/user-attachments/assets/84468333-395e-49dd-80b2-402c0daa264f)
- **Popular Albums**: Displays up to 3 popular albums by the artist.
![image](https://github.com/user-attachments/assets/2926f753-7cca-4c9d-b44c-c397e394a32a)
- **Related Artists**: Provides recommendations for related artists.
![image](https://github.com/user-attachments/assets/0845d903-393f-4262-98c5-0149bcde99b2)
- **Playlists**: Shows playlists associated with the artist.
![image](https://github.com/user-attachments/assets/72786e4c-74a4-401f-bde1-43335de1c4cf)
- **Lyrics**: Fetches lyrics for the artist's songs using the Genius API.
- **Spotify Embed**: Embedded Spotify player for songs, albums, and playlists.
![image](https://github.com/user-attachments/assets/cf1cc6a0-f285-4b18-95e5-ed54a5bdcbc2)

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
