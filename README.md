# 🪷 NayePankh Foundation — Redesigned Website

A modern, interactive redesign of [NayePankh Foundation](https://nayepankh.com/) built as a web development internship project.

## ✨ Features

- **🪙 Piggy Bank Animation** — Click the animated piggy to "donate ₹1", hear a coin sound (Web Audio API), see coins drop, and confetti bursts. Milestone toasts at ₹10, ₹25, ₹50, ₹100.
- **🪷 Clickable Logo → Story Modal** — Opens an illustrated story of how "NayePankh" got its name, the founding incident, and a founder card for Prashant Shukla.
- **🩸 Menstrual Awareness Section** — Menstruation-themed design (crimson × dusty rose × parchment). Includes a myth-vs-fact panel and visual menstrual cycle explainer.
- **📊 Animated Impact Counters** — Numbers count up when scrolled into view.
- **📜 Scrolling Marquee Banner** — Period-awareness messaging.
- **📋 Volunteer Form** — With a 3-step onboarding explainer.
- **💳 Donate CTA** — Quick-select amounts linking to the live donation page.
- **📱 Fully Responsive** — Mobile, tablet, and desktop.

## 🚀 Deploy to GitHub Pages

### Option A — Upload via GitHub.com

1. Create a new repository (e.g. `nayepankh-website`)
2. Click **Add file → Upload files** and upload `index.html`
3. Commit to `main`
4. Go to **Settings → Pages → Source → Deploy from branch → main / root**
5. Click **Save** — live in ~60 seconds at `https://YOUR_USERNAME.github.io/nayepankh-website/`

### Option B — Git CLI

```bash
git init
git add index.html README.md
git commit -m "feat: NayePankh interactive redesign"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nayepankh-website.git
git push -u origin main
```
Then enable Pages in repo Settings.

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Custom properties, Grid, Flexbox, animations |
| Vanilla JavaScript | Piggy bank, modal, counters, audio |
| Web Audio API | Coin sound (zero external files) |
| Google Fonts | Playfair Display + DM Sans + DM Mono |

## 🎨 Design Palette

| Name | Hex | Usage |
|---|---|---|
| Crimson | `#C0392B` | Primary / CTAs |
| Rose | `#E8647A` | Accents |
| Mauve | `#9B4D62` | Secondary accents |
| Parchment | `#FDF5EE` | Background |
| Blush | `#FEE8EC` | Piggy hero background |

---
Made with 🌸 for NayePankh Foundation internship application
