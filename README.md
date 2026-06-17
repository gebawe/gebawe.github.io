# gebawe.github.io

Personal portfolio of **Awet Gebrehiwot** — Senior Machine Learning & Computer Vision Engineer, autonomous-driving perception.

Live: https://gebawe.github.io

## About this site
A single self-contained `index.html` (HTML + CSS + JS inline) with a "sensor visualizer" visual language: an animated LiDAR/BEV sweep hero, monospace telemetry labels, bounding-box framing on imagery, and segmentation-style color tags. No build step — GitHub Pages serves it directly.

Sections: About · Experience · Publications (IROS 2023, IEEE RA-L 2022, ECCV 2020) · Work · Skills · Contact.

## Editing
- Everything lives in `index.html`. Styles are in the `<style>` block (CSS variables at the top control the palette); behavior is in the `<script>` at the bottom.
- Portfolio demos are `images/*.mp4`/`*.jpeg`, loaded on click to keep the page light. Add a card by copying an `article.card` block and setting `data-video` / `data-img` and `data-cat` (`dl`, `cv`, `rob`).

## Before going live
- **Contact form:** create a free form at https://formspree.io and replace `YOUR_FORM_ID` in `index.html`.
- **Google Scholar:** add your profile URL if you want a Scholar link.

## Cleanup (optional)
The old template assets are no longer referenced and can be deleted: `stylesheets/all.css`, `javascripts/all.js`, and the `fonts/` directory. Fonts now load from Google Fonts; icons from Font Awesome.
