# CLAUDE.md — Services Avicoles Grondines Associés (SAGA Conseils)

This file is the primary reference for Claude when working on this project.
Read it at the start of every session before making any changes.

## Project Overview

**Site:** Services Avicoles Grondines Associés (SAGA Conseils)
**Live URL:** https://sagaconseils.ca/
**Language:** French (site content), French and English (communication with user)

A professional presentation and lead-generation website for a poultry services company in Quebec. The site serves as:
- A showcase for expert services in the poultry industry (aviculture)
- A booking/contact funnel powered by **Formspree**
- A library of expert articles on the poultry industry (`ressources.html`)

## File Structure

```
index.html        — Main page (hero, services, team, contact)
ressources.html   — Expert articles, written manually in HTML
politique.html    — Privacy/legal policy page
fonts/            — Sora variable font (woff2)
logos/            — Logo assets
videos/           — Video assets
CNAME             — Points to sagaconseils.ca
```

## Tech Stack

- Pure HTML + CSS + vanilla JavaScript (no build tools, no frameworks)
- Custom font: **Sora** (variable, self-hosted)
- Forms: **Formspree** (already integrated — do not replace or alter form endpoints)
- Hosting: GitHub Pages with custom domain
- Articles: written manually in HTML, enhanced with Claude

## How to Work With the User

### Before making any changes
Always show the user what you plan to change and wait for explicit approval before editing files.
Never commit or push unless the user says "commit and push" or equivalent.

### Commits
- Commit messages: **short and direct** (e.g., `améliore section héros`, `ajoute article ressources`)
- No conventional commit prefixes (`feat:`, `fix:`, etc.)
- Language: French or English, both are fine

### Golden rule — preserve existing work
- Never break or remove modifications already in place
- If a change risks affecting an existing feature or section, **fix the impact before presenting**
- The goal is that the site is never in a worse state than before a change

## Key Design Decisions to Respect

- Color palette: deep navy `#0d2b6b`, blue `#1565c0`, light blue `#90caf9`, white `#ffffff`
- Font: Sora (variable weight, self-hosted in `fonts/`)
- 3D ring animation in the hero section — treat with care, it is intentional and complex
- Glassmorphism-style cards: `rgba(240,246,255,0.92)` background, `#c8dcf5` border
- Animated gradient on logo and CTA button (`btnSpotlight`, `logoSpotlight` keyframes)
- All scroll animations use IntersectionObserver — do not remove

## Working Solo

This project has a single developer/owner. There is no team, no branching strategy required.
Work directly on `main`.
