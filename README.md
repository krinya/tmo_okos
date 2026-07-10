# tmo_okos

A one-page website that displays a single picture, plays a sad trombone, and rains 🎺.

Built to prove a very important point: anyone can buy a domain and put whatever they want on it. Yes, even that.

## What's inside

- [`public/index.html`](public/index.html) — the entire site. One image, centered on a dark background.
- [`public/tmo_okos.png`](public/tmo_okos.png) — the picture. The whole reason we're here.

The sad trombone ("wah wah wah waaaah") is synthesized in the browser with the Web Audio API, so there's no audio file to ship. Trombone emojis rain down continuously behind the image.

## Run it locally

```bash
cd public
python3 -m http.server 8000
```

Then open http://localhost:8000.

> If you don't hear the trombone right away, click once. That's your browser's autoplay policy, not a bug — it behaves the same everywhere.

## Put it on a real domain

1. Enable GitHub Pages (Settings → Pages → deploy from `main`, folder `/public`). Instantly live at `https://krinya.github.io/tmo_okos/`.
2. Or drag the `public/` folder onto [Netlify Drop](https://app.netlify.com/drop).
3. Buy the domain of your choosing, point it at the site, and let the point make itself.

## License

Do whatever you want. It's a picture and a trombone.
