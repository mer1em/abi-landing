# ABI Landing (Coming Soon)

A lightweight, static landing page for ABI with a Netlify contact form (no backend required).

## Deploy (recommended): Netlify (with form handling)
1. Create a GitHub repo and push this folder.
2. Go to Netlify → **Add new site** → **Import from Git** → select your repo.
3. Build settings:
   - **Build command:** (empty)
   - **Publish directory:** `.`
4. Deploy.

Netlify will automatically capture submissions from the form named `abi-early-access`.

## Local preview
Open `index.html` in your browser (or use VS Code Live Server).

## Forms
Form submissions redirect to `/thanks.html`.
