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
4. **(Optional)** Add a `music.mp3` file to the root for background music
5. **Push to GitHub** and enable GitHub Pages in Settings → Pages → Source: `main` branch

## How to Add Photos

Drop your photos in the `images/` folder and name them `photo1.jpg` through `photo6.jpg` (or however many you have).

To **add or remove photos**, edit the `PHOTOS` array near the top of `index.html`:

```js
const PHOTOS = [
  { src: "images/photo1.jpg", caption: "🥰 Haaye dil le gayi kudi" },
  { src: "images/photo2.jpg", caption: "🤩 mashuka" },
  // add more or remove as needed
];
```

## How to Customize

Everything is configurable at the top of the `<script>` section in `index.html`:

- **`BIRTHDAY_NAME`** — her name
- **`BIRTHDAY_AGE`** — her age
- **`SENDER_NAME`** — your name
- **`REASONS`** — the 5 balloon messages
- **`PHOTOS`** — photo filenames + captions
- **`LETTER_TEXT`** — the love letter content

## Sections (in order)

1. 💖 Cupid Intro — tap to start, floating hearts
2. 🎀 Happy Birthday splash — pink gradient
3. 🌳 Heart Tree — tree blooms with hearts, name + age reveal
4. 🎂 Birthday Cake — confetti burst
5. 🎈 Pop the Balloons — 5 tappable balloons with reasons
6. 📸 Memory Lane — swipeable photo carousel
7. 💌 Love Letter — envelope opens, typewriter effect
8. 🎉 Finale — confetti rain, final message

## Background Music

Drop any `.mp3` file in the root folder named `music.mp3`. The music toggle button is in the top-right corner.

## Hosting

Works on GitHub Pages, Netlify, Vercel, or any static host. Just push the folder as-is.

Your site URL will be: `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

Made with ❤️ by Gaurav
