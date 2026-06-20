# 🌷 Sk. Arif Birthday Surprise Website

A 2-page interactive birthday surprise site. No build tools, no server —
just open `index.html` in a browser.

## 📁 Folder Structure

```
sk-arif-birthday/
├── index.html        ← Page 1 (flat-lay coffee + envelope scene)
├── page2.html         ← Page 2 (beach birthday surprise scene)
├── images/
│   ├── photo1.jpg     ← ✅ already here (Page 1 background)
│   ├── photo2.jpg      ← ✅ already here (Page 2 background)
│   ├── scratch1.jpg    ← ⬜ still needed (scratch card #1 reveal photo)
│   ├── scratch2.jpg    ← ⬜ still needed (scratch card #2 reveal photo)
│   └── scratch3.jpg    ← ⬜ still needed (scratch card #3 reveal photo)
└── audio/
    ├── voice.mp3       ← ⬜ still needed (voice message)
    └── song.mp3        ← ⬜ still needed (CD / birthday song)
```

## 🎮 Interactions

### Page 1 (index.html)
| Element | Action |
|---|---|
| ☕ Coffee cup | Click repeatedly → coffee drains → "All done!" after 5 sips |
| ✉️ Envelope | Click → petal loading screen → goes to Page 2 |

### Page 2 (page2.html)
| Element | Action |
|---|---|
| 📜 Letter | Click → letter opens with the birthday message |
| 🎴 Scratch cards (×3) | Click → scratch to reveal `images/scratchN.jpg` (shows a gift-box placeholder until that file exists) |
| 🎤 Voice message | Click → plays `audio/voice.mp3` |
| 💿 CD player | Click → disc spins + plays `audio/song.mp3` |

## ✅ What's done vs. still needed

- Both pages, all animations, and all click interactions are fully wired and working.
- `photo1.jpg` and `photo2.jpg` are in place.
- Still missing, purely as assets (the code already looks for them — just drop them in):
  - `images/scratch1.jpg`, `scratch2.jpg`, `scratch3.jpg`
  - `audio/voice.mp3`, `audio/song.mp3`
- Nothing breaks if these are missing — cards show a placeholder, audio buttons just stay silent until the files are added.

## 🚀 How to open

Double-click `index.html`. No server needed.
