# 🗣️ BanterBase

> A dark-mode random joke generator for Dark Jokes, Dad Jokes, Pick-up Lines, and Long Jokes. Built for GitHub Pages.

BanterBase is a simple, elegant web app that serves random banter from four categories at the click of a button. No database, no backend — just JSON files and vanilla HTML/CSS/JS.

🔗 **Live demo:** [https://colourfulcarnage.github.io/banterbase](https://colourfulcarnage.github.io/banterbase/)

---

## ✨ Features

- 🌙 **Dark mode** UI with orange & white accents
- 📱 **Fully responsive** — works on PC, tablet, and phone
- 🎲 **Truly random** — each click pulls a fresh joke (repeats allowed, no session tracking)
- 🔘 **Large, tappable buttons** — thumb-friendly on mobile
- 📜 **Scrollable long jokes** — never cut off
- 🔄 **Back button** — clears the joke and returns to category menu
- ✏️ **Easy to update** — add or edit jokes without touching HTML/CSS

---

## 🗂️ Category JSON Files

All jokes are stored in the `data/` folder as separate JSON files:

| File | Category |
|------|----------|
| `data/dark.json` | Dark Jokes |
| `data/dad.json` | Dad Jokes |
| `data/pickup.json` | Pick-up Lines |
| `data/long.json` | Long Jokes |

Each file follows this simple format:

```json
[
  "Your first joke here.",
  "Your second joke here.",
  "Your third joke here."
]
