# ZENVIA Revenue Engine
### Powering ENSO Holistic Wellness · Built by ZENVIA Services

An interactive revenue acceleration dashboard for ZENVIA Services — tracking the 90-day sprint to close the KES 549,456/month revenue gap for ENSO Holistic Wellness, Nairobi.

**Live site:** `https://codeedge-ai.github.io/zenvia-revenue-engine/`

---

## What's Inside

| Tab | What it shows |
|---|---|
| **Revenue Map** | Live SPARK fill-rate calculator + all 5 revenue streams current vs potential |
| **90-Day Sprint** | Week-by-week action plan with KES estimates and skills used |
| **Skills Engine** | Each AURA agent mapped to a monthly KES revenue number |
| **ZENVIA Scale** | 6-month trajectory from KES 35K → KES 185K/month |

---

## Deploy in 5 Steps

### 1. Create the GitHub repo
```bash
# On GitHub: New repo → name it "zenvia-revenue-engine" → Public → Create
```

### 2. Clone and push
```bash
git clone https://github.com/codeedge-ai/zenvia-revenue-engine.git
cd zenvia-revenue-engine

# Copy all project files into this folder, then:
git add .
git commit -m "Initial deploy — ZENVIA Revenue Engine"
git push origin main
```

### 3. Enable GitHub Pages
```
GitHub repo → Settings → Pages
Source: GitHub Actions (NOT "Deploy from a branch")
Save
```

### 4. Watch it deploy
```
GitHub repo → Actions tab
You'll see "Deploy to GitHub Pages" workflow running
Takes ~60 seconds
```

### 5. Visit your live site
```
https://codeedge-ai.github.io/zenvia-revenue-engine/
```

---

## Local Development

```bash
npm install
npm run dev
# → http://localhost:5173
```

---

## Stack

- **React 18** + **Vite 5** — fast build, zero config
- **GitHub Actions** — auto-deploys on every push to `main`
- **GitHub Pages** — free hosting, custom domain ready
- No external dependencies, no API keys needed

---

## Custom Domain (Optional)

To use `dashboard.zenviaservices.com`:
1. Add a `CNAME` file to the repo root containing: `dashboard.zenviaservices.com`
2. In your DNS: add a CNAME record pointing to `codeedge-ai.github.io`
3. In GitHub Pages settings: add your custom domain

---

Built with AURA — Autonomous Unified Response Architecture · ZENVIA Services
