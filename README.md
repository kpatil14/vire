# vire — a small dawn

A cinematic, single-page experience designed for an Instagram bio link.

The visitor lands on a pitch-black screen with a quiet hint: *"move to reveal."* As they drag their cursor (or finger on mobile), the darkness wipes away to slowly uncover a misty mountain landscape at dawn. Once they've explored enough, the **surprise** triggers — the entire scene comes alive: the sun rises, mist drifts, birds glide across the sky, and a soft greeting appears.

No accounts. No tracking. No clutter. Just one beautiful moment.

## Curated by Nachiket.

---

## Run locally

```bash
npm install
npm run dev
```

## Deploy

This is set up to auto-deploy to GitHub Pages on every push to `main`.

1. Push the code to your `vire` repo.
2. In GitHub: Settings → Pages → Source → **GitHub Actions**.
3. Wait ~2 minutes. Site goes live at `https://YOUR_USERNAME.github.io/vire/`.

## Customizing

- **Your name** → edit `SIGNATURE` at the top of `src/App.tsx`.
- **Greeting wording** → edit the `greeting` function inside `App.tsx`.
- **Mountain colors / dawn palette** → tweak the `nightTop`, `dawnTop`, `mountainLayers` arrays in `App.tsx`.
