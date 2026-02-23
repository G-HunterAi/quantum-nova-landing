# Quantum Nova — Pre-Launch Landing Page

Pre-launch waitlist capture for the Quantum Nova multi-asset decision intelligence platform.

## Live
🔗 https://g-hunterai.github.io/quantum-nova-landing/

## Features
- Hero with email waitlist capture
- Live ticker bar (animated, demo data)
- Stats band (instruments, metrics)
- Problem statement
- Terminal preview (realistic QN v5.1 output)
- Feature grid (6 cards)
- Silo architecture explainer
- Step-by-step how it works
- CTA section
- Mobile responsive

## Setup

### Deploy to GitHub Pages
```bash
gh repo create quantum-nova-landing --public --source=. --remote=origin --push
# Then enable Pages via: Settings → Pages → Deploy from branch → main → / (root)
```

### Wire Formspree (email capture)
1. Create free account at formspree.io
2. Create a new form
3. Replace `REPLACE_WITH_ENDPOINT` in `index.html` with your form ID
4. Commit and push

## Stack
- Pure HTML/CSS/JS (zero dependencies)
- Google Fonts: Inter, Playfair Display, JetBrains Mono
- No build step needed
- GitHub Pages ready
