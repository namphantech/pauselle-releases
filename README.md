<p align="center">
  <a href="https://pauselle-website.pages.dev">
    <img src="https://pauselle-website.pages.dev/img/robin.svg" alt="Pauselle" width="72">
  </a>
</p>

<h1 align="center">Pauselle</h1>

<p align="center">
  <b>A little room to breathe.</b><br>
  A gentle, local-first break reminder for macOS.
</p>

<p align="center">
  <a href="https://github.com/namphantech/pauselle-releases/releases/latest/download/Pauselle-macOS.dmg"><b>Download for Mac</b></a>
  ·
  <a href="https://github.com/namphantech/pauselle-releases/releases">Release notes</a>
  ·
  <a href="https://pauselle-website.pages.dev">Website</a>
</p>

---

"One more thing" easily becomes one more hour. Pauselle reminds you to look away, stretch and breathe — and stays quiet when you're busy. No account, no server, no telemetry.

## Highlights

- **20-20-20 by default** — work 20 minutes, look 20 feet away for 20 seconds. Every interval is adjustable.
- **A gentle heads-up** — a small note a minute before each break. Start now or snooze for 1, 5 or 15 minutes.
- **Countdown by your cursor** — a tiny timer appears where you're looking, and waits while you're typing or dragging.
- **Smart Pause** — holds the timer during calls, screen sharing or recording, fullscreen games, the apps you choose and selected calendar events. Resumes on its own.
- **Calm break screen** — covers your displays, with a timer and soft start and end chimes. Afterwards you're back where you left off.
- **Local first** — settings and history live in SQLite on your Mac and work offline. Export to JSON or erase everything any time.

## Install

1. Download [`Pauselle-macOS.dmg`](https://github.com/namphantech/pauselle-releases/releases/latest/download/Pauselle-macOS.dmg) from the latest release.
2. Open the DMG and drag **Pauselle** into **Applications**.
3. Launch it from Applications. Pauselle lives in the menu bar.

Pauselle is signed with an Apple Developer ID and notarized by Apple, so it opens like any other Mac app.

### Requirements

| | |
|---|---|
| macOS | 13 Ventura or later |
| Chip | Apple Silicon (arm64) |
| Price | Free preview |

Intel Macs and Windows aren't tested yet.

### Verify your download (optional)

Each release ships a `SHA256SUMS.txt`. Put it in the same folder as the DMG and run:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

A matching checksum confirms the file arrived intact. To check the signature and notarization after installing:

```sh
spctl -a -vv /Applications/Pauselle.app
```

It should report `source=Notarized Developer ID`.

## Privacy

- Data stays on your Mac. Nothing is sent to a server.
- Website stats are opt-in and record domains only — never paths, queries or page content.
- Calendar and Automation permissions are optional and requested only when a feature needs them.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/namphantech/pauselle-releases/issues). Please leave out private browsing data, tokens and personal screenshots.

## About this repository

This repo hosts public builds, checksums and release notes only. The app source is private; GitHub's auto-generated "Source code" archives contain just this repository's files. No open-source license is granted for the application.

<p align="center"><sub>© 2026 Pauselle</sub></p>
