# KanaTrainer
**VIBECODED, Sorry :(**

# Kana Sprint

A small single-file web app for practicing hiragana and katakana. A kana appears, you type its romaji, and you get instant feedback. No build step, no dependencies, no server.

## Run it

Download `kana_sprint.html` and open it in any modern browser.

Optional: put `correct.wav`, `wrong.wav` and `finish.wav` in the same folder for sound effects. Without them the app works fine, just silently.

## Features

**Modes**
- **Classic:** go through the whole set once, at your own pace.
- **Timed:** answer as many as you can before the round ends.
- **Endless:** no end and no timer. Stop whenever you like.
- **Flash:** each kana disappears after a short time. You can still type your answer afterwards, and the summary shows how many you got right after it vanished.

**Content**
- Hiragana, katakana, or both.
- Single kana, combinations (yoon like きゃ, しゅ, ちょ), or both.
- Combination difficulty from Easy to Expert:
  - Easy: standard combinations (kya, sha, cho…)
  - Medium: adds voiced ones (gya, ja, bya, pya)
  - Hard: adds foreign sounds (fa, ti, je, wi…)
  - Expert: adds rare ones (kye, nye, ye…)
- Practice specific rows (K, S, T…). Pick as many as you want, or none for all rows.

**Settings**
- Round length: slider that snaps every 5 seconds, plus a number field for exact values.
- Flash visible time: slider plus number field.
- Sound effects on/off and volume (slider plus number field). Sound settings are remembered between visits.

## Controls

- `Enter` submits your answer
- `Esc` ends the round

## Notes

- The whole app lives in one HTML file with no external requests.
- Answers are romaji in Hepburn style, for example `shi`, `chi`, `tsu`, `fu`, `ji`.
- Written with heavy AI assistance and only lightly reviewed. Expect rough edges, and PRs are welcome.
