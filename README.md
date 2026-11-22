# Media Tambola

Media Tambola is an offline Windows desktop app for running Tambola (Housie) game nights where every number is tied to a song or video. The host draws a number, the audience sees and hears the matching media on a projector, and players claim prizes on tickets you generate and print yourself.

This repository only holds the downloadable installers. The app itself is not published here.

## Download

Go to the [Releases](../../releases/latest) page and download the file named `Media Tambola_<version>_x64-setup.exe` from the latest release.

## Install

1. Run the downloaded setup file and follow the steps.
2. Windows may show a "Windows protected your PC" (SmartScreen) message because the installer is not yet signed with a paid code-signing certificate. Choose **More info**, then **Run anyway**, only if you downloaded the file from this Releases page.
3. Start **Media Tambola** from the Start menu.

Requirements: Windows 10 or 11 (64-bit). No internet is needed to play. Everything is stored on your computer.

## What it does

- Song Grid tickets (3 x 5) and classic 90-ball tickets (3 x 9)
- Each number is mapped to a video or image from your own media folders
- Projector window for the audience, with a reveal animation before each song
- Prize schemes with claim checking: the full ticket is shown with the called songs marked
- Ticket generator and printing with your own background, header images or built-in designs
- English and Gujarati, one language at a time
- Backup and restore of your game data

## Updates

Starting with the first version that includes the updater (1.0.5 or later; versions before it must be updated by installing the new setup by hand), when a newer version is published here the app shows **An update is available** with an **Update** button. Pressing it downloads the new setup, verifies it, installs it and restarts the app. Updates are never started while a game is running. You can turn the automatic check off in Settings.

Your games, tickets and media settings are kept when you update.

## Release notes

Each release on the [Releases](../../releases) page lists what changed in plain words.

## Safety and privacy

- The app works offline and does not send your data anywhere.
- The only network use is the optional update check, which reads the latest version information from this repository, and the optional one-time download of the video preview tool (FFmpeg), which the app asks you to confirm first.
- Every update is checked against a digital signature before it is installed.
