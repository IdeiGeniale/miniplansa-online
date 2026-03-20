# MiniPlansa Online

> A clean, all-in-one planning & design board that lives in a single HTML file. No installs, no servers, no dependencies.

![MiniPlansa Online](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-orange?style=flat-square)
![Languages](https://img.shields.io/badge/languages-EN%20%7C%20RO-blueviolet?style=flat-square)

---

## ✨ Features

### 🎨 Drawing Board
- **Freehand pen** with adjustable stroke size and color
- **Shape tools** — line, rectangle, circle, arrow
- **Text tool** — click anywhere on the canvas to type
- **Eraser** for corrections
- **Sticky notes** — draggable, resizable, color-coded
- **Image upload** — drag and reposition images on the board
- **Undo** support (up to 20 steps)
- Per-project board state (each project has its own canvas)

### ✅ Task Board (Kanban)
- Three columns: **To Do**, **In Progress**, **Done**
- **Drag & drop** cards between columns
- Task labels: Feature, Improvement, Design, Research, Bug
- Optional description and due date per task
- Per-project task lists

### 📅 Calendar
- Monthly grid view with navigation
- Click any day to add an event
- Color-coded events (blue, green, orange, purple, red)
- Click an event to view details or delete it

### 💾 Save & Load
- **Auto-save** to `localStorage` on every change — your work persists between sessions
- **Export** your workspace to a `.miniplansa` file
- **Import** a `.miniplansa` file to restore a previous workspace
- Full multi-project support

### 🌐 Language Support
- Toggle between **English** and **Romanian** via the `EN / RO` button in the top bar
- Language preference is saved and restored automatically

---

## 🚀 Getting Started

No build step, no package manager, no server required.

1. **Download** `MiniPlansa Online.html`
2. **Open** it in any modern browser (Chrome, Firefox, Edge, Safari)
3. Start planning

That's it.

---

## 📁 File Structure

MiniPlansa Online is intentionally a **single self-contained file**:

```
MiniPlansa Online.html   ← everything: HTML + CSS + JS, no external files needed
README.md
```

The only external resource loaded is the **DM Sans / DM Mono** font from Google Fonts (requires an internet connection for the first load; falls back to system sans-serif otherwise).

---

## 🗂 Data & Persistence

| Storage | What it holds |
|---|---|
| `localStorage` (`miniplansa_data`) | Projects, tasks, events, board state (auto-saved) |
| `localStorage` (`miniplansa_lang`) | Language preference |
| `.miniplansa` file | Full exported workspace (JSON) |

> **Note:** Board drawings are saved as base64 data URLs inside the workspace. Large or complex drawings may increase file size noticeably.

---

## Supported Devices

1. Android phone/tablet
2. iPhone, iPad or Mac/MacBook
3. PC/Laptop
4. Interactive Board (ex: Samsung)

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Structure | Vanilla HTML5 |
| Styling | Vanilla CSS3 (CSS variables, Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Drawing | HTML5 Canvas API |
| Fonts | DM Sans + DM Mono (Google Fonts) |
| Storage | `localStorage` + File API |

Zero frameworks. Zero npm packages. Zero build tools.

---

## 🌍 Localization

The app supports English and Romanian out of the box. All UI strings — labels, tooltips, modal titles, column names, toasts, and confirm dialogs — are translated.

To switch language, click the flag button (`🇬🇧 EN` / `🇷🇴 RO`) in the top-right area of the toolbar.

---

## 📸 Screenshots

> *(Add your own screenshots here)*

| Board | Tasks | Calendar |
|---|---|---|
| *(screenshot)* | *(screenshot)* | *(screenshot)* |

---

## 🤝 Contributing

Contributions are welcome! Since the whole app is one file, just edit `MiniPlansa Online.html` directly.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push and open a pull request

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<p align="center">Made with ☕ and vanilla JS &nbsp;·&nbsp; <strong>TRY. YOUR. ABSOLUTE. HARDEST.</strong></p>
