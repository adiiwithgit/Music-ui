# Wavelength – Music Player UI

A Spotify-style music player interface built with plain HTML, CSS and JavaScript. It is **visual only**: no real audio plays, but the progress bar, timer, queue and controls all behave as if a song were playing.

**Live demo:** https://music-ui-7f6q.onrender.com

## Features

- Three-column layout: sidebar, main view, and a Now Playing / queue panel
- Bottom player bar with play/pause, next, previous, shuffle, repeat, like, seek and volume
- Draggable seek and volume sliders
- Track table with hover play buttons and an animated equalizer on the playing row
- Header color that changes with the current song
- "Jump back in" tiles and a "Made for you" shelf
- Light and dark mode (follows your system, with a toggle button)
- Responsive on desktop, tablet and phone
- Keyboard support: `Space` to play/pause, `←` / `→` on the seek bar to skip 5 seconds
- Respects reduced-motion settings
- No images, frameworks or build step. Cover art is generated with CSS gradients

## Project structure

```
music-player.html   # the whole app: markup, styles and scripts
README.md           # this file
```

## Ideas for next steps

- Real audio with the HTML `<audio>` element
- Search results page
- Lyrics view and full-screen Now Playing
- Album and artist pages
- Save liked songs with `localStorage` when hosted on your own site

## Notes

All artists and songs are fictional. This is a design and learning project and is not affiliated with Spotify.
