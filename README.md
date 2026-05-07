# CSnet Website

Static website for [CSnet](https://csnet.net.au) — community service case management software built for the sector, by people who've worked in it.

## Pages

| File | Page |
|------|------|
| `index.html` | Homepage (Section 1) |
| `about.html` | About (Section 2) |

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

## Deploying with GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

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
├── index.html       # Homepage
├── about.html       # About page
└── README.md        # This file
```

## Pages still to build

- [ ] Getting Started / Implementation (Section 3)
- [ ] Resources (Section 4)
- [ ] Contact
