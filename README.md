<p align="center">
  <img src="assets/icon.png" alt="Animarvle App Icon" width="112" />
</p>

<h1 align="center">Animarvle</h1>

<p align="center">
  A high-performance Android streaming client for Anime, Movies, and TV series with an obsidian OLED black interface. Built with native Kotlin, AndroidX Media3 / ExoPlayer, and Google Drive cloud sync.
</p>

<p align="center">
  <a href="https://github.com/nd7hdyt/AniMarvle/releases/latest"><strong>Download APK</strong></a>
</p>

<p align="center">
  <a href="https://github.com/nd7hdyt/AniMarvle/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/nd7hdyt/AniMarvle?style=for-the-badge&logo=github&label=latest&color=00D4B2"></a>
  <a href="https://github.com/nd7hdyt/AniMarvle/releases"><img alt="Total downloads" src="https://img.shields.io/github/downloads/nd7hdyt/AniMarvle/total?style=for-the-badge&logo=github&label=downloads&color=107C41"></a>
  <a href="LICENSE"><img alt="GPLv3 license" src="https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge"></a>
</p>

<p align="center">
  <a href="https://developer.android.com/"><img alt="Android 8.0+" src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white"></a>
  <a href="https://kotlinlang.org/"><img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-2.0%2B-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"></a>
  <a href="https://developer.android.com/media/media3"><img alt="Media3 ExoPlayer" src="https://img.shields.io/badge/Media3-ExoPlayer-E50914?style=for-the-badge&logo=google&logoColor=white"></a>
  <a href="https://m3.material.io/"><img alt="Material 3 Design" src="https://img.shields.io/badge/Material%203-Expressive-6750A4?style=for-the-badge&logo=materialdesign&logoColor=white"></a>
</p>

## About

Animarvle is a free, modern Android streaming client built from the ground up for smooth, high-speed playback of Anime, Movies, and TV series. It combines a pure OLED black (`#000000`) obsidian glass design with low-latency edge resolution, adaptive HLS video streaming, rich franchise metadata, and cross-device cloud watchlist synchronization.

⭐ **Please give the repo a star if you like the project. It helps more people find it!** 🌟

## Highlights

- **Pure OLED Black & Obsidian Glass UI:** Pitch-black `#000000` dark mode foundation with live real-time frosted glass backdrop blur and glowing specular edges.
- **Dual Media Hubs:** Dedicated Anime hub powered by AniList (Trending, Airing Now, Seasonal, Donghua) and Movies & TV hub powered by TMDB with direct streaming provider rails (Netflix, Prime Video, Disney+, Apple TV+, Hotstar, Max).
- **Obsidian Glass Player Engine:** AndroidX Media3 / ExoPlayer with adaptive HLS bitrate streaming, multi-audio track routing (SUB, DUB, RAW), manual quality selector (4K down to 360p), and styled SSA/ASS subtitles.
- **Smart Auto-Rotate Fullscreen:** Portrait-locked browsing interface that smoothly expands into an immersive edge-to-edge landscape player when rotated.
- **Cross-Device Cloud Watchlist:** Automatic background watchlist (`My List`) synchronization with Google Drive AppData using deterministic conflict resolution.
- **Franchise Relations & TMDB Saga Enrichment:** Chronological prequel/sequel series order and canonical saga breakdown for continuous anime like *One Piece* and *Bleach*.
- **In-App Auto-Updater:** Seamless in-app update checks with direct package installation and SHA-256 integrity verification.
- **Multi-Architecture Builds:** Optimized native APK packages for `arm64-v8a`, `armeabi-v7a`, `x86_64`, and `universal`.

<details>
<summary><strong>Features</strong></summary>

### 🎬 Playback & Player
- Adaptive HLS bitrate playback powered by AndroidX Media3 / ExoPlayer.
- Localized glass submenus for Speed (0.25x – 2.0x), Quality, Audio language, and Subtitles without UI recreation or flicker.
- Dual-mode episode layout: 2-column 16:9 thumbnail cards with episode titles vs. 6-column anime number tiles.
- Custom subtitle engine supporting SRT, VTT, and styled ASS/SSA tracks with delay adjustments.
- Picture-in-Picture (PiP) and background audio playback support.
- Configurable double-tap seek duration (5s to 90s) and hardware aspect-ratio resize modes (Fit, Fill, Zoom).

