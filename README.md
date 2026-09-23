# 🎵 Web Music Player & Artist Showcase

A sleek, responsive, dark-themed music streaming web application built with vanilla JavaScript, HTML5, and CSS3. It includes dynamic track loading, custom audio controls, an interactive seek bar, animated wave visualizers, and artist profile sections[cite: 5, 6].

---

## ✨ Features

- **Dynamic Track Playlist**: Automatically populates song metadata (titles, artists, album posters) from JavaScript data objects.
- **Playback Controls**:
  - Play, Pause, Next, and Previous track controls.
  - Track duration and live timestamp formatting (`MM:SS`)[cite: 5].
  - Interactive scrub/seek bar with dynamic progress fill[cite: 5, 6].
- **Audio Wave Visualizer**: CSS-animated equalizer wave that synchronizes with the active playback state[cite: 5, 6].
- **Artist & Track Discovery**:
  - Horizontal scrollable sections for popular songs and featured artists[cite: 5, 6].
  - Dedicated artist detail views and banner display.
- **Clean Dark UI**: Styled using modern gradients, blur backdrops, and Poppins typography[cite: 6].

---

## 🛠️ Tech Stack

- **Markup**: HTML5 Audio API[cite: 5]
- **Styling**: CSS3 (Flexbox, CSS Variables, Keyframe Animations)[cite: 6]
- **Icons**: Bootstrap Icons (`bi-*`)[cite: 5, 6]
- **Scripting**: Vanilla JavaScript (ES6+)[cite: 5]

---

## 📁 Project Structure

```text
├── audio/                   # Audio files (.mp3)
├── img/                     # Song posters & artist thumbnails (.jpg, .jpeg)
│   ├── 00s.jpeg
│   ├── akhil.jpg
│   ├── alan.jpg
│   ├── arjit.jpg
│   ├── atif.jpg
│   └── dafa.jpg
├── artiststyle.css          # Core application styling & animations
├── artistscript.js          # Player logic, playlist state & event listeners
├── index.html               # Main player markup
└── README.md
