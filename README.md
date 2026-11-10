# etsy-dashboard-callback

The sign-in callback page for the Etsy Dashboard desktop app, served by GitHub Pages at
https://nicholasbrunet.github.io/etsy-dashboard-callback/

Etsy sends the user here after they approve the app. The page shows the one-time code so it can be pasted into the app. The code is useless on its own: exchanging it needs the PKCE verifier held by the running app.

The page loads nothing external and holds no secrets. Its source and tests live in the main (private) repo; this repo only publishes it. Keep anything else out of here.
