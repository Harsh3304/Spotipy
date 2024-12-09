# SPOTIPY: The Perfect Music Player 🎵

## 📝 Overview

A feature-rich music player built with Python and MySQL, this application provides a user-friendly interface that supports local MP3 playback and YouTube music integration. Search any song and Spotipy has makes it available for you.

## ✨ Features

- 🎵 Play local MP3 files
- 🎬 Download and play YouTube music
- 🔍 YouTube music search functionality
- 📱 Windows 10 notifications
- 📊 MySQL database integration for playlist management
- 🎨 Modern GUI with Tkinter
- ⏯️ Basic media controls (play, pause, next, previous)
- 🕒 Real-time progress bar and duration display
- 📂 File browser for local music selection

## Prerequisites

Make sure you have Python 3.7/3.11 installed and the following dependencies:

```bash
pip install pygame mutagen beautifulsoup4 pydub pillow yt-dlp tk youtube-search-python win10toast pywin32 requests pythumb mysql-connector-python
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Harsh3304/Spotipy.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up MySQL database:
   - Create a new database
   - Configure the database connection in the application
   - Run the included SQL schema (if provided)

## Usage

Run the application:
```bash
python Spotipy.py
```

## 🖼️ Screenshots

1. **Home page (For new User)**
    ![alt text](/Dependencies/readme_images/new_user_screen.png)

2. **Home page (With Music Entries)**
    ![alt text](/Dependencies/readme_images/screen_with_songs_screen.png")

3. **Home page (With Music Entries - Dark Mode)**
    ![alt text](/Dependencies/readme_images/screen_with_songs_screen_dark.png")


### Features Guide:

1. **Local Music Playback**
   - Click "Browse" to select local MP3 files
   - Use media controls to play/pause/skip tracks

2. **YouTube Integration**
   - Search for songs directly in the application
   - Download and play YouTube music
   - Automatically saves thumbnail and metadata

3. **Playlist Management**
   - Create and manage playlists
   - Save favorite tracks
   - Queue management

## Project Structure

```
music-player/
├── main.py
├── requirements.txt
├── assets/
│   ├── icons/
│   └── images/
├── downloads/
│   ├── music/
│   └── thumbnails/
└── database/
    └── schema.sql
```

## Libraries Used

- `tkinter`: GUI framework
- `pygame.mixer`: Audio playback
- `mutagen`: Audio metadata handling
- `yt-dlp`: YouTube download functionality
- `pydub`: Audio processing
- `mysql.connector`: Database connectivity
- `win10toast`: Windows notifications
- `beautifulsoup4`: Web scraping
- `pillow`: Image processing
- `youtube-search-python`: YouTube search functionality

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📞 Contact

Your Name - harshp3304@gmail.com

Project Link: [https://github.com/Harsh3304/Spotipy.git](https://github.com/Harsh3304/Spotipy.git)