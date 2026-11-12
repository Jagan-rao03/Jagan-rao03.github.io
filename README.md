# Jagan Rao Y – Portfolio

Single-page portfolio website (plain HTML, CSS and JavaScript, no build step).

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Deploy
- **GitHub Pages:** push to GitHub, then Settings > Pages > Deploy from branch > `main` / root.
- **Netlify / Vercel:** import the repository; no build command, publish directory is the root.

## Structure
- `index.html` – all markup, styles and scripts
- `assets/` – hero photo and event photos (`hero.jpg`, `moment-*.jpg`)

## Notes
- The enquiry form opens WhatsApp (+91 88856 88386) with the message filled in, and offers an email option. It does not send email by itself; for that, connect a form service such as Formspree or Netlify Forms.
- Contact details, LinkedIn link and WhatsApp number are in `index.html`; search for `yjagannath03@gmail.com`, `linkedin.com/in/` and `918885688386`.
