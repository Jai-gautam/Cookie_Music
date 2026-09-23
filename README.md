🎵 Web Music Player & Artist Showcase
Welcome to my Web Music Player! I built this responsive, dark-themed music streaming web app entirely with vanilla JavaScript, HTML5, and CSS3. My goal was to create a smooth, interactive listening experience complete with dynamic track loading, custom audio controls, an interactive seek bar, animated wave visualizers, and sections dedicated to showcasing artists.

✨ Features
Dynamic Track Playlist: The app automatically pulls and populates song details like titles, artists, and album artwork straight from JavaScript data objects.

Playback Controls: You can easily play, pause, or skip forward and backward through tracks. It tracks the song's duration and shows live timestamps in a clean MM:SS format. There's also an interactive scrub/seek bar that fills up dynamically as the song plays.

Audio Wave Visualizer: I added a CSS-animated equalizer wave that syncs up with the active playback state to give the player a lively, energetic feel.

Artist & Track Discovery: Users can scroll horizontally to discover popular songs and featured artists. There are also dedicated banner displays and detailed views for individual artists.

Clean Dark UI: The design is sleek and modern, utilizing dark gradients, blurred backdrops, and Poppins typography for a polished look.

🛠️ Tech Stack
Markup: HTML5 Audio API for handling the underlying music playback.
Styling: Pure CSS3, making use of Flexbox, CSS Variables, and Keyframe Animations.
Icons: Bootstrap Icons (bi-*) to keep the interface looking sharp.
Scripting: Vanilla JavaScript (ES6+) for all the core logic, state management, and event handling.

📁 Project Structure
Plaintext
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
