# Moonshine Cooldown Alert

A small companion tool for the [Abyss Logs DPS Meter](https://github.com/karim-mo/aion2-abysslogs-dps-meter) (AION 2). It watches the cooldown display of the meter and plays a sound when a skill is ready again.

**Closed source.** This repository only holds the download. The program itself is not published, all rights reserved.

## Download

Go to **[Releases](../../releases/latest)** and download `Moonshine-Cooldown-Alert.exe` from the *Assets* of the latest release.

It is one file: nothing to install, no administrator rights needed. Put it anywhere and start it.

- **Windows SmartScreen** may say "Windows protected your PC", because the program is not signed. Click *More info*, then *Run anyway*. A virus scanner can complain for the same reason.
- **Your data** (settings, what the tool learned, your own sounds, the log) is written to a folder called `data` next to the `.exe`. To move the program, move both; to remove everything, delete both.

## What it does

- Reads the cooldown icons of the meter from your screen (square icons, round icons or the list look) and plays a sound you choose per skill the moment a skill is ready again.
- A guided setup walks you through it on the first start.
- Profiles (for example one per class), a mute for single skills, your own sounds (`.wav`, `.mp3`, `.ogg`).
- Optional: start the meter and other programs together with the game through a Steam launch option.
- Two designs: the gentle Moonshine, and, behind the **Woke** button, a loud one with Jamal.

For the first setup, stand in front of a clear, calm background so the tool can find the icons by itself. The game has to run windowed or borderless.

## About it

- **Passive only.** It reads screen pixels, like screen-recording software, and plays sounds. It sends no keyboard or mouse input, does not touch the game process or its memory, and makes no network connections.
- **Windows only.**
- This tool is a companion to the meter but is not made by, endorsed by or affiliated with the meter's author or the game's publisher. Reading the screen is not an in-game automation, but check the game's terms of service yourself before you use any third-party tool.
