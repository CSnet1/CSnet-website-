# CSnet Website

Static website for [CSnet](https://csnet.net.au) — community service case management software built for the sector, by people who've worked in it.

## Pages

| File | Page | Nav label |
|------|------|-----------|
| `index.html` | Homepage | Home |
| `about.html` | About | About |
| `resources.html` | Security & Data FAQ | Resources |

## Image assets

These image files must sit in the **same root folder** as the HTML files for pages to display correctly.

| File | Used on |
|------|---------|
| `b_corp_logo.png` | Homepage hero, About B Corp section |
| `b_corp_photo.jpg` | About B Corp section background |
| `graphic_bus.jpg` | About — Our Impact bus animation |
| `impact_report.jpg` | About — Impact Report card |

## Stack

Plain HTML + CSS + vanilla JavaScript. No build tools, no dependencies, no frameworks.

Fonts are loaded from Google Fonts:
- **Bricolage Grotesque** SemiCondensed SemiBold — display headings
- **Public Sans** Regular / Medium / SemiBold / Bold — body copy

## Brand

Follows CSnet Brand Guidelines v1.0 (2025).

| Token | Hex |
|-------|-----|
| Impact Orange | `#FFAD2F` |
| Canvas Cream | `#F7F2EE` |
| Accent Pink | `#FFA1F7` |
| Driving Magenta | `#FB4D86` |
| Creative Lavender | `#A864FC` |
| Deep Green | `#01924E` |
| Curious Blue | `#2A77FF` |
| Soft Black | `#312D2B` |

## Deploying with Vercel

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) and import the repo
3. Leave all settings as default — Vercel auto-detects static HTML
4. Click **Deploy** — your site will be live in under 30 seconds

## Local development

No build step required. Open any `.html` file directly in a browser, or use a simple local server:

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## File structure

```
/
├── index.html           # Homepage
├── about.html           # About page
├── resources.html       # Resources — Security & Data FAQ
├── b_corp_logo.png      # Certified B Corporation logo
├── b_corp_photo.jpg     # B Corp landscape background photo
├── graphic_bus.jpg      # CSnet Impact Bus illustration
├── impact_report.jpg    # CSnet Impact Report 2025 cover
└── README.md            # This file
```

## Pages still to build

- [ ] Getting Started / Implementation
- [ ] Contact
