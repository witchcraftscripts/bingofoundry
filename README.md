# BingoFoundry
![License](https://img.shields.io/badge/license-MIT-green)
![OBS Widget](https://img.shields.io/badge/OBS-compatible-blueviolet)
![Web Widget](https://img.shields.io/badge/Web--Widget-HTML%2FCSS%2FJS-blue)
![Stars](https://img.shields.io/github/stars/witchcraftscripts/bingo-for-the-entity?style=social)

# BingoFoundry 🎮

**Formerly Bingo for the Entity | Originally the DBD Bingo Widget**

BingoFoundry is evolving from a *Dead by Daylight* Twitch bingo overlay into a customizable bingo platform designed for gamers, streamers, and their communities.

### 🛠️ Project Update | October 10, 2026

Today marks the beginning of BingoFoundry's next chapter!

The repository has been renamed from `bingo-for-the-entity` to `bingofoundry` to reflect the project's expanded vision.

**What's planned for BingoFoundry?**

- Customizable bingo cards for multiple games and genres
- Custom challenge packs and reusable presets
- Multiple visual themes, color palettes, and sound effects
- OBS-friendly overlays and streamer controls
- Saved games, session histories, and progress recovery
- Future community and multiplayer bingo experiences

**Current Status:** Planning and early development.

The original *Dead by Daylight* bingo widget remains the current playable version while the expanded BingoFoundry platform is developed.

Thank you for being part of the journey!

------------------------------

A custom Twitch overlay widget designed for *Dead by Daylight* bingo games. Perfect for streamers who want to add chaotic, creepy fun and viewer interaction to their broadcasts.

![Preview of the Bingo Widget](preview.png)

## 🧩 Features

- Killer, survivor, and action-based bingo modes
- Works natively as a browser source in OBS
- Custom title input
- Click-to-stamp cells with blood splatter effect
- Sound and visual effects for stamped squares and completed bingos

## 🎮 How to Use

1. Open `index.html` in your browser or host it somewhere.
2. In OBS, add a **Browser Source** and point it to the hosted file (or local file with `file:///` path).
3. Choose your bingo mode, enter a title, and hit **Start Game**.
4. Click on cells to mark them as completed.

## 🎨 Assets Used

All assets (fonts, audio, images) are included in the `assets/` folder:
- Custom fonts (`Title.ttf`, `Grid.ttf`, `UI.ttf`)
- Background: `blood-splatter-background.jpg`
- Cell overlay: `blood-splatter-frame.png`
- Audio: `stamp.ogg`, `bingo.mp3`

## 🛠 Customize

You can edit the `pools` object in the HTML `<script>` section to change bingo content. Add your own categories, items, or adjust difficulty.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🧙‍♀️ Credits

Made by [witchcraftscripts](https://github.com/witchcraftscripts) with design inspiration from the Entity themself.
