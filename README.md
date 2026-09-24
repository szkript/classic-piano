# Classic Piano

A four-lane falling-tile rhythm game for Android. Tiles slide down, you tap
them on the judgement line. Twelve classical pieces, two difficulties each,
a full-length and a ~90-second short map of every one, five lives, local best
records, a global leaderboard, and online multiplayer for up to four players.

This repository is the **public release channel**: the APK downloads and the
[privacy policy](https://szkript.github.io/classic-piano/privacy.html). The
game's source lives in a private repository.

## Install

1. Download `classicpiano.apk` from the [latest release](../../releases/latest).
2. Open it on the phone. Android will ask you to allow installs from your
   browser or file manager the first time — that is expected for an app that
   is not on the Play Store yet.
3. Android 8.0 (API 26) or newer, ARM64.

The first launch runs a thirty-second latency calibration. Do it with the
volume up; every timing judgement in the game depends on it.

## Testers

If you are one of the testers: thank you. Two switches on the settings screen
are **off by default** and stay off unless you turn them on:

- **SHARE RUN DATA** sends an anonymous timing summary after each run so the
  game can be tuned for phones the developer does not own.
- **POST MY SCORES** publishes your nickname, score and accuracy on the
  global leaderboard.

The [privacy policy](https://szkript.github.io/classic-piano/privacy.html)
says exactly what each one does.

The game shows ads through Google AdMob. In this pre-release build they are
Google's **test ads** — tapping them is harmless and earns nothing.

## What's new

### 0.2 — 2026-09-24

- **In-game display:** a big score, the song's title, and a timeline along
  the top of the board showing how far through the song you are, with the
  elapsed time and the song's length.
- **New look:** the board is a soft-dark neon, the four keys sit on the
  judgement line, and hold notes look like holds.
- **Redesigned menu and screens:** larger, easier-to-read text on the menu,
  settings, calibration, scores, results, the lobby and the race results. The
  song-length switch shows how long each version is.
- **Removed:** the `<` / `>` offset buttons during a song. Timing is set by
  the calibration in settings.
- Installs over 0.1 and keeps your settings and records. You can still race
  players who are on 0.1.

### 0.1 — 2026-09-20

First public build for testers.

## Credits

Four of the pieces are generated from engravings published by the Mutopia
Project, and their licences ask for the credit to travel with the work:

```
Engraving: Mutopia Project, typeset by smailliw
CC BY-SA 3.0 - creativecommons.org/licenses/by-sa/3.0
```

```
Engraving: Mutopia Project, typeset by Robert Clausecker
CC BY 3.0 - creativecommons.org/licenses/by/3.0
```

The same credits are shown under each song inside the game.
