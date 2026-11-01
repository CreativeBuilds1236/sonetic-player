<p align="center">
  <img src="docs/images/logo.png" alt="Sonetic logo" width="120" />
</p>

<h1 align="center">Sonetic</h1>

<p align="center">
  <b>A free, ad-free, offline-first music player for Android.</b><br/>
  No ads. No account. No tracking. Just your music.
</p>

<p align="center">
  <a href="https://github.com/CreativeBuilds1236/sonetic/releases/latest"><img src="https://img.shields.io/github/v/release/CreativeBuilds1236/sonetic?style=for-the-badge&color=D2A679&label=Download" alt="Latest release" /></a>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-17110E?style=for-the-badge" alt="GPL-3.0 license" /></a>
</p>

<p align="center">
  <img src="docs/images/banner.png" alt="Sonetic screenshots" width="100%" />
</p>

---

## Why Sonetic?

Most music players today want your account, your data, or your attention for ads. Sonetic wants none of that. It plays the music on your phone, works fully offline, and stays out of your way. It is open source, so anyone can check the code, learn from it, or improve it.

---

## Screenshots

<table>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/d60d1a2d-9313-4770-a712-eb9fd8a6f979" width="300" alt="Home screen" /><br/><sub>
      <b>Now Playing</b></sub></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/42d72f6f-e8d5-4259-aec5-5d2934cd8170" width="300" alt="Now Playing screen" /><br/><sub><b>Home</b></sub></td>
    <td align="center"><img src="docs/images/library.png" width="220" /><br/><sub><b>Library</b></sub></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/images/audio-lab.png" width="220" /><br/><sub><b>Audio Lab</b></sub></td>
    <td align="center"><img src="docs/images/search.png" width="220" /><br/><sub><b>YouTube Music Search</b></sub></td>
    <td align="center"><img src="docs/images/themes.png" width="220" /><br/><sub><b>Themes</b></sub></td>
  </tr>
</table>

---

## Features

### 🎵 Playback
- Plays the music stored on your phone, with no internet needed
- Queue with an "Up next" view, shuffle and repeat
- Shuffle shows the real play order, and the song you tap always plays first
- Your queue, shuffle and repeat settings are remembered after you close the app
- Notification and lock-screen controls
- Built on Media3 / ExoPlayer for smooth, reliable playback

### 📚 Library
- Playlists, Liked songs, Downloaded, and On this device
- Browse by albums and artists
- Drag to reorder your playlists and songs
- Choose your own music folders in Settings

### 🎚️ Audio Lab
- 10-band graphic equalizer
- Parametric EQ for fine control
- Preamp with auto-headroom, so boosting the EQ doesn't distort
- Soft limiter to prevent clipping
- ReplayGain for even volume across songs
- Playback speed control
- Import AutoEq headphone profiles
- Remembers a separate EQ preset for each output device (speaker, wired headphones, Bluetooth)

### 🔎 YouTube Music
- Search for songs and play them instantly
- Download songs as MP3 (CBR or VBR, choose your bitrate) or FLAC
- Cover art, artist and album tags embedded automatically
- Custom filename patterns
- Update yt-dlp from inside the app

### 🎨 Appearance
- Seven themes: **Espresso**, **Latte**, **Midnight**, **Moss**, **Dusk Rose**, **Mono** and **Custom**
- Custom colour picker for background, text and accent, with a readability check
- Clean design with a floating navigation bar

### 🔒 Privacy
- No ads, ever
- No account or sign-in needed
- No tracking or analytics
- Internet is only used for YouTube search, downloads and yt-dlp updates. Local playback never touches the network.

### 🎧 Coming soon: Listen Together
Listen to the same song, in sync, with up to 8 friends. Each phone streams the song itself, and Sonetic keeps everyone in time. Join with a simple room code.

---

## Download

1. Go to the [**Releases**](https://github.com/CreativeBuilds1236/sonetic/releases/latest) page.
2. Download the latest `.apk` file.
3. Open it on your phone. If asked, allow installing apps from this source.
4. Done! Open Sonetic and give it permission to read your music.

> Sonetic is not on the Google Play Store. GitHub Releases is the only official place to get it.

---

## Build it yourself

**You need:**
- [Android Studio](https://developer.android.com/studio) (latest stable version)
- An Android phone or emulator

**Steps:**

```bash
git clone https://github.com/CreativeBuilds1236/sonetic.git
cd sonetic
./gradlew assembleDebug
```

Or just open the project folder in Android Studio and press **Run ▶**.

---

## Built with

| Part | Technology |
|------|------------|
| Language | Kotlin |
| UI | Jetpack Compose |
| Playback | Media3 / ExoPlayer |
| YouTube | yt-dlp (via youtubedl-android) |
| Listen Together | Firebase |

---

## Roadmap

- [x] Local playback, queue, shuffle and repeat
- [x] Themes and custom colours
- [x] Library with playlists, albums and artists
- [x] Audio Lab (EQ, preamp, limiter, ReplayGain, speed, AutoEq)
- [x] YouTube Music search, streaming and downloads
- [x] Grouped settings pages
- [ ] Listen Together
- [ ] Hi-res / bit-perfect playback mode

---

## Important note

Sonetic includes [yt-dlp](https://github.com/yt-dlp/yt-dlp) for YouTube search and downloads. You are responsible for following YouTube's Terms of Service and the copyright laws where you live. Sonetic does not bypass DRM and does not work around age-restricted, members-only or private videos.

---

## Contributing

Ideas, bug reports and pull requests are welcome!

- Found a bug? [Open an issue](https://github.com/CreativeBuilds1236/sonetic/issues)
- Have an idea? Start a discussion or open an issue with the `enhancement` label
- Want to help with code? Fork the repo, make your change, and open a pull request

---

## License

Sonetic is free software, released under the **GNU General Public License v3.0 or later**. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ☕ by <a href="https://github.com/CreativeBuilds1236">Rajesh Divakaran</a><br/>
  If you like Sonetic, give it a ⭐ on GitHub!
</p>
