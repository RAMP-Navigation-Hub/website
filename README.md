# RAMP Navigation Hub — GitHub Pages site v1

This is a static, accessible prototype built from the supplied RAMP NHS App guides, readiness material, playlists and official NHS source register.

## Publish on GitHub Pages
1. Upload all files and folders to the repository root.
2. In **Settings → Pages**, publish from the `main` branch and `/ (root)`.
3. Wait for the Pages deployment, then test the published URL.

## Structure
- `index.html` — homepage
- `journey.html` — route-finding
- `readiness.html` — Apple/Android checks
- `guides.html` — PDF library
- `videos.html` — YouTube playlists and individual videos
- `resources.html` — approved NHS links
- `about.html` — boundaries and privacy
- `assets/documents/` — downloadable PDFs
- `assets/images/` — guide previews

## Pre-publication checks
- Verify both YouTube playlist embeds.
- Test every NHS link.
- Check captions on the videos.
- Test keyboard navigation, zoom at 200%, mobile layout and PDF downloads.
- Confirm local ownership and review dates.

## Version 1.3 — performance optimisation

- Replaced large JPEG previews with compact WebP images.
- Reduced preview dimensions to a maximum width of 720 pixels.
- Added lazy loading and asynchronous image decoding.
- Added fixed image dimensions to reduce layout movement.
- Prioritised the homepage hero image.
- Changed YouTube embeds to click-to-load players.
- Preserved the original high-resolution PDFs for viewing and printing.
