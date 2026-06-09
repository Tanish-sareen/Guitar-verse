<div align="center">

# 🎸 GuitarVerse Pro
### *Studio Edition — v3.0*

**A fully interactive, browser-based guitar simulator with real audio synthesis, chord library, chromatic tuner, and metronome. No downloads. No plugins. Just open and play.**

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FJS-f0c040?style=for-the-badge&logo=html5&logoColor=black)](https://github.com/tanishsareen/guitarverse-pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-d4a017?style=for-the-badge)](LICENSE)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-20c060?style=for-the-badge)]()
[![Offline Ready](https://img.shields.io/badge/Works-Offline-8b5cf6?style=for-the-badge)]()

<br>

*Developed with ❤️ by **Tanish Sareen***

</div>

---

## ✨ Features

### 🎼 10 Unique Instruments
| Instrument | Tuning | Genre |
|---|---|---|
| 🎸 Acoustic Guitar | E A D G B E | Folk, Country, Blues |
| ⚡ Electric Guitar | E A D G B E | Rock, Metal, Blues |
| 🎵 Classical Guitar | E A D G B E | Classical, Flamenco |
| 🎚 Bass Guitar | E A D G — — | Funk, Rock, Jazz |
| ✨ 12-String Guitar | E A D G B E | Folk-Rock, Indie |
| 💃 Flamenco Guitar | E A D G B E | Flamenco, Spanish |
| 🔩 Resonator Guitar | E A D G B E | Bluegrass, Delta Blues |
| 🌊 Slide Guitar | D G D G B D | Blues, Slide, Country |
| 🌺 Ukulele | G C E A — — | Hawaiian, Pop |
| 🪕 5-String Banjo | G D G B D | Bluegrass, Old-Time |

### 🎛 Real Audio Engine (Web Audio API)
- **Karplus-Strong** string synthesis for realistic plucked string sound
- **Live effects chain** — Reverb · Delay · Tone · Drive · Chorus · Vibrato · Sustain
- **Pitch shifting** — ±12 semitones
- **Waveform visualizer** + spectrum analyzer

### 🎹 Interactive Fretboard
- Full **15-fret** playable fretboard
- Click any fret to play individual notes
- **Chord highlighting** — see where fingers go
- **Scale overlay** — visualize scale patterns
- Left-hand / right-hand mirror mode

### 📚 Chord & Scale Library
- Major, Minor, 7th, Sus2, Sus4, Maj7, Min7, Dim, Aug chords
- Multiple voicings per chord
- Scale patterns: Major, Minor, Pentatonic, Blues, Dorian, Mixolydian

### 🎯 Chromatic Tuner
- Real-time microphone-based pitch detection
- Autocorrelation algorithm
- Visual needle with cents deviation display
- Supports all instrument tunings

### ⏱ Metronome
- BPM range: 40–240
- Time signatures: 2/4 · 3/4 · 4/4 · 6/8
- Visual beat indicators
- Audio accent on downbeat

### ⌨️ Keyboard Shortcuts
| Key | Action |
|---|---|
| `A S D F G H` | Pluck strings 1–6 |
| `Q W E R T Y U I` | Play chords (C G Am Em Dm A E F) |
| `Space` | Mute all strings |

---

## 🚀 Getting Started

### Option 1 — Just open it
```bash
# No build step needed — it's a single HTML file
open index.html
```

### Option 2 — Serve locally
```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .

# Then open http://localhost:8080
```

### Option 3 — Deploy to GitHub Pages
See the [GitHub Pages deployment section](#-deploy-to-github-pages) below.

---

## 📁 Project Structure

```
guitarverse-pro/
│
└── index.html        # Everything — HTML + CSS + JS in one file
                      # (~1000 lines, zero dependencies)
```

---

## 🌐 Deploy to GitHub Pages

1. Go to your repository → **Settings**
2. Scroll to **Pages** → Source: `Deploy from a branch`
3. Branch: `main` → Folder: `/ (root)` → **Save**
4. Your site will be live at `https://yourusername.github.io/guitarverse-pro`

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| **Web Audio API** | Sound synthesis, effects, tuner |
| **Canvas API** | Waveform + spectrum visualizer |
| **Vanilla JS** | All logic, zero frameworks |
| **CSS Variables** | Theming and dark UI |
| **Google Fonts** | Bebas Neue, Rajdhani, Playfair Display |

---

## 📸 Screenshots

> *Open `index.html` in your browser to experience it live.*

The app features:
- Deep dark gold-accented UI (`#08070C` background, `#D4A017` gold)
- SVG guitar illustrations per instrument
- Responsive fretboard that adapts to screen size
- Animated string vibration on pluck

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

1. Fork the repo
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with 🎸 by **Tanish Sareen**

*If you find this useful, give it a ⭐ on GitHub!*

</div>
