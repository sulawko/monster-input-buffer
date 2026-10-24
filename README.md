<p align="center">
  <img src="logo.png" width="110" alt="Monster Input Buffer">
</p>

<h1 align="center">Monster Input Buffer</h1>

<p align="center">
  A <b>Geode</b> mod for Geometry Dash 2.208 that fixes your clicks "just in case".<br>
  Made by <b>SuLawko</b>.
</p>

<p align="center">
  <a href="https://github.com/sulawko/monster-input-buffer/releases/latest"><b>⬇ Download</b></a> ·
  <a href="https://sulawko.github.io/monster-input-buffer/">Website</a> ·
  <a href="https://discord.gg/Ya9GCDp7fd">Discord</a>
</p>

---

## What does it do?

It simulates your click a few ticks ahead using two invisible "ghost" players. If clicking now would kill you, but a click slightly later survives, your input is held back and delivered at the right tick. It is a strong but not exaggerated help (1 tick = 0.25 frames at 60 fps).

- Cube, ball, ufo, spider, robot, swing and wave (presses and releases). The ship is never touched.
- Orbs, pads, gravity portals and speed portals are simulated too.
- Fast wave spam is left alone.

## Installation

1. Install [Geode](https://geode-sdk.org) (version 5.11.2 or newer) on Geometry Dash 2.2081, Windows.
2. Download `sulawko.monster-input-buffer.geode` from the [latest release](https://github.com/sulawko/monster-input-buffer/releases/latest).
3. Copy it into the game's `geode/mods` folder (or drag it onto the game) and restart.

## Usage

| Key | Action |
| --- | --- |
| **F6** | Cycles the strength: 0.5f → 1f → 2f → 4f → 6f → 8f → custom → off |
| **K** | Shows / hides the log panel inside a level |

A console window with the same log also opens when the game starts. Every time the mod saves one of your clicks it logs it (for example `SAVED press +3t`). The settings (custom delay, prediction time, etc.) are in the mod's configuration inside Geode.

## Important

This mod changes the timing of your inputs: completions made with it may not count as legit on lists or leaderboards. Use it at your own risk.

Unofficial mod, not affiliated with RobTop Games or the Geode team.

---

<sub>This repository contains the mod's website and its downloads (Releases). To update the download, edit the `CONFIG` block in `index.html` (`DOWNLOAD_URL`, `SHA256`, `YOUTUBE_ID`).</sub>
