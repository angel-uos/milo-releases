# MILO releases

MILO is a meeting assistant for the Mac: it transcribes meetings live, starts a new line when a different
person speaks, and writes meeting notes and action items. Everything runs on your Mac: audio and transcripts
never leave it, and sessions are stored encrypted.

This repository only publishes the ready-to-use app. Download the latest version from
[Releases](https://github.com/angel-uos/milo-releases/releases/latest).

## Install or update

1. Download `MILO-<version>.zip` from the latest release and open it.
2. Quit MILO if it is running, then drag **MILO** into **Applications** (choose **Replace** when updating).
   Your sessions are kept: they are stored outside the app.
3. The first time, right-click MILO and choose **Open**: the app is not signed with an Apple Developer ID,
   so macOS asks you to confirm.
4. When you first press Start, allow microphone access.

## Requirements

- A Mac with Apple Silicon (M1 or later).
- An internet connection the first time, to download the speech model (about 1.6 GB) and, when you first
  summarise, the summary model (about 1.8 GB). After that MILO works offline.

MILO tells you when a new version is available (Settings → Version).
