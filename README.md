# Waghela Enterprises — Company Website

Static marketing site for **Waghela Enterprises** — Leaders in Underground Infrastructure & Trenchless Technology (Thane / Mumbai).

## Stack

- Single-page HTML (`index.html`)
- Mobile-first CSS (`styles.css`) — navy `#0B1F3A` + gold `#C9A227`
- Minimal JS (`script.js`) — mobile nav + year
- SVG favicon (`favicon.svg`) — WE circle mark

## Open locally

```bash
cd /workspace/waghela-site
python3 -m http.server 8765
```

Then open [http://127.0.0.1:8765/](http://127.0.0.1:8765/) in a browser.

Or open `index.html` directly in a browser (some SEO meta previews work best via a local server).

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `waghela-enterprises` or `waghela-enterprises.github.io`).
2. Push this folder’s contents to the `main` branch:

   ```bash
   git init
   git add .
   git commit -m "Add Waghela Enterprises static site"
   git branch -M main
   git remote add origin https://github.com/<USER>/<REPO>.git
   git push -u origin main
   ```

3. In the repo **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` / root (`/`)
4. After a minute, the site is live at `https://<USER>.github.io/<REPO>/` (or the custom domain / user site URL if configured).

Update the `canonical`, Open Graph `og:url`, and JSON-LD `url` in `index.html` to match the final public URL.

## Contact (authoritative)

| Field | Value |
|-------|--------|
| HQ | Thane, Maharashtra — 400 607 |
| Address | Ground Floor, Bldg No. R-3, Gala No. 80, Shree Swami Samarth CHS, Khartan Road, Thane |
| Phones | +91 96194 96191 / +91 98215 59495 |
| Email | waghela.enterprises@gmail.com |
| GSTIN | 27AASPW3890J1ZO |
| Partners | Pravin Waghela & Ashish Thakur |
| WhatsApp | https://wa.me/919821559495 |

## License

Site content © Waghela Enterprises. All rights reserved.
