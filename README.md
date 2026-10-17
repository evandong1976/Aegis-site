# aegis-site

The website for **Aegis** — a macOS menu-bar app plus Chrome extension that checks links,
downloads and scam text before they reach you. (The app itself lives in a separate repository.)

- `index.html` — the product landing page. Static; deploy anywhere.
- `demo.html` — a **demonstration** page used to show Aegis catching a look-alike domain. It
  mimics a Microsoft sign-in and links to `rnicrosoft.com` (the letters "rn" reading as "m"). It
  is a labeled demo, **not** a real Microsoft page, and it collects nothing — the "Sign in"
  buttons are just the look-alike link, which is the thing Aegis flags. Run it on your own machine
  with Aegis installed; do not host it as if it were a real sign-in page.

## Run locally

```bash
python3 -m http.server 8099
# then open http://localhost:8099/
```

No build step — plain HTML and CSS, fonts from Google Fonts.
