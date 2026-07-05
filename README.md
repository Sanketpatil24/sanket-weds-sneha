# Sanket & Sneha — Wedding Invitation

Static wedding invitation site (25th November 2026, Pune).

## Deploy

Push this folder to a GitHub repo and import it in Vercel
(framework preset: **Other**, no build step — it is plain HTML).
Or enable GitHub Pages on the repo root.

## Structure

```
index.html          — the entire site (all artwork is inline SVG)
assets/styles.css   — stylesheet (self-hosted)
assets/story-1.jpg  — Our Story carousel, slide 1 (auto-rickshaw)
assets/story-2.jpg  — slide 2 (café)
assets/story-3.jpg  — slide 3 (garden)
```

To swap a story photo, replace the file keeping the same name —
images are auto-cropped to the 4:5 polaroid frame.

## Notes

- Only external dependency: Google Fonts.
- RSVP form shows a thank-you message but does not store responses anywhere.
- Countdown targets 25 Nov 2026, 11:26 AM IST.
