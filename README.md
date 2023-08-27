# This is a fork of [ani-cli](https://github.com/pystardust/ani-cli) with some extra features.

<p align=center>
<br>
<a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
<a href="#Linux"><img src="https://img.shields.io/badge/os-linux-brightgreen">
<a href="#MacOS"><img src="https://img.shields.io/badge/os-mac-brightgreen">
<a href="#Android"><img src="https://img.shields.io/badge/os-android-brightgreen">
<a href="#Windows"><img src="https://img.shields.io/badge/os-windows-yellowgreen">
<a href="#iOS"><img src="https://img.shields.io/badge/os-ios-yellow">
<a href="#Steam-deck"><img src="https://img.shields.io/badge/os-steamdeck-yellow">
</a>
</p>

<h3 align="center">
<br>
A cli to browse and watch anime (alone AND with friends). This tool scrapes the site <a href="https://allanime.to/">allanime.</a>
</h3>
	
<h1 align="center">
	Showcase
</h1>

[ani-cli-demo.webm](https://user-images.githubusercontent.com/44473782/224679247-0856e652-f187-4865-bbcf-5a8e5cf830da.webm)

## Table of Contents

- [Fixing errors](#fixing-errors)
- [Install](#install)
- [Uninstall](#uninstall)
- [Homies](#homies)
- [Contribution Guidelines](./CONTRIBUTING.md)
- [Disclaimer](./disclaimer.md)

## Fixing errors

If you encounter "Video url not found" or any breaking issue, then make sure you are on latest version by typing
`sudo ani-cli -U` to update on Linux, Mac and Android. On Windows, run gitbash as administrator then there type `ani-cli -U`.
If after this the issue persists then open an issue.

History has been reworked and relocated. We're working on a transition script, please be patient. Old history can be viewed with `less ${XDG_CACHE_HOME:-$HOME/.cache}/ani-hsts`

## Install

### Installing from source

_This method works for any unix-like operating system_

Install dependencies [(See below)](#dependencies)

```sh
git clone "https://github.com/adamekka/ani-cli.git"
sudo ./ani-cli/install
rm -rf ani-cli
```

## Uninstall

- Unix-like:

```sh
sudo rm "/usr/local/bin/ani-cli"
```

## Dependencies

- grep
- sed
- curl
- mpv - Video Player
- iina - mpv replacement for MacOS
- aria2c - Download manager
- yt-dlp - m3u8 Downloader
- ffmpeg - m3u8 Downloader (fallback)
- fzf - User interface

## Homies

### Original

- [ani-cli](https://github.com/pystardust/ani-cli): Original ani-cli

### Other

- [animdl](https://github.com/justfoolingaround/animdl): Ridiculously efficient, fast and light-weight (supports most sources: allanime, zoro ... (Python)
- [jerry](https://github.com/justchokingaround/jerry): stream anime with anilist tracking and syncing, with discord presence (Shell)
- [anipy-cli](https://github.com/sdaqo/anipy-cli): ani-cli rewritten in python (Python)
- [saikou](https://github.com/saikou-app/saikou): Best android app for anime/manga with anilist integration (Kotlin)
- [mangal](https://github.com/metafates/mangal): Download & read manga from any source with anilist sync (Go)
- [lobster](https://github.com/justchokingaround/lobster): Watch movies and series from the terminal (Shell)
- [mov-cli](https://github.com/mov-cli/mov-cli): Watch movies/shows in the cli (Python/Shell)
- [dra-cla](https://github.com/CoolnsX/dra-cla): ani-cli equivalent for korean dramas (Shell)
- [redqu](https://github.com/port19x/redqu): A media centric reddit client (Clojure)
