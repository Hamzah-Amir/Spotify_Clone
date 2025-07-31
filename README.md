# Spotify Clone - Web Music Player

A responsive and interactive web-based music player inspired by Spotify's UI. Built using HTML, CSS, and JavaScript, this clone allows you to browse albums, play/pause tracks, view seekbars, and control volume.

> **Note:** This project is part of my learning journey in the **Sigma Web Development Course by [CodeWithHarry](https://www.codewithharry.com/)**.

## 📂 Folder Structure

```
spotify_clone/
├── assets/            # All static media assets (icons, covers, etc.)
│   ├── hamburger.svg
│   ├── logo.svg
│   ├── play.svg
│   ├── pause.svg
│   ├── prevsong.svg
│   ├── nextsong.svg
│   ├── music.svg
│   ├── volume.svg
│   ├── mute.svg
│   └── cross.svg
├── css/               # Stylesheets
│   ├── style.css
│   ├── utility.css
│   └── media.css
├── js/                # JavaScript code
│   └── script.js
├── songs/             # Songs & metadata folders (e.g. /cs)
│   └── [album-folder]/
│       ├── track1.mp3
│       ├── track2.mp3
│       ├── cover.jpg
│       └── info.json
├── favicon.ico
└── index.html
```

## 🚀 Features

* Responsive design with media queries
* Hamburger menu on smaller screens
* Sidebar navigation for song library
* Fetch and display albums from `/songs/`
* Play, pause, next, and previous song controls
* Seekbar to navigate through the song
* Volume control and mute/unmute toggle
* Scrollable playlist view

## 🙂 Getting Started

1. Clone this repository:

```bash
git clone https://github.com/your-username/spotify_clone.git
cd spotify_clone
```

2. Make sure you have a local server (e.g. VS Code Live Server, Python's HTTP server)

```bash
# Python 3
python -m http.server
```

3. Open your browser and navigate to:

```
http://127.0.0.1:8000/
```

## 🎵 Adding Your Own Songs

1. Create a folder inside `songs/` (e.g. `songs/pop/`)
2. Add your `.mp3` files and a `cover.jpg`
3. Create a `info.json` file like:

```json
{
  "title": "Pop Hits",
  "description": "Best of pop music."
}
```

## ✅ To Do / Improvements

* Add shuffle and repeat features
* Improve mobile responsiveness further
* Integrate with backend for dynamic song uploads
* Add user authentication (login/signup functionality)

## 💎 Credits

This project is built for educational purposes. All icons and assets used are either self-created or under permissive licenses.

Special thanks to **CodeWithHarry** for the amazing **Sigma Web Development Course** that inspired and guided this project.

---

Feel free to fork or use it as a base for your music app!

**Made with ♥ by Hamza Amir**
