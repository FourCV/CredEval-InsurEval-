# CredEval / InsurEval — Investor Pitch Deck

> **Live Site →** [https://YOUR-USERNAME.github.io/credeval-pitch](https://YOUR-USERNAME.github.io/credeval-pitch)

---

## About

Interactive investor pitch deck for **CredEval** and **InsurEval** — a dual-platform commercial real estate intelligence company democratizing CRE valuation for the 60% of the market left behind by traditional appraisal services.

### What This Deck Covers

| Slide | Topic |
|---|---|
| 01 | Cover — Platform Overview |
| 02 | Market Problem — The 60% Gap |
| 03 | Solution — Dual Platform Architecture |
| 04 | Core Product — The IQ Report (~$350) |
| 05 | Value Propositions — All Stakeholders |
| 06 | Revenue Model — Transactional + Subscription |
| 07 | Competitive Moat — 4 Defensibility Layers |
| 08 | Go-To-Market — Three-Channel Flywheel |
| 09 | The Ask — Investment Opportunity |

---

## Navigation

| Input | Action |
|---|---|
| `→` / `↓` Arrow Key | Next slide |
| `←` / `↑` Arrow Key | Previous slide |
| Click nav dots | Jump to any slide |
| Swipe left/right | Next / previous (mobile) |

---

## Repository Structure

```
credeval-pitch/
├── index.html          # Full pitch deck (single file, self-contained)
├── 404.html            # Redirect fallback for GitHub Pages
├── .nojekyll           # Disables Jekyll so HTML renders correctly
├── .github/
│   └── workflows/
│       └── deploy.yml  # Auto-deploy to GitHub Pages on push to main
└── README.md           # This file
```

---

## Deployment

This repo auto-deploys to GitHub Pages via GitHub Actions on every push to `main`.

### First-Time Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set **Source** to `GitHub Actions`
4. Push any change to `main` — deployment triggers automatically
5. Your deck is live at `https://YOUR-USERNAME.github.io/REPO-NAME`

### Manual Deploy (No Actions)

1. Go to **Settings → Pages**
2. Set **Source** to `Deploy from a branch`
3. Select `main` branch → `/ (root)`
4. Save — GitHub Pages builds in ~60 seconds

---

## Embed (SharePoint / Notion / Any CMS)

```html
<iframe
  src="https://YOUR-USERNAME.github.io/credeval-pitch"
  width="100%"
  height="100vh"
  style="border:none; width:100%; height:100vh; min-height:900px; display:block;"
  allowfullscreen="true"
  frameborder="0"
  scrolling="no">
</iframe>
```

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript — zero dependencies, zero build step
- Google Fonts (Playfair Display · DM Mono · DM Sans)
- Fully self-contained in `index.html`

---

## Platforms

Built with prompts compatible with:
- **Lovable** — Full-stack React/TypeScript rebuild
- **Gravity** — No-code interface builder
- **Gamma.app** — AI presentation generator

---

*CredEval / InsurEval · Benjamin Greenberg, CEO & Founder · 2026*
