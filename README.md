# Codepack Landing Page

Single-page static marketing site for the Codepack VS Code extension.

## Files

- `index.html`
- `styles.css`
- `script.js`
- `netlify.toml`
- `assets/logo.png`
- `assets/og-image.png`

## Local Preview

- Open `index.html` directly in a browser.
- Or run:

```bash
py -m http.server 8000
```

## Netlify Setup

1. Connect this GitHub repo in Netlify.
2. Build command: none.
3. Publish directory: `.`.
4. Direct routes are folder-based static pages, including `/terms-and-conditions/` and `/terms-of-service/`, so no SPA rewrite should be configured.

## Domain Setup (`nikolasifyart.com`)

1. In Netlify, open Site configuration > Domain management.
2. Add custom domain `nikolasifyart.com`.
3. Follow Netlify DNS instructions:
   - Use Netlify nameservers, or
   - Configure A/CNAME records exactly as Netlify provides.

## Notes

- Premium checkout link currently routes to `#contact`.
- Contact email for premium purchase: `nikolasify@nikolasifyart.com`.
- Legal pages live at `/terms-and-conditions/` and `/terms-of-service/`.
- Future commercial plans may add Pro and Business/Enterprise tiers; one-time Premium purchasers remain grandfathered for Premium access and receive discounted future Pro pricing when offered.