### 🌌 Interface & Theming
- Pure OLED `#000000` surface hierarchy ensuring zero grey wash and vibrant contrast.
- Real-time stack blur capturing content behind the top header and bottom navigation bar.
- 1:1 structural skeleton loaders and procedural polygon-morph loading animation (`VortexMorphLoadingView`).
- 35% velocity parallax backdrop with dynamic progressive dimming on Details screen.

### 📚 Library & Tracking
- Reactive `My List` indicator with status categorization (Watching, Completed, Plan to Watch).
- Vertical Continue Watching rail with 2:3 cover poster geometry and progress tracking.
- Domain isolation ensuring Anime and Live-Action media remain cleanly partitioned in history and library.
- Google Play Services authentication with Google Drive AppData watchlist cloud synchronization.

### ⚡ Gateway & Sources
- Built-in edge relay gateway resolving adaptive HLS streams instantly.
- Multi-server fallback architecture (Spiral, Turbo, FastX) ensuring high stream reliability.
- In-app Extension Manager supporting external media source plugins.

</details>

<details>
<summary><strong>Recent improvements</strong></summary>

- **Hardwired Edge Resolver:** Streamlined Cloudflare edge relay resolution directly inside the source engine for sub-second startup times.
- **Cloud Watchlist Synchronization:** Added Google Drive AppData cloud sync with deterministic last-write-wins conflict resolution.
- **Franchise Relation Ordering:** Traverses prequel and sequel chains backward and forward to build strictly chronological season orders.
- **Continuous Anime TMDB Saga Enrichment:** Single-entry continuous anime are enriched with all canonical TV sagas and arc titles.
- **Smart Orientation Engine:** App-wide portrait lock with automatic full-screen landscape expansion upon physical device rotation during playback.
- **Multi-Architecture Packaging:** Independent CI builds for `arm64-v8a`, `armeabi-v7a`, `x86_64`, and `universal` with individual SHA-256 checksums.

</details>

## Star History

<a href="https://www.star-history.com/?repos=nd7hdyt%2FAniMarvle&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=nd7hdyt/AniMarvle&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=nd7hdyt/AniMarvle&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=nd7hdyt/AniMarvle&type=date&legend=top-left" />
 </picture>
</a>

## Install

1. Open the [latest GitHub release](https://github.com/nd7hdyt/AniMarvle/releases/latest).
2. Download the APK corresponding to your device architecture:
   - **`arm64-v8a`** *(Recommended)*: For modern Android phones and tablets (fastest performance, smaller download).
   - **`universal`**: Compatible with all Android devices.
   - **`armeabi-v7a`**: For older 32-bit Android devices.
   - **`x86_64`**: For Android emulators and x86 Chromebooks.
3. Install the APK on your device.
4. Launch Animarvle and start streaming.

> **Note:** Android may request permission to allow installations from your browser or file manager. This is standard for APKs installed outside the Google Play Store.

## FAQ

### Does Animarvle host or distribute video content?
> No. Animarvle does not host, upload, or maintain any video files or streams on its servers. The application is an edge client that resolves streams dynamically through third-party services and extensions.

### Is Animarvle free?
> Yes. Animarvle is 100% free with no subscription tiers or paywalls.

### How do app updates work?
> Animarvle includes a built-in in-app updater. When an update is published, you can download and install it directly within the app with one tap. You can also download the latest APK manually from the GitHub Releases page.

### Can I sync my watchlist across multiple devices?
> Yes. Simply sign in with your Google account in the Profile tab. Your watchlist and bookmarks will automatically synchronize across all devices connected to the same Google account.

## Disclaimer

<div align="left">

The developer(s) of this application have no affiliation with any media providers or video hosting services. Animarvle acts strictly as a media client and indexing tool; it does not host, store, or upload media files. Users are responsible for complying with the terms and copyright regulations in their respective jurisdictions.

</div>

## License

[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)

<div align="left">

Animarvle is licensed under the **GNU General Public License v3.0 (GPLv3)**. You may copy, distribute, and modify the software under the terms of the GPLv3 license.

</div>
