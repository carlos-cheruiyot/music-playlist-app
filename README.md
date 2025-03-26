# Music Playlist App

# Author: Carlos Cheruiyot

## Description

The **Music Playlist App** is a simple web application that allows users to browse a collection of songs, like individual songs, and search through the song list. The app fetches song data from a local API (using **json-server**) and dynamically displays the song list with options to like songs. Users can search for songs by title or artist and interact with the song list without reloading the page. It’s a lightweight project designed to practice asynchronous data fetching, DOM manipulation, and simple interactivity with JavaScript.

## Features

- **Song Display**: View a list of songs with their title, artist, genre, and album art.
- **Like Button**: Users can click a "like" button to increment a song’s like count.
- **Search Functionality**: Search songs by title or artist.
- **Single Page Application**: No page reloads, all actions happen seamlessly on the same page.

## Project Setup Instructions

### Prerequisites
Before running the app, make sure you have the following installed:

- **Node.js** (which includes npm)
- **json-server** (for creating the mock API)
  
### 1. Clone the Repository
First, clone the project repository to your local machine:

```bash
git clone https://github.com/carloscheruiyot/music-playlist-app.git
cd music-playlist-app
