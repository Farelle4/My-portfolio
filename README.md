# Portfolio — Farelle Tchoukwe Yonzue

Personal portfolio website built with vanilla HTML, CSS and JavaScript. No framework, no build step.

**Live:** [to be added after deployment]

---

## Tech stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styles | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Inter, JetBrains Mono (CDN) |
| i18n | Custom lightweight translation system (`translation.js`) |

---

## Run locally

Open `index.html` directly in a browser — no install needed.

---

## Project structure

```
Portfolio_Farelle/
├── index.html        # Structure and all page content
├── style.css         # Styles, dark theme, responsive layout
├── main.js           # Scroll effects, nav highlight, hamburger menu, reveal animations
├── translation.js           # Translations (EN / DE / FR) + language switcher logic
├── Farelle.jpg       # Profile photo
└── README.md
```

---

## Sections

| # | Section | Anchor |
|---|---------|--------|
| 1 | Hero | `#hero` |
| 2 | About | `#about` |
| 3 | Education | `#ausbildung` |
| 4 | Work Experience | `#experience` |
| 5 | Projects | `#projects` |
| 6 | Volunteering | `#volunteer` |
| 7 | Skills | `#skills` |
| 8 | Contact | `#contact` |

---

## Multilingual support

The site supports **English** (default), **German** and **French**.  
Language is switched via the `DE / EN / FR` buttons in the navbar and persisted in `localStorage`.

To add a new language, add a new key block in `i18n.js` and a new `<button class="lang-btn" data-lang="xx">` in `index.html`.

---

## Deploy

The site is fully static — no server-side logic required.

| **Vercel** | Import the repository on [vercel.com](https://vercel.com) |

---

## Contact

Farelle Tchoukwe Yonzue · [tchoukwefarelle@gmail.com](mailto:tchoukwefarelle@gmail.com) · [LinkedIn](https://www.linkedin.com/in/farelle-tchoukwe-yonzue-931889391/)
