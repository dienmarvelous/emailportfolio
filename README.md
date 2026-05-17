# Email Copywriting Portfolio

A portfolio site showcasing email copywriting campaigns across multiple industries — built with vanilla HTML, CSS, and JavaScript. Features an interactive email viewer with live campaign switching and fully rendered email previews.

---

## Live Preview

> Deploy to [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), or [Vercel](https://vercel.com/) for a shareable link. Open `index.html` locally in any browser to preview immediately — no setup required.

---

## About the Project

This is the source for a single-page email copywriting portfolio designed to present campaign samples in a clean, client-ready format.

Each featured campaign includes a full multi-email sequence rendered inside a realistic email viewer — complete with subject lines, sender details, and brand-accurate typography and layout. Campaigns span different industries, tones, and email types, demonstrating range across brand voice, audience psychology, and conversion strategy.

---

## Featured Campaigns

### 1. ChainClass Academy — Tutorial Series
**Type:** Educational onboarding sequence · 3 emails  
**Industry:** Crypto / Fintech  
**Brief:** Break down complex blockchain concepts (blockchain fundamentals, wallets & private keys, DeFi) into digestible lessons without losing technical credibility. Voice: precise, empowering, jargon-light.

### 2. Maison Velours — Welcome Sequence
**Type:** Welcome & conversion sequence · 3 emails  
**Industry:** Quiet luxury fashion  
**Brief:** Introduce a refined brand world, share a founder story, and nudge new subscribers toward a first purchase — without discounts or artificial urgency. Voice: editorial, unhurried, refined.

### 3. Petit Four Bakehouse — Nurture Sequence
**Type:** Brand story to first-order nurture · 3 emails  
**Industry:** Food & beverage / E-commerce  
**Brief:** Take subscribers from origin story to first-order incentive using sensory-rich storytelling that makes readers taste the product before they order it. Voice: warm, specific, inviting.

---

## Site Features

- **Interactive campaign selector** — click any campaign card to load its email sequence into the viewer
- **Email tab navigation** — switch between individual emails within a sequence
- **In-sequence button navigation** — e.g. "Continue to Lesson 2" loads the next email directly
- **Realistic email chrome** — subject lines, sender addresses, and browser-style UI per email
- **Brand-differentiated rendering** — each campaign has its own distinct typography, color palette, and layout
- **Responsive layout** — works on desktop and mobile
- **No external dependencies** — vanilla HTML, CSS, and JavaScript only (Google Fonts for typography)

---

## File Structure

```
/
├── index.html        # The entire portfolio — single self-contained file
└── README.md         # This file
```

All styles, scripts, and markup live in `index.html`. No build step, no bundler, no framework.

---

## How to Use

**View locally:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
open index.html        # macOS
# or
start index.html       # Windows
```

**Deploy to GitHub Pages:**
1. Go to your repository → Settings → Pages
2. Under Source, select `main` branch and `/ (root)`
3. Save — your portfolio will be live at `https://your-username.github.io/your-repo-name`

---

## Customisation

**To update contact and CTA buttons:** Search for `Send me a brief` and `View full portfolio` in `index.html` and add your real links or email address.

**To add a new campaign:** Duplicate an existing campaign card in the HTML, update the copy and colour variables, and add the corresponding email blocks inside the viewer section. The JavaScript `campaigns` object at the bottom of the file controls tab labels — add your new campaign there too.

**To update the About section:** Find the `about-section` div and edit the copy and service items directly.

---

## Built With

- HTML5
- CSS3 (custom properties, CSS Grid, Flexbox)
- Vanilla JavaScript
- [Google Fonts](https://fonts.google.com/) — DM Serif Display, DM Sans, Space Mono, Cormorant Garamond, Playfair Display, Lato

---

## License

This repository is shared for portfolio and demonstration purposes. The copy, campaign concepts, and brand names featured are original creative work. Please do not reproduce or redistribute the written content without permission.

---

*Built to share, not to hoard.*
