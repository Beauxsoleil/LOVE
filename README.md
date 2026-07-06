# Guess How Much I Love You 💗🚀

A little love-note web app: a photo collage with a glowing heart button in the
middle. Tap it and a rocket blasts off to a **random planet** (the Moon, Mars,
Saturn, Neptune, and more) and flies back, with a sweet message and a burst of
hearts. Every tap picks a different planet.

Works great on iPhone (and any phone or computer) — it's just one HTML file,
no build step, no internet needed after loading.

## How to run it

### On your iPhone
1. Get the files onto a place your phone can open them. Easiest options:
   - **Host it free** with GitHub Pages, Netlify, or Vercel, then open the link
     in Safari.
   - Or open `index.html` from the Files app / iCloud Drive.
2. Once it's open in Safari, tap **Share → Add to Home Screen** to make it feel
   like a real app (full screen, its own icon).

### On a computer
Just double-click `index.html`, or run a tiny local server:

```bash
cd LOVE
python3 -m http.server 8000
# then open http://localhost:8000
```

## Adding your photos
- **Easiest:** open the app and tap **"＋ Add Photos"** (top-right). Photos are
  saved on the device and appear in the collage right away.
- **Or:** drop images into the `images/` folder named `1.jpg … 12.jpg`.
  See `images/README.md` for details.

Empty spots become cute heart tiles, so the collage always looks full even
before you add any pictures.

## Customizing
Everything lives in `index.html`:
- **Planets** — edit the `PLANETS` list (name, color, size, rings, message).
- **Button text / colors** — search for `love-btn` and the button label.
- **Collage feel** — tweak `FOLDER_PHOTOS` and the `.tile` styles.
