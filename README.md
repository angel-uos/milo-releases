# MILO releases

MILO is a meeting assistant for the Mac: it transcribes meetings live, starts a new line when a different
person speaks, and writes meeting notes and action items. Everything runs on your Mac: audio and transcripts
never leave it, and sessions are stored encrypted.

This repository only publishes the ready-to-use app. Download the latest version from
[Releases](https://github.com/angel-uos/milo-releases/releases/latest).

## Install

1. Download `MILO-<version>.zip` from the [latest release](https://github.com/angel-uos/milo-releases/releases/latest).
2. Move the zip file into your **Applications** folder.
3. In **Applications**, double-click the zip file to unzip it. This creates **MILO**.
4. Delete the zip file (drag it to the **Bin**): only **MILO** is needed.
5. The first time, right-click **MILO** and choose **Open**: the app is not signed with an Apple Developer ID,
   so macOS asks you to confirm.
6. When you first press **Start**, allow microphone access.

## Update to a new version

1. Quit MILO.
2. In **Applications**, drag the old **MILO** to the **Bin**. Your sessions are kept: they are stored outside
   the app.
3. Then follow steps 1–5 above. (If the old MILO is still there when you unzip, macOS creates a second copy
   called "MILO 2" instead of replacing it.)

## Requirements

- A Mac with Apple Silicon (M1 or later).
- An internet connection the first time, to download the speech model (about 1.6 GB) and, when you first
  summarise, the summary model (about 1.8 GB). After that MILO works offline.

MILO tells you when a new version is available (Settings → Version).
