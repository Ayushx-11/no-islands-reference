# No Islands — Official Reference Guide

A web companion to **No Islands Vol. 1**, the manga set in the world of Ghara.

Static reference site covering:

- Philosophy of interdependence
- World setup — Ghara & the Heavens
- Characters — The Parent, Badara/Ronbel, Deliro Monasque, Angel
- The Kruhind
- The divine hierarchy
- Fortune & suffering as opposing forces
- Outer cosmic powers (The Chalice, Adam, Uriel)

## Image placeholders

Every dashed box marked `[ MANGA … ]` in the layout is a placeholder ready to be
swapped for real art. Drop your image into the project folder and replace the
matching `<div class="image-slot …">…</div>` with a normal `<img src="…">`.

## Local preview

This is a pure static site — no build step.

```bash
npx serve .
```

Then open the printed URL.

## Deploy

Pushes to `main` deploy automatically to Vercel.
