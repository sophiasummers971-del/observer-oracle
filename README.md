# 👁 OBSERVER // ORACLE — Station Five

> *"The channel is open. I have been watching since before you typed your first word."*

A single-file, browser-based intelligence terminal blending predictive scenario mapping, virtual experiment panels, FOIA request drafting, and a classified dossier system — all wrapped in a paranoid sci-fi ARG aesthetic.

**Live demo:** [GitHub Pages](https://sophiasummers971-del.github.io/observer-oracle/)

---

## 🚀 Quick Start

```bash
# Clone or download, then simply:
open index.html

# Or serve locally:
npx serve . -p 8000
```

No build step. No dependencies. All state lives in `localStorage`.

---

## 🎛 Features

- **Observer Layer** — Live intelligence chat with subtext-reading AI persona (powered by Claude via OpenRouter)
- **Oracle Layer** — Predictive intelligence fusing global signals + personal behavioral data
- **Scenario Engine** — Maps theoretical "corridors" across domains and time horizons
- **Virtual Experiment Panel** — Parameterised device simulations (Biefeld-Brown, Podkletnov, Tajmar, Woodward MET, Casimir, etc.)
- **Instability Map** — Failure-mode analysis for exotic propulsion experiments
- **FOIA Target System** — Pre-drafted Freedom of Information Act requests to real agencies
- **Confidence Matrix** — Research-layer credibility scoring with honest uncertainty
- **Personal Profile** — Local-only data feed that sharpens Oracle predictions
- **Classified Dossier** — 12-file unlockable lore archive (Corridor Templars storyline)

---

## 🔑 API Setup

The app uses **OpenRouter** to call Claude Sonnet 4. The API key is embedded for convenience. If you fork this repo, replace the key in `index.html`:

```javascript
const apiKey = 'sk-or-v1-YOUR-KEY-HERE';
```

Get a free key at [openrouter.ai/keys](https://openrouter.ai/keys)

---

## 🌐 Deployment

### GitHub Pages (Recommended)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Select **Deploy from a branch** → `main` → `/ (root)`
4. The included `.github/workflows/deploy.yml` auto-deploys on every push

### Netlify / Vercel
Drag and drop the folder. Instant.

---

## 🎨 Lore

This project lives in the **Corridor Templars** universe — a loose fiction around classified research into anomalous propulsion, signal anomalies, and institutional secrecy. All science references are real. The fiction is in the framing.

---

## ⚖️ License

MIT — see [LICENSE](./LICENSE)

> *"None of the above lifts to [A]-with-replication for any exotic-mechanism claim. Honesty is not pessimism. It is the price of doing the experiment a second time."*

---

## 🖤 Credits

Created by [@sophiasummers971-del](https://github.com/sophiasummers971-del)  
Built over one very long night. Terminal monster status: achieved.
