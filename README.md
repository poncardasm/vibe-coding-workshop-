# Vibe Coding Workshop Landing Page

A single-page static site for workshop attendees. Clean, light mode, mobile-first.

## Quick Start

Open `index.html` in any browser. No server required.

## Structure

```
vibe-coding-workshop/
├── index.html          # Main landing page
├── css/
│   └── styles.css      # Complete stylesheet (light mode only)
└── README.md           # This file
```

## Content Sections

1. **Pre-Workshop Setup** - Node.js check, OpenCode install, troubleshooting
2. **Workshop Resources** - API key setup (Google AI Studio, OpenRouter), links
3. **Live Reference** - Commands cheat sheet, model switching, free tier limits
4. **After the Workshop** - Next steps, community, recording link

## Deployment

### GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → main → / (root)
4. Site will be at `https://username.github.io/repo-name/`

### Custom Domain

Add a `CNAME` file with your domain, then configure DNS:
```
vibe-coding.poncardas.com
```

### Cloudflare Pages

1. Connect GitHub repo to Cloudflare Pages
2. Build settings: None (static site)
3. Deploy

## Updating Content

1. Edit `index.html` directly
2. Test locally by opening in browser
3. Commit and push to deploy

## Design Notes

- Light mode only (consistent, no flash)
- Mobile-first responsive
- Print-friendly styles included
- No JavaScript dependencies
- < 20KB total

## Last Updated

April 6, 2025
