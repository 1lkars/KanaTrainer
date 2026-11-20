**VIBECODED, Sorry :(**

# Kana Trainer

A small single-file web app for practicing hiragana and katakana. A kana (or a short string of kana) appears, you type its romaji, and you get instant feedback. No build step, no dependencies, no server.

## Run it

Go to https://1lkars.github.io/KanaTrainer/ and play it from your browser. Available both from PC and phone.

## Features

**Modes**
- **Classic:** go through the whole set once, at your own pace. Every kana appears exactly once across the questions.
- **Timed:** answer as many as you can before the round ends.
- **Endless:** no end and no timer. Stop whenever you like.

Any mode can be combined with the **Hide each kana after a short time** tick box. The kana disappears after the time you set, but you can still type your answer afterwards, and the summary shows how many you got right after it vanished.

**Content**
- Hiragana, katakana, or both.
- Content: single kana only, combinations only (random strings of 2 or more kana, like katakana-style nonsense words), or a mix of both.
- Difficulty from Easy to Expert sets the longest string: 5 (Easy), 10 (Medium), 15 (Hard) or 20 (Expert) kana. It also decides which small-kana syllables can appear (standard, voiced, foreign sounds, rare ones).
- The max string length can be adjusted separately with a slider and number field. Difficulty and max length are hidden for "Single kana only".
- Small-kana syllables (きゃ, しゅ, ちょ…) are included but shown rarely, and ゃ, ゅ and ょ can each be switched off individually.
- Practice specific rows (K, S, T…). Pick as many as you want, or none for all rows.
- Practice specific rows (K, S, T…). Pick as many as you want, or none for all rows.

**Round overview**
After every round you get a summary with accuracy, time, average time per answer, best streak and a list of the kana you missed (with what you typed). Play again with the same settings or go back to setup.

**Settings**
- Round length: slider that snaps every 5 seconds, plus a number field for exact values.
- Visible time for the hide-after-delay option: slider plus number field.
- Sound effects on/off and volume (slider plus number field). Sound settings are remembered between visits.
- Theme: follows your system light/dark setting, or force light or dark. Remembered between visits.

## Controls

- `Enter` submits your answer
- `Esc` ends the round

## Notes

- The whole app lives in one HTML file with no external requests. The tab icon is embedded in it too.
- Answers are romaji in Hepburn style, for example `shi`, `chi`, `tsu`, `fu`, `ji`.
- Written with heavy AI assistance and only lightly reviewed. Expect rough edges, and PRs are welcome.
