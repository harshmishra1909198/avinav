# Abhinav Pandey Birthday Surprise

A premium, responsive React + Vite birthday experience with Framer Motion animations, canvas-confetti, a touch-friendly scratch card, virtual cake, WhatsApp sharing, and an accessible music toggle.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown by Vite. To create a production build:

```bash
npm run build
npm run preview
```

## Personalize

Edit `BIRTHDAY_CONFIG` near the top of `src/main.jsx`. This is where the name, demo photo, music URL, sender, messages, and profile values live. Replace the demo photo URL with the real photo and set `music` to an MP3 path or URL when ready. Music intentionally begins only after the user opens the gift to comply with browser autoplay policies.
