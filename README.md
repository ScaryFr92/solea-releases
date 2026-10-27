<h1 align="center">
  <br>
  <img src="images/icon.png" alt="Solea" width="200">
  <br>
  Solea
  <br>
</h1>

<h4 align="center">A free IPTV player for Android TV, Fire TV, Android, iPhone and Windows: Xtream Codes and M3U playlists, with a TV interface built for the remote. Built with <a href="https://flutter.dev/" target="_blank">Flutter</a> and <a href="https://claude.com/claude-code" target="_blank">Claude</a>.</h4>

<p align="center"><b><a href="https://solea.tv/en/">solea.tv</a></b></p>

<p align="center">
  <a href="#download">Download</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#community">Community</a> •
  <a href="#whats-new">What's New</a> •
  <a href="#built-with-claude">Built with Claude</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

<div align="center">

  [![Latest release](https://img.shields.io/github/v/release/ScaryFr92/solea-releases?display_name=tag&color=E8506E)](https://github.com/ScaryFr92/solea-releases/releases/latest)
  [![Downloads](https://img.shields.io/github/downloads/ScaryFr92/solea-releases/total?color=FFB36B)](https://github.com/ScaryFr92/solea-releases/releases)
  [![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/42FVvupACy)
  [![Built with Claude](https://img.shields.io/badge/built%20with-Claude-D97757)](#built-with-claude)

</div>

> [!IMPORTANT]
> Solea is a player, just as a web browser is for web pages. It **provides, sells and recommends no content and no
> subscription**: it only plays the sources you add yourself, and you must have the right to watch them.

This repository hosts the **releases** of Solea (downloads and release notes). The source code is private.

## Download

Get the latest version on the [releases page](https://github.com/ScaryFr92/solea-releases/releases/latest):

* **Android TV, Fire TV Stick, Android boxes, phones and tablets** – `Solea-<version>-android.apk`
  (on a Fire TV: install the *Downloader* app, then type `solea.tv/apk`)
* **Windows** – `Solea-<version>-Setup.exe` (installer) or `Solea-<version>-windows.zip` (portable)
* **iPhone, iPad** – with SideStore: see below

### iPhone and iPad with SideStore

Solea installs on iPhone and iPad with [SideStore](https://sidestore.io), for free, with your own Apple Account. You need
a computer once (about 10 minutes); after that, updates arrive on the iPhone. Step-by-step guide:
**[solea.tv/en/install-iphone](https://solea.tv/en/install-iphone/)**.

Already have SideStore? Add the Solea source (Sources › +):

```
https://raw.githubusercontent.com/ScaryFr92/solea-releases/main/sidestore.json
```

> [!WARNING]
> (Windows) Like other unsigned apps, Solea may be flagged by Windows SmartScreen on first launch: choose
> “More info” › “Run anyway”.

## Key Features

* Live TV, movies, series, anime and replay from your own subscription
* Xtream Codes accounts and M3U / M3U8 playlists, with their XMLTV program guide (EPG); several subscriptions you can
  switch between, and up to 5 backup servers per subscription
* Program guide as a grid, with a live preview of the selected channel
* Sign in a TV from your phone: scan the QR code, type on the phone (end-to-end encrypted)
* Several versions of a title shown as one (quality, language) – the best one your device can play is picked for you
* Forgiving search – typos, accents, missing spaces – and voice search with the remote's mic
* Rich movie and series pages – backdrops, cast with photos, trailers, similar titles (TMDB)
* Sports space – matches and live events of the coming days with the channels showing them, live scores
* Plays everything – hardware decoding on Android, mpv elsewhere: MKV, H.265, HDR, AC3, DTS, TrueHD…
* Subtitles – from the file or found online (OpenSubtitles, SubDL, SubSource, Addic7ed), one-press sync, ASS signs in
  place, appearance in detail
* Skip intro, recap and credits, next episode, playback speed, picture-in-picture on Android, iPhone and iPad
* Remembers your audio and subtitle choices per title, resumes where you left off
* Multiple profiles – avatars or photos, PIN codes, parental control, favorites and "Continue watching" per profile
* Cast to Chromecast (Dolby and DTS converted on the fly, subtitles included), AirPlay, DLNA TVs or another Solea device
* Jellyfin – your own server's movies and series next to your subscription, used as a backup when the provider is busy
* Trakt – watched titles and series progress sent by themselves, your watchlist and lists in the app
* Discord – "Watching Solea" on your profile (Windows)
* Optional Solea account – subscriptions, profiles, favorites, progress and services synced across devices, end-to-end
  encrypted
* A TV interface built for the remote, and a full interface for mouse, keyboard and touch
* French and English
* Platforms
  - Android TV, Fire TV and Android boxes
  - Android phones and tablets
  - iPhone + iPad (with SideStore)
  - Windows

## Screenshots

> All titles, channels, programs, posters and cast below are fictional, made up for these screenshots.

<p align="center">
  <img src="images/tv-home.png" alt="Home on a TV, with the remote" width="49%">
  <img src="images/tv-live.png" alt="Live TV on a TV, with what's on now" width="49%">
</p>
<p align="center">
  <img src="images/tv-movies.png" alt="Movies on a TV" width="49%">
  <img src="images/desktop-home.png" alt="Home on Windows" width="49%">
</p>
<p align="center">
  <img src="images/desktop-movie.png" alt="Movie page" width="49%">
  <img src="images/desktop-series.png" alt="Series page" width="49%">
</p>
<p align="center">
  <img src="images/phone-home.png" alt="Home on a phone" width="24%">
  <img src="images/phone-movie.png" alt="Movie page on a phone" width="24%">
  <img src="images/phone-live.png" alt="Live TV on a phone" width="24%">
</p>

## Community

Questions, bug reports, ideas, beta versions: join us on **[Discord](https://discord.gg/42FVvupACy)**.

You can also open an [issue](https://github.com/ScaryFr92/solea-releases/issues):
- check first that it hasn't been reported already;
- give the steps to reproduce it, your device (TV box model, phone, Windows…) and your Solea version;
- **never** paste your subscription address, username, password or playlist address.

## What's New

Each version comes with its notes on the [releases page](https://github.com/ScaryFr92/solea-releases/releases), in
English, and on [solea.tv](https://solea.tv/en/) in French. Versions ending in `.0` (1.2.0) are final versions, offered
as updates by the app; the others (1.2.5) are test versions: turn on **Settings › About › Beta versions** to get them.

### Coming later

* Samsung TVs (Tizen)
* Apple TV

## Built with Claude

Solea is built by [@ScaryFr92](https://github.com/ScaryFr92) together with **Claude**, Anthropic's AI, using
[Claude Code](https://claude.com/claude-code). ScaryFr92 decides what the app should be and tests every feature on real
devices (TV boxes, Fire TV, Android TVs, iPhone, Windows); Claude writes most of the code, researches the hard parts
(video decoding, Chromecast audio conversion, subtitle sync, audio language detection…) and runs the tests.

## Credits

This software uses the following services and open source projects:
- [Flutter](https://flutter.dev/)
- [TMDB](https://www.themoviedb.org) – movie and series data and images. *This product uses the TMDB API but is not
  endorsed or certified by TMDB.*
- [OpenSubtitles](https://www.opensubtitles.com), [SubDL](https://subdl.com), [SubSource](https://subsource.net),
  [Addic7ed](https://www.addic7ed.com) – subtitles; [TheIntroDB](https://theintrodb.org) – intro and recap timings
- [Trakt](https://trakt.tv) – watch history and lists; [Jellyfin](https://jellyfin.org) – your own media server
- [ExoPlayer / Media3](https://developer.android.com/media/media3), [mpv](https://mpv.io) through
  [media_kit](https://github.com/media-kit/media-kit), [FFmpeg](https://ffmpeg.org) (LGPL) – playback
- [iptv-org](https://github.com/iptv-org) – channel logos; [flag-icons](https://github.com/lipis/flag-icons) (MIT) – flags
- [Plus Jakarta Sans](https://github.com/tokotype/PlusJakartaSans) (SIL Open Font License) – font

## License

© ScaryFr92. All rights reserved. Solea is free to download and use; it may not be modified, resold or
redistributed.
