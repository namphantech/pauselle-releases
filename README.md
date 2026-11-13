# Pauselle downloads

Public downloads, checksums and release notes for Pauselle, a local-first macOS break reminder.

[Download the latest release](https://github.com/namphantech/pauselle-releases/releases/latest)

## Current platform

macOS 13 or later on Apple Silicon (arm64). Intel Mac and Windows builds are not provided here yet.

## Preview signing

Preview builds are signed ad-hoc, not with an Apple Developer ID, and are not notarized. macOS may show an extra first-launch confirmation. There is no automatic updater yet.

## Verify a download

Download `Pauselle-macOS.dmg` and `SHA256SUMS.txt` from the same release. In that folder, run:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

A checksum verifies download integrity; it is not Apple notarization or an independent publisher signature.

## Repository contents

Application source remains private. This repository contains public distribution information only. GitHub-generated Source code archives contain only this distribution repository's metadata, not the desktop app source. No open-source license is granted for the application by this repository.

Report reproducible issues via this repository's Issues page; omit private browsing data, tokens and personal screenshots.
