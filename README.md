# Belkal Kennedy Sheva — Personal Portfolio

A clean, dark-themed personal portfolio website built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks, no dependencies.

---

## 🔗 Live Preview

Open `kennedy_portfolio.html` directly in any modern browser. No server or build step required.

---

## 📁 Project Structure

```
portfolio/
├── kennedy_portfolio.html   # Single-file portfolio (HTML + CSS + JS)
└── README.md                # This file
```

Everything lives in one self-contained HTML file — styles and scripts are inlined for zero-dependency portability.

---

## ✨ Features

- **Responsive layout** — adapts cleanly to desktop and mobile viewports
- **Smooth scroll reveal** — sections animate in as you scroll via IntersectionObserver
- **Active nav highlighting** — navigation links highlight based on current scroll position
- **Dark aesthetic** — deep dark background (`#0b0c10`) with cyan and purple accent glows
- **Noise texture overlay** — subtle SVG fractal noise adds depth to the background
- **Hero stats card** — at-a-glance summary of certifications, training, and languages
- **Skills grid** — 8 skill cards with hover glow effects
- **Certifications section** — color-coded obtained vs in-progress badges
- **Projects section** — 4 project cards with tech tags
- **Contact section** — email, phone, and LinkedIn links

---

## 🎨 Design Tokens

| Token | Value | Usage |
|---|---|---|
| `--bg` | `#0b0c10` | Page background |
| `--card` | `#161820` | Card surfaces |
| `--accent` | `#00e5ff` | Cyan highlight |
| `--accent2` | `#7c3aed` | Purple highlight |
| `--gold` | `#f5a623` | In-progress badges |
| `--text` | `#e8eaf0` | Body text |
| `--muted` | `#7a7f94` | Secondary text |

Fonts: **Syne** (headings) and **DM Sans** (body) — loaded from Google Fonts.

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `kennedy_portfolio.html` in your browser
3. No installation, build tools, or internet connection required (except for Google Fonts)

To host it online, upload the HTML file to any static hosting service:

- [GitHub Pages](https://pages.github.com/)
- [Netlify Drop](https://app.netlify.com/drop)
- [Vercel](https://vercel.com/)

---

## 📋 Sections

| Section | ID | Description |
|---|---|---|
| Hero | — | Name, tagline, CTA buttons, stats card |
| About | `#about` | Bio, personal details, language proficiency |
| Skills | `#skills` | 8 technical skill cards |
| Certifications | `#certifications` | Obtained and in-progress credentials |
| Projects | `#projects` | 4 portfolio projects with tech tags |
| Contact | `#contact` | Email, phone, LinkedIn |

---

## 🛠️ Customisation

All content is in plain HTML — easy to edit:

- **Name / bio** — update text inside the `<h1>` and `<p>` tags in the hero and about sections
- **Projects** — edit the `.project-card` divs in `#projects`
- **Skills** — edit `.skill-card` divs in `#skills`
- **Colors** — change CSS variables inside `:root {}` at the top of `<style>`
- **Contact links** — update `href` values in the `#contact` section

---

## 📄 License

This portfolio is personal work by **Belkal Kennedy Sheva**. Feel free to use the structure as inspiration, but please don't copy the personal content (bio, projects, certifications) as your own.

---

*Built with HTML, CSS & JavaScript · Douala, Cameroon · 2026*
