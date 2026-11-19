**VIBECODED, Sorry :(**

# Kana Trainer

A small single-file web app for practicing hiragana and katakana. A kana (or a short string of kana) appears, you type its romaji, and you get instant feedback. No build step, no dependencies, no server.

## Run it

Go to https://1lkars.github.io/KanaTrainer/ and play it from your browser. Available both from PC and phone.

**Modes**
- **Classic:** go through the whole set once, at your own pace. Every kana appears exactly once across the questions.
- **Timed:** answer as many as you can before the round ends.
- **Endless:** no end and no timer. Stop whenever you like.

Any mode can be combined with the **Hide each kana after a short time** tick box. The kana disappears after the time you set, but you can still type your answer afterwards, and the summary shows how many you got right after it vanished.

**Content**
- Hiragana, katakana, or both.
- Single kana, combinations (yoon like きゃ, しゅ, ちょ), or both.
- Difficulty from Easy to Expert. Each question is a random string of up to 5 (Easy), 10 (Medium), 15 (Hard) or 20 (Expert) kana, and difficulty also controls which combinations appear:
  - Easy: standard combinations (kya, sha, cho…)
  - Medium: adds voiced ones (gya, ja, bya, pya)
  - Hard: adds foreign sounds (fa, ti, je, wi…)
  - Expert: adds rare ones (kye, nye, ye…)
- The max string length can be adjusted separately with a slider and number field. Set it to 1 for one kana at a time.
- Turn individual small kana (ゃ, ゅ, ょ) on or off for combinations, for example to practice only kya and kyo.
- Practice specific rows (K, S, T…). Pick as many as you want, or none for all rows.

**Settings**
- Round length: slider that snaps every 5 seconds, plus a number field for exact values.
- Visible time for the hide-after-delay option: slider plus number field.
- Sound effects on/off and volume (slider plus number field). Sound settings are remembered between visits.

## Controls

- `Enter` submits your answer
- `Esc` ends the round

## Notes

- The whole app lives in one HTML file with no external requests.
- Answers are romaji in Hepburn style, for example `shi`, `chi`, `tsu`, `fu`, `ji`.
- Written with heavy AI assistance and only lightly reviewed. Expect rough edges, and PRs are welcome.
