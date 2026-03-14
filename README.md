# 📱 Satish — iOS Developer Portfolio
> Senior iOS Engineer · 7+ Years · 15+ Apps · 9M+ Downloads · 6 Countries

🌐 **Live:** [satish24sp.github.io](https://satish24sp.github.io)

---

## 🗂️ Repository Structure

```
Satish24sp.github.io/
├── index.html                  # Main portfolio page
├── Resource/
│   ├── Satish_iOS_resume.pdf   # Downloadable resume
│   ├── preview.png             # OG / social preview image
│   └── AppsImage/              # Local app icons (.webp)
│       ├── paytm.webp
│       ├── myLiberty.webp
│       ├── mimas.webp
│       ├── ooredooMaldives.webp
│       ├── glocafe.webp
│       ├── payplus.webp
│       ├── sanskarTV.webp
│       ├── dams.webp
│       ├── rahulIAS.webp
│       ├── utkarsh.webp
│       ├── nextIAS.webp
│       ├── madeEasy.webp
│       ├── learnForward.webp
│       ├── ezbitex.webp
│       └── cerberex.webp
```

---

## ✨ Features

- ⚡ **Pure HTML / CSS / JavaScript** — zero frameworks, zero dependencies
- 📱 **Fully responsive** — mobile-first with hamburger nav
- 🎨 **Apple-inspired design** — DM Sans, iOS blue `#007AFF`, glassmorphism nav
- 🖼️ **Local app icons** — loaded from `Resource/AppsImage/` (no API calls)
- ⭐ **Half-star ratings** — CSS gradient trick for fractional star display
- 🔍 **SEO optimised** — meta description, OpenGraph, Twitter Card, JSON-LD schema, canonical tag
- 🔗 **Share speed-dial** — 3-action FAB (Share · Copy Link · Download Resume)
- ⬆️ **Scroll-to-top** — appears after 300px scroll, smooth return
- 🍔 **Hamburger menu** — full mobile nav dropdown with all links
- 💤 **Performance** — no external JS libraries, passive scroll listeners

---

## 🗺️ Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, title, animated badge, CTA buttons |
| **Stats Bar** | 7+ yrs · 15+ apps · 9M+ downloads · 6 countries |
| **Experience** | 3 companies with bullet points and ratings |
| **App Portfolio** | 15 cards with icons, ratings, download counts, App Store links |
| **Skills & Stack** | 12 skill cards across languages, architecture, security, tooling |
| **Achievements** | 9 metric cards with real production numbers |
| **Articles** | 6 Medium articles with tags and links |
| **Contact** | Email, LinkedIn, GitHub, Medium — dark gradient section |

---

## 🚀 Deployment

Hosted via **GitHub Pages** — auto-deploys on every push to `main`.

```bash
# Clone
git clone https://github.com/Satish24sp/Satish24sp.github.io.git
cd Satish24sp.github.io

# Make changes to index.html, then push
git add .
git commit -m "Update portfolio"
git push origin main
```

GitHub Pages deploys within **1–2 minutes** after pushing.

---

## 🔄 Updating App Icons

Place `.webp` files in `Resource/AppsImage/` matching the filenames in the `APPS` array inside `index.html`:

```
paytm.webp · myLiberty.webp · mimas.webp · ooredooMaldives.webp
glocafe.webp · payplus.webp · sanskarTV.webp · dams.webp
rahulIAS.webp · utkarsh.webp · nextIAS.webp · madeEasy.webp
learnForward.webp · ezbitex.webp · cerberex.webp
```

Icons load automatically. If a file is missing, the app name's first letter is shown as a placeholder.

---

## 📄 Updating Resume

Replace `Resource/Satish_iOS_resume.pdf` with the new version — keep the exact filename. The **Download Resume** button and share speed-dial both reference this path.

---

## 🔧 Updating App Data

All app data lives in the `APPS` array in `index.html` (around line 548). Each entry looks like:

```js
{
  id:     'myliberty',
  img:    'myLiberty.webp',          // filename in Resource/AppsImage/
  name:   'My Liberty App',
  client: 'Liberty Puerto Rico',
  cat:    'Telecom',
  catClr: ['#EDF7EE', '#1A8040'],    // [background, text] for category badge
  country:'Puerto Rico 🇵🇷',
  co:     'paytm',                   // filter key: paytm | appsquadz | oodles
  dl:     '523K+ downloads',         // null if unknown
  rating: '4.8',                     // supports half-stars e.g. '3.5'
  rc:     '20K ratings',             // null if unknown
  desc:   'Cable & mobile self-care SuperApp...',
  url:    'https://apps.apple.com/us/app/my-liberty-app/id1637472836'
}
```

---

## 📬 Contact

| | |
|-|-|
| 🌐 Portfolio | [satish24sp.github.io](https://satish24sp.github.io) |
| 💼 LinkedIn | [linkedin.com/in/satish-iosdev](https://linkedin.com/in/satish-iosdev) |
| 📧 Email | [satish24sp@gmail.com](mailto:satish24sp@gmail.com) |
| 🐙 GitHub | [github.com/Satish24sp](https://github.com/Satish24sp) |
| ✍️ Medium | [medium.com/@satish24sp](https://medium.com/@satish24sp) |

---

## 🧰 License
MIT License

---

*Built with ❤️ — Pure HTML · CSS · JavaScript · No frameworks*
