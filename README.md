# Mon-tableau-de-bord-Life-os
> A private life dashboard that tracks every dimension of who you are — financially, emotionally, socially, and creatively — over time.

**[→ Open Life OS](https://yourusername.github.io/life-os/)** &nbsp;·&nbsp; No account. No server. No tracking. Just you.

---

## What is this?

Most apps track one thing. Life OS tracks *you*.

It is a single HTML file you can open in any browser — or publish on GitHub Pages — that works as a personal operating system for your life. Every module captures a different dimension: your money, your people, your milestones, your mood, your identity, and your letters to the future.

Think of it as something richer than a journal, more personal than a spreadsheet, and more honest than social media. The data never leaves your device.

---

## Modules

### 💰 Financial Tracker
Log monthly income and expenses in FCFA, categorized by source (job, freelance, side hustle, gift). Track savings goals and watch your financial independence grow over time. Includes a memory vault for your first salary, worst decision, and smartest investment.

### 🤝 Relationship Tracker
A reflection tool — not surveillance. Log the people in your circle with their type, the energy they bring, how often you connect, and the last meaningful moment you shared. Notice which relationships grow, which fade, and which drain you.

### 📍 Life Timeline
Record the moments that changed you. Every major event — a new job, a move, a heartbreak, a breakthrough — logged with a date, category, and your personal reflection. Over time you see your life as a story unfolding.

### 🧠 Emotional Check-ins
Monthly snapshots of your inner world. Rate your mood from 1 to 10, log your biggest challenge, something you learned, and something you are proud of. Watch your mindset evolve across the years.

### ✨ Identity & Style
A time-stamped snapshot of who you are *right now* — your aesthetic, music taste, hobbies, technologies you are learning, and what inspires you. Your future self will smile reading this.

### 📩 Future Letters
Write sealed letters to yourself with a custom unlock date — 1 year, 5 years, 10 years from now. Letters stay locked until their date arrives. When they open, you read them alongside the real data of your life at the time you wrote them.

---

## Features

- **100% private** — everything is stored in your browser's localStorage. No account, no server, no cloud, no tracking
- **Zero dependencies** — one single `.html` file. No npm, no build step, no internet required after the first load
- **Export & Import** — download all your data as a `.json` backup file at any time. Import it on any device to restore everything instantly
- **Danger zone** — erase all data with a double-confirmed prompt if you ever need a clean slate
- **Responsive** — works on desktop and mobile
- **Beautiful by design** — built with a warm, editorial aesthetic using Fraunces serif and DM Sans, with a signature palette of gold, coral, and plum

---

## Getting started

### Option A — Just open it locally

1. Download `index.html`
2. Double-click it to open in your browser
3. Start logging your life

That is it. No installation needed.

### Option B — Publish on GitHub Pages (recommended)

Publishing gives you a permanent URL you can open from any device.

1. Fork or clone this repository
2. Make sure the file is named `index.html` at the root
3. Go to **Settings → Pages**
4. Set source to `Deploy from a branch → main → / (root)`
5. Click Save

Your Life OS will be live at `https://yourusername.github.io/life-os/` within about 60 seconds.

---

## Your data

Life OS uses `localStorage` to save your data. This means:

- ✅ Data is private — it only exists in your browser
- ✅ No account or login required
- ✅ Works fully offline
- ⚠️ Clearing your browser data or switching browsers will erase it

**This is why the Export feature matters.** Get in the habit of downloading a backup monthly. Save it somewhere you trust — Google Drive, iCloud, a USB drive. When you need to restore, import the `.json` file and everything comes back instantly.

---

## Backup workflow

```
Add data → Export JSON → Save to Google Drive / iCloud → Done
```

On a new device:

```
Open Life OS → Import JSON → Everything restored
```

---

## Philosophy

This project was born from a simple question: *what if FutureMe.org was just the beginning?*

A letter to your future self means more when it is backed by real data. When you can say: "In March 2026, I earned X, I was closest to these people, my mood was a 6, I was obsessed with this aesthetic, and here is what I wrote to you" — that is not just a letter. That is a life, documented.

Life OS is a personal archive. A private operating system. A gift to the person you are becoming.

---

## Tech stack

| Layer | Choice |
|---|---|
| Framework | Vanilla HTML/CSS/JS — zero dependencies |
| Fonts | [Fraunces](https://fonts.google.com/specimen/Fraunces) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Storage | Browser localStorage |
| Hosting | GitHub Pages |
| Build tool | None |

---

## Roadmap ideas

- [ ] GitHub Gist sync (cross-device without a backend)
- [ ] Supabase integration (full cloud sync with login)
- [ ] Mood chart visualization over time
- [ ] Financial growth chart (income vs expenses over months)
- [ ] PDF export of your full life report
- [ ] Dark mode toggle
- [ ] Multiple profiles (for couples or families)

Pull requests welcome.

---

## License

MIT — do whatever you want with it. This is a personal tool. Make it yours.

---

*Built with intention. Designed to last. Made for the long game.*
