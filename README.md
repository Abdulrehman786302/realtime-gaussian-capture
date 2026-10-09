# Live Gaussian-Splat Volumetric Capture — project page

Static project page (single `index.html`, no build step) for GitHub Pages.

## Publish
1. Create an empty repository on GitHub (e.g. `realtime-gaussian-capture`).
2. Push this folder to its `main` branch.
3. Repository **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. The page appears at `https://<user>.github.io/<repo>/`.

## Add media
Put cleared captures in `assets/` and replace the placeholder in the `#video` section of `index.html`:

```html
<video src="assets/teaser.mp4" autoplay muted loop playsinline></video>
```

Keep videos short (H.264 MP4, a few MB) so the page loads fast.
