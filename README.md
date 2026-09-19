# 🌾 Harvest Optimizer

A coin maximization tool for a farming/harvest game with fertilizer mechanics.

## 🚀 Live Site
**[Open the app →](https://gogit2194.github.io/Clash-of-Critters-Cozy-Farm/)**

## 🛠 Tools Included

### 🌾 Optimizer
- Assign plants to 6 soil slots per reset
- Enter multiplier per plant
- Set your fertilizer budget
- Auto-recommends the best fert split for **maximum coins** across 5 resets (12hrs each)
- Pure greedy algorithm — no forced minimums

### 🧮 Manual Calculator
- Manually enter plant, multiplier, and fertilizer per soil
- Live coin calculation per plant per reset
- Use to compare against optimizer recommendations

## 📐 Formula
- **Coins** = `floor(in_game_weight × multiplier)`
- **Weight (fert 0–100):** exact in-game values
- **Weight (fert 101–1920):** `W(n) = 5.027 + 15.982 × n^0.4248`
- Validated: fert 67 → 100.36 kg ✓ · fert 1920 → 401.50 kg ✓

## 🌱 Plant Companions
| Plant | Companion |
|---|---|
| 🍌 Banana | 🐒 Monkey |
| 🐉 Dragon Fruit | 🐸 Frog |
| 🥕 Carrot | 🦋 Moth |
| 🍒 Cherry | 🦇 Bat |
| 🎋 Bamboo | 🐼 Panda |

## 📦 Files
- `index.html` — The full app (works offline, no build step needed)
- `README.md` — This file

## 🔧 How to Host on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`
