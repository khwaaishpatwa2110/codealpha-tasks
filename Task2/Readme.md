# 🎵 ARIRANG — BTS Music Player

A sleek, responsive web-based music player built with pure HTML, CSS, and JavaScript. Designed around the *ARIRANG* album by BTS, it features a Spotify-inspired layout that adapts beautifully between mobile and desktop.

---

## ✨ Features

- **Responsive Layout** — Stacks vertically on mobile; switches to a side-by-side Spotify-style layout on desktop (768px+)
- **Spinning Vinyl Cover Art** — Album art rotates like a vinyl record while a track is playing
- **Full Playback Controls** — Play/Pause, Previous, Next, Shuffle, and Loop
- **Interactive Progress Bar** — Click or drag to seek through the track; displays current time and total duration
- **Volume Slider** — Smooth volume control with a dynamic red fill
- **Clickable Playlist** — Full tracklist panel with track number, cover art, title, artist, duration, and an active-track indicator
- **Explicit Content Badge** — Tracks marked as explicit display an `E` badge
- **Error Handling** — Gracefully notifies when an audio file is missing or unavailable

---

## 📁 Project Structure

```
/
├── index.html                # Main application (single file)
├── arirang_album_cover.jpg   # Album cover image
├── Body to Body.mp3
├── Hooligan.mp3
├── Aliens.mp3
├── FYA.mp3
├── 2.0.mp3
├── No. 29.mp3
├── Swim.mp3
├── Merry Go Round.mp3
├── NORMAL.mp3
├── Like Animals.mp3
├── they don't know 'bout us.mp3
├── One More Night.mp3
├── Please.mp3
└── Into the Sun.mp3
```


---

## 🛠️ Built With

- **HTML5** — Structure and native `<audio>` API
- **CSS3** — Custom styling, animations, media queries, and responsive layout
- **Vanilla JavaScript** — All playback logic, playlist rendering, and UI state management
- **[Font Awesome 6](https://fontawesome.com/)** — Icons (loaded via CDN)

---

## 🎨 Design Highlights

- Dark theme with a `#121212` background and `#dc2626` (red) accent color
- Smooth CSS `spin` animation on the cover art while playing
- Dynamic gradient fill on range sliders (progress & volume) that tracks the thumb position in real time
- Custom scrollbar styling for the playlist panel

---

## 📋 Tracklist

| # | Title | Duration |
|---|-------|----------|
| 1 | Body to Body | 3:09 |
| 2 | Hooligan | 3:02 |
| 3 | Aliens | 2:47 |
| 4 | FYA | 3:00 |
| 5 | 2.0 | 2:49 |
| 6 | No. 29 | 1:38 |
| 7 | SWIM | 2:39 |
| 8 | Merry Go Round | 3:49 |
| 9 | NORMAL `E` | 3:01 |
| 10 | Like Animals | 3:09 |
| 11 | they don't know 'bout us | 2:44 |
| 12 | One More Night | 2:47 |
| 13 | Please | 2:52 |
| 14 | Into the Sun | 3:47 |

---

## 📄 License

This project is for personal/educational use. All music and album artwork are the property of their respective copyright holders (HYBE / BTS). This player does not distribute or host any audio files.
