# relay4agents.com

Marketing site for [relay4agents](https://github.com/arunrlverma/relay4agents) — the secure bridge between AI agents and your phone.

## Pages

- **/** — Landing page
- **/privacy.html** — Privacy policy (required for App Store)
- **/terms.html** — Terms of service
- **/support.html** — Support & FAQ (required for App Store)

## Hosting

Static site hosted on GitHub Pages with custom domain `relay4agents.com`.

## Development

No build step. Open `index.html` in a browser.

```bash
# Local preview
python3 -m http.server 8000
open http://localhost:8000
```

## Deploy

Push to `main` → GitHub Pages auto-deploys.
