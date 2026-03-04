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
npx serve .
```

## Netlify Setup

1. Connect this GitHub repo in Netlify.
2. Build command: none.
3. Publish directory: `.`.
4. Netlify will use `netlify.toml` redirect settings automatically.

## Domain Setup (`nikolasifyart.com`)

1. In Netlify, open Site configuration > Domain management.
2. Add custom domain `nikolasifyart.com`.
3. Follow Netlify DNS instructions:
   - Use Netlify nameservers, or
   - Configure A/CNAME records exactly as Netlify provides.

## Notes

- Premium checkout link currently routes to `#contact`.
- Contact email for premium purchase: `nikolasify@nikolasifyart.com`.
