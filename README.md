# Overtime Authorisation links

These pages exist for one reason: **WhatsApp will not show a preview card for an
Apps Script link.** It shows a bare `script.google.com/macros/...` URL, which looks
like spam to a shop-floor manager. A tiny page on GitHub Pages, carrying the right
`og:` tags and redirecting on to the real form, fixes that.

## Setting it up (once, about five minutes)

1. On github.com, create a new **public** repository — `overtime-links` is a fine name.
2. Upload `overtime-preview.png` and the five store pages into it.
3. Settings ▸ Pages ▸ Source: *Deploy from a branch*, branch `main`, folder `/ (root)`. Save.
4. Wait a minute or two, then your links are:

       https://<your-github-username>.github.io/overtime-links/zss.html
       https://<your-github-username>.github.io/overtime-links/kss.html
       ... and so on

5. Drop the right one into each store's WhatsApp group.

## What a manager sees

A card with the image, the title "Overtime Authorisation — <store>", and one line
of description. Tapping it opens the form in their phone browser, already set to
that store, with only that store's staff in the search box.

Ask them to **Add to Home Screen** once. After that it opens like an app.

## If you change a store name or the form URL

Edit that store's `.html` file on GitHub — every value is in plain sight near the top.
