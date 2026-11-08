# 🎂 Happy Birthday Shikha — Setup Guide

## Quick Start (GitHub Pages)

1. **Create a new GitHub repo** (e.g. `happy-birthday-shikha`)
2. **Extract this zip** directly into the repo
3. **Add your photos** to the `images/` folder:
   - `images/photo1.jpg`
   - `images/photo2.jpg`
   - `images/photo3.jpg`
   - `images/photo4.jpg`
   - `images/photo5.jpg`
   - `images/photo6.jpg`
4. **Push to GitHub** and enable GitHub Pages in Settings → Pages → Source: `main` branch

## How to Add Photos

Drop your photos in the `images/` folder and name them `photo1.jpg` through `photo6.jpg` (or however many you have).

To **add or remove photos**, edit the `PHOTOS` array near the top of `index.html`:

```js
const PHOTOS = [
  { src: "images/web/photo1.jpg", caption: "🥰 Haaye dil le gayi kudi" },
  { src: "images/web/photo2.jpg", caption: "🤩 mashuka" },
  // add more or remove as needed
];
```

Resized copies used by the site live in `images/web/` (the originals stay in `images/`).

## How to Customize

Everything is configurable at the top of the `<script>` section in `index.html`:

- **`BIRTHDAY_NAME`** — her name
- **`BIRTHDAY_AGE`** — her age
- **`SENDER_NAME`** — your name
- **`REASONS`** — the 5 balloon messages
- **`PHOTOS`** — photo filenames + captions
- **`LETTER_TEXT`** — the love letter content

## Sections (in order)

1. Bow — hold and release; the arrow lights the heart
2. Happy Birthday — the sparks form the words
3. Heart Tree — grows and blooms, name + age
4. Cake — blow out the candles
5. Balloons — each pop releases a note
6. Memory Lane — tap each polaroid to develop it
7. Envelope — break the wax seal
8. Letter — words appear as if being written (tap to show it all)
9. Finale — tap the sky for fireworks

## Hosting

Works on GitHub Pages, Netlify, Vercel, or any static host. Just push the folder as-is.

Your site URL will be: `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

Made with ❤️ by Gaurav
