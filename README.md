# Dhanush Kumar S V — Portfolio

A three-identity portfolio for a Process Engineer:

**Top-corner switcher — two professional modes:**

| Theme | Vibe |
|-------|------|
| ☀️ **Light** (default) | Crisp white with hot-rod red & gold accents — Playfair serif, blueprint grid |
| 🌙 **Noir** | Midnight black — champagne-gold & violet aurora, whisper grid |

**Identity vault — six hidden character themes at the bottom of the page** (click "🎭 Hidden identities").
Every one has a unique palette, font, hero backdrop **and a special skill**:

| Theme | Vibe | Special skill |
|-------|------|---------------|
| 🕷️ **Spider-Man** | Red & white, diagonal panel, white spider emblem | Click anywhere → a web bursts at that spot |
| 🦇 **Batman** | Near-black, bat-yellow, skyline & bat-signal | "🔦 Lights out" button → darkness, a spotlight follows your cursor |
| 🛡️ **Captain America** | Steel blue, flag red/navy, spinning shield | Click anywhere → shield rings ripple out |
| 🌾 **Vinland Saga** | Green meadow & wheat amber, rolling hills | Click anywhere → wheat grains drift down |
| 🏴‍☠️ **Luffy** | Ocean blues, waves, floating straw hat | "🌊 Gravity OFF" button → the sea rises, everything bobs, and the page sails itself section by section |
| 🍥 **Naruto** | Orange ninja energy, Konoha swirl, action rays | Click anywhere → a chakra spiral spins |

The site always opens in **Light professional**. The chatbot can switch themes by name
("show me batman") and opens the vault if you ask about *secrets*.

## Features
- **Theme switcher** in the top-right corner — every color, font, backdrop and even the chatbot's personality changes (Alfred answers in Gotham mode). Each theme has its own signature hero backdrop — no shared effects.
- **Resume section** — downloads for PDF and Word (`assets/`).
- **Resume chatbot** — 100% client-side Q&A about education, skills, research, internships, publications, contact. No API keys, works offline.
- **Fully responsive** — desktop, tablet and mobile (hamburger nav).
- Award-level details: branded preloader, custom cursor (desktop), scrolling skills marquee,
  film-grain texture, blur-rise reveals, magnetic hero buttons, 3D card tilt, hero parallax,
  scroll progress bar, typewriter hero, animated stat counters. Respects `prefers-reduced-motion`.

## Run locally
Just open `index.html` in a browser, or serve it:

```
python -m http.server 8087
```

then visit http://localhost:8087

## Deploy (free options)
- **GitHub Pages**: push this folder to a repo → Settings → Pages → deploy from branch.
- **Netlify / Vercel**: drag-and-drop the folder — it's a fully static site, no build step.

## Updating the resume
Replace `assets/Dhanush_Kumar_Resume.pdf` / `.docx`, and edit `js/resume-data.js`
so the chatbot's answers stay in sync.
