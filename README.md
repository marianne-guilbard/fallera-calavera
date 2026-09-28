# 💀 La Fallera Calavera — Training Simulator

**▶️ Play online: [marianne-guilbard.github.io/fallera-calavera](https://marianne-guilbard.github.io/fallera-calavera/)**

A browser-based, guided simulator to learn the rules of the Valencian card game
***La Fallera Calavera*** by playing against an AI — before playing the real thing with friends and family.

Available in **Español**, **Français** and **Valencià**.

---

## ✨ Features

- 🃏 **Full card set** — all 55 official card models (100 cards: 27 treasures, 33 battle cards, 40 special cards)
- 🤖 **AI opponent** with 4 difficulty levels: Beginner, Normal, Advanced, Expert
- 🧭 **Contextual guide** — explains each rule at the moment it applies, plus a tactical tip every turn
- 📜 **Action log** and game aids in the sidebar
- 🌍 **Three languages** — Spanish (default), French, Valencian — card names stay in Valencian, as in the original game
- 🌙 **Dark / light theme** and adjustable font size
- 📦 **Zero install** — a single `index.html` file, no build step, no dependencies

## 🎯 Goal of the game

Gather **5 ingredients** on your *mostrador* to cook the paella… and escape the Fallera Calavera before she devours you!
Each turn you take **one action**: sell a treasure, attack, play a special card, or take *almoina* (draw without playing).

## 🚀 Run it locally

No installation needed:

```bash
git clone https://github.com/marianne-guilbard/fallera-calavera.git
cd fallera-calavera
open index.html        # macOS  (or double-click the file / xdg-open on Linux)
```

## 🛠️ Modify and improve it

Everything lives in **`index.html`**:

| Section | What you'll find |
|---|---|
| `<style>` | Colours (CSS variables in `:root`), dark & light themes |
| Welcome page (`#welcome-overlay`) | Intro screen and language choice |
| `TREASURES`, battle & special card arrays | Card data (names, effects, quantities) |
| `I18N` translation keys | All interface texts in `fr` / `es` / `val` |
| Game engine & AI | Turn logic, battles, AI difficulty levels |

To add a language, add a new key (e.g. `en`) to every translation entry and a button on the welcome page.

Ideas for contributions: English translation, multiplayer mode, card illustrations, mobile layout improvements, sound effects.
Feel free to **fork** the project, open an **issue** or send a **pull request**!

## 👩‍💻 Author

Created by **Marianne Guilbard** — [github.com/marianne-guilbard](https://github.com/marianne-guilbard)

Built with the help of Claude (Anthropic) as a personal side project.

## ⚖️ Disclaimer & licence

This is a **personal, unofficial and non-commercial** learning tool.
All rights to the original game *La Fallera Calavera* — its name, rules, cards and artwork — belong to its author, **Enric Aguilar**.
If you enjoy the game, please buy the real one! 🎲

The simulator's source code is released under the [MIT licence](LICENSE). This licence covers the code only, not the original game content.

---

### 🇫🇷 En bref

Simulateur d'entraînement pour apprendre les règles du jeu de cartes valencien *La Fallera Calavera* en jouant contre une IA, avec un guide qui explique chaque règle au bon moment. Disponible en espagnol, français et valencien. Il suffit d'ouvrir `index.html` dans un navigateur. Projet personnel créé par **Marianne Guilbard**.

### 🇪🇸 En resumen

Simulador de entrenamiento para aprender las reglas del juego de cartas valenciano *La Fallera Calavera* jugando contra una IA, con una guía que explica cada regla en el momento adecuado. Disponible en español, francés y valenciano. Basta con abrir `index.html` en un navegador. Proyecto personal creado por **Marianne Guilbard**.
