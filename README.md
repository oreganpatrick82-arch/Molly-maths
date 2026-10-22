# Molly's Maths

Molly's Division Challenge as an installable iPad app, with a welcome screen
("Maths is the language of the universe"), its own icon, full-screen launch and
offline play.

## Put it online (once, about 5 minutes)

1. On a computer, unzip `molly-maths-app.zip`.
2. Go to https://app.netlify.com/drop and drag the `molly-maths-app` folder onto the page.
3. Sign up for a free Netlify account when it offers, so the site is claimed and stays up.
4. Rename the site if you like (Site settings → Change site name), e.g. `mollys-maths.netlify.app`.

GitHub Pages or Cloudflare Pages work just as well. Any HTTPS host does.

## Install on Molly's iPad

1. Open the site in **Safari** (not Chrome).
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Open it once from the new icon while on Wi-Fi so it saves itself and the fonts for offline use.

## Notes

- Progress is saved on the iPad, inside the app. Deleting the app icon deletes the progress.
- To update the app later, change the files, bump `VERSION` in `sw.js`, and drag the folder
  onto the site's Deploys page in Netlify. The iPad picks it up on the next launch or two.
