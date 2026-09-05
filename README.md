# AudPlay Pro

A sleek, feature-rich web audio player with advanced playback controls, built entirely in vanilla HTML/CSS/JavaScript.

## Features

### 🎵 Core Playback
- **Play/Pause Control** – Seamless audio playback with intuitive controls
- **Progress Slider** – Seek to any point in the track with visual feedback
- **Time Display** – Real-time duration and current position tracking
- **Multiple Format Support** – MP3, WAV, OGG, M4A, AAC, FLAC, WebM, MP4, Opus, WMA

### ⚡ Playback Control
- **Speed Control** – Adjust playback speed from 0.5× to 2.0× without affecting pitch (or together)
- **Pitch Control** – Modify voice tone from deep to squeaky (0.5× to 2.0×)
- **Smart Pitch Preservation** – Automatically preserves original pitch when only changing speed
- **Loop Modes** – Toggle between no loop, loop all, and loop one
- **Shuffle** – Randomize playlist playback order
- **Surround Sound** – Enhanced audio spatializing (Web Audio API)
- **Previous/Next Navigation** – Skip tracks or rewind 10 seconds

### 📂 Playlist & Loading
- **Single Track Loading** – Paste any audio URL to load
- **GitHub Folder Support** – Load all audio files from a GitHub repository folder
- **URL Expansion** – Automatically expands short URLs (is.gd, bit.ly, tinyurl.com, etc.)
- **Playlist Management** – View and navigate through multiple tracks
- **Saved Playlists** – Store and load your favorite playlists via browser localStorage
- **Share Links** – Generate shareable URLs with ?url= parameters

### 🎨 User Experience
- **Animated Visualizer** – 12-bar equalizer that responds to playback state
- **Glass Morphism UI** – Modern frosted glass design with purple/neon accents
- **Status Indicator** – Visual dot showing playback state
- **Dark Theme** – Eye-friendly high-contrast interface
- **Responsive Design** – Works on desktop and mobile devices
- **Error Handling** – Clear error messages for network and format issues
- **Media Session API** – Integrates with device media controls

## Getting Started

### Online Usage
Visit the hosted version: [AudPlay Pro](https://3ekodomo.github.io/audplay/)

### Loading Audio

#### Option 1: Paste a Direct URL
1. Click the URL input field
2. Paste your audio URL (e.g., `https://example.com/song.mp3`)
3. Click **Load** or press Enter

#### Option 2: Share a Pre-loaded URL
Add `?url=` parameter to the URL:
