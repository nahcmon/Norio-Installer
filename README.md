# Norio for macOS

Norio runs a team of coding agents of your choice on your projects, with an
orchestrator that plans the work and keeps you posted.

This repository exists only to distribute the app. The source lives elsewhere.

## Download

**[Download Norio for macOS](https://github.com/nahcmon/Norio-Installer/releases/latest/download/Norio.dmg)**

Apple silicon Mac, macOS 14 or later. Open the disk image and drag Norio into
Applications.

### The first launch needs one extra click

This build isn't notarized by Apple yet, so macOS may say it can't check Norio
for malicious software. Open **System Settings → Privacy & Security**, scroll to
the message about Norio, and click **Open Anyway**. You only do this once.

## Updates

Norio checks this repository on launch and every 30 minutes. When a new version
is out, an **Update** button appears with the release notes; nothing downloads
until you click it. Updates are signed, and Norio refuses any that aren't.

Each release holds the full disk image, small patch files (`.delta`) for
updating from recent versions, and `appcast.xml`, the feed Norio reads.
