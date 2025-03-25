🎶 Spotify Clone - Your Personal Music Hub 🎶
Welcome to the Spotify Clone! This sleek, Spotify-inspired web app lets you browse your favorite tracks, explore song details, and control playback — all wrapped in a beautiful, user-friendly interface. Built with React and Context API, this app brings the ultimate music experience right to your browser.

🛠️ Tech Stack
Frontend: React, Tailwind CSS

State Management: Context API

Icons & Assets: Local assets (stored in src/assets)

📂 Project Structure
🔊 SongItem.js
This component displays individual songs, complete with cover images, titles, and descriptions.

Props:

name: Song title

image: Cover image URL

desc: Short song description

id: Unique song ID

When you click a song, it triggers the playback function to start the music.

🎵 Player.js
The heart of the app — the music player!

Displays current track info (image, name, description)

Play/Pause, Next/Previous track navigation

Shuffle, Loop, and Volume controls

Seek bar to track song progress

Shows current and total track time

🎛️ Context API
Manage state for the music player with ease:

track: Current track details (image, name, description)

playStatus: Whether the song is playing or paused

play(), pause(), next(), previous(): Control functions for playback

time: Current and total track time

seekBar and seekBg: Refs for the seek bar

🚀 How to Get Started
Clone the repository
git clone https://github.com/your-repo/spotify-clone.git

Navigate to the project folder
cd spotify-clone

Install dependencies
npm install

Run the app
npm run dev

Now, you're ready to rock and roll with your own Spotify-inspired app! 🎧

