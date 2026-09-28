# Classic Piano

A four-lane falling-tile rhythm game for Android. Tiles slide down, you tap
them on the judgement line. Twelve classical pieces, two difficulties each,
a full-length and a ~90-second short map of every one, five lives, local best
records, a global leaderboard, and online multiplayer for up to four players.

This repository is the **public release channel**: the APK downloads and the
[privacy policy](https://szkript.github.io/classic-piano/privacy.html). The
game's source lives in a private repository.

## Install

1. Download `classicpiano.apk` from the newest release on the
   [releases page](../../releases) (currently
   [0.5.1](../../releases/download/v0.5.1/classicpiano.apk)).
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

The game shows ads through Google AdMob. Since 0.5 they are **real ads**, so
please treat them like any player would: watch them, and **don't tap one just to
help**. Clicks from people who know the developer count as invalid traffic, and
Google closes ad accounts for it.

## What's new

### 0.5.1 — 2026-09-28 — continuing after an ad works again

**Fixed: after watching the continue ad, the notes froze and the run failed
soon after.** The game carried on underneath, but the picture was stuck far
ahead of the music, so there was nothing to hit. Now the notes pick up exactly
where the song restarts. Thanks to the tester who reported it.

If SHARE RUN DATA is on, the run summary now also says how a continue went
(whether the ad was watched, and whether the game, the music and the picture
all restarted properly), so a problem like this shows up without needing the
phone. The [privacy policy](https://szkript.github.io/classic-piano/privacy.html)
lists the new fields; nothing about the ad itself or you is included.

Install it over 0.5; settings and records are kept.

### 0.5 — 2026-09-28 — ads, a new icon and GRAND by default

**This version has real ads.** They are live, so please watch them like any
player would, and **don't tap an ad just to help me.** Clicks from people who
know the developer count as fake traffic, and Google closes ad accounts for it.
There are only two kinds:

- **Continue:** when you run out of lives you can watch a short ad to carry on
  from 2 seconds before you died. It's your choice; "FELADOM" (give up) goes
  straight to results. If no ad is available, the continue is free.
- **Before a run:** now and then a full-screen ad appears when you start a song.
  Never during a song, never in your first 4 runs, never in the first 45 seconds
  after opening the app, at most one every 3.5 minutes, and never in
  multiplayer or the tutorial.

**Consent question on first launch.** In the EU, Google asks whether ads may
use your data. Either answer is fine; the game plays the same. You can change it
later in Settings → **AD PRIVACY OPTIONS**.

**New app icon**, from the GRAND board. **GRAND is now the default board** for
new players; if you already picked a board, you keep it.

Please tell me whether the ads feel too frequent, and whether any ad ever broke
a run (the song not coming back, sound missing afterwards).

Songs, timing and scoring are unchanged, and you can still play multiplayer with
people on 0.4. Install it over your current version as usual. Your settings and
records stay.

### 0.4 — 2026-09-24 — mistakes you can hear and feel

**Missed notes now sound wrong.** When you miss a note, or let go of a long
note too early, the game plays that note out of tune, like a pianist fumbling
it. Hits sound exactly as before: only mistakes make a noise.

**Your phone vibrates on mistakes.** You get a short buzz when you miss and a
longer one when you run out of lives. It works even if you have turned off
vibration for touches in your phone's settings.

Both are on by default. Each has its own switch in Settings → GAMEPLAY:
**MISS SOUND** and **VIBRATION**. Please tell me whether the miss sound helps
you or just annoys you, and whether it is too loud or too quiet.

**One board fewer.** ARC is gone. Settings → GAMEPLAY → **BOARD** now offers
**CLASSIC**, **GRAND**, **SCORE** and **HANDS**. If you were playing on ARC,
the game switches you to CLASSIC. I'd still like to hear which board you
enjoy most, and especially what you think of SCORE.

Songs, timing and scoring are unchanged, and you can still play multiplayer
with people on 0.3 and 0.3.1. Install it over your current version as usual.
Your settings and records stay.

### 0.3.1 — 2026-09-24 — tells us which board you played

A small update to 0.3. Nothing you can see has changed: same boards, same songs,
same timing, and you can still play multiplayer with people on 0.3.

If you have **Share run data** switched on in Settings, each run now also says
which board you played it on. That lets me check whether a board changes how
early or late people tap, without having to ask you. The
[privacy policy](https://szkript.github.io/classic-piano/privacy.html) lists
the new item. If sharing is off, nothing is sent, as before.

Install it over 0.3 as usual. Your settings and records stay.

### 0.3 — 2026-09-24 — four experimental boards

This build is a design test. There are now **four new boards** to play on, and
I'd like to hear which one you enjoy playing most. Songs, timing, scoring and
multiplayer are unchanged. Only the look of the game is new.

**How to switch:** Settings → GAMEPLAY → **BOARD**, then pick **CLASSIC**,
**GRAND**, **SCORE**, **ARC** or **HANDS**. The game remembers your choice,
and CLASSIC is the board you already know.

- **GRAND:** you play from inside a grand piano at night. Notes slide down a
  lacquered highway toward four big ivory keys at the bottom of the screen.
  - Each note has a lane-coloured edge so you can tell the lanes apart.
  - A hit presses the key down and throws the red felt hammer up into the
    strings, and the lane's strings flash gold.
  - While you hold a note, the key stays down under a column of warm light.
  - Your five lives are candles, and a candle goes out when you lose a life.
- **SCORE:** the song is played from an engraved page of sheet music. The
  staff is turned on its side, so its four spaces, F A C E, are the four
  lanes, with a lettered ivory key under each one.
  - Notes are black noteheads with a watercolour wash in the lane's colour.
  - A hit turns the note to gold leaf. A miss smears it into an ink blot.
  - Bar lines scroll past with the music.
  - Past a 50 combo the whole page gilds itself.
- **ARC:** a record spins near the top of the screen. Your combo is on its
  label, and a gold ring around it shows how far into the song you are.
  - Notes fly out along four curved rails to targets on a wide arc at the
    bottom. The arc follows the path your thumbs naturally sweep, which may be
    more comfortable than straight columns. Tell me if it is.
  - A hit fills the target and sends a shockwave outward.
  - Every 50 combo the record flares gold.
- **HANDS:** the board splits into two highways, one for each thumb. The left
  one is warm (bass) and the right one is cool (treble).
  - The line down the middle is the song's timeline, filling with gold as the
    song goes on.
  - When both hands have a note at the same moment, the two notes are tied
    with a gold bar. Hit both together and a gold arc jumps from thumb to
    thumb ("CHORD PERFECT").
- **What I'd love to hear:**
  - Which board you'd keep, and which you'd throw away.
  - Whether you can read the notes coming just as well as on CLASSIC. Try a
    fast song, for example Revolutionary Etude.
  - Whether any board feels less smooth, or whether hits feel late or early on
    it.
  - Anything that's hard to read, covers the notes, or looks broken.
- **Also:** the "combo", "accuracy" and "chord" labels are translated to
  Hungarian.
- Installs over 0.2 and keeps your settings and records. You can still race
  players who are on 0.2, and they will see their own board.

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
