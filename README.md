# Evergreen Launcher (Evergreen OS)

Unified gateway for all Evergreen Media Design applications and dashboards.

## Quick Start

This folder is configured for GitHub Pages deployment to `launcher.evergreenmediadesign.com`.

### Files
- `CNAME` - Contains: `launcher.evergreenmediadesign.com`
- `index.html` - Main landing page
- `README.md` - This file

### Deployment

1. Create a new GitHub repository: `evergreen-launcher`
2. Copy this folder contents to the repo root
3. Push to GitHub
4. Go to repo **Settings → Pages**
5. Enable GitHub Pages from main branch
6. Add custom domain: `launcher.evergreenmediadesign.com`
7. GitHub will auto-detect CNAME and provision SSL

### DNS Configuration

Add this CNAME record in Squarespace Domains:

| Host | Type | Value | TTL |
|------|------|-------|-----|
| `launcher` | CNAME | `generalmillz.github.io` | Auto |

### Status

- ✅ Subdomain configured
- ✅ CNAME file ready
- ✅ Index.html placeholder
- ⏳ GitHub repo creation (manual step)
- ⏳ DNS propagation

### Support

For issues, contact Evergreen Media Design or GitHub Pages support.
