# Semantic Versioning Standup Presentation

A short (about 3 minutes, 7 slides) presentation built with [reveal.js](https://revealjs.com), loaded from a CDN. There is nothing to install.

## Presenting
1. Double-click `index.html` to open it in a browser. An internet connection is needed to load reveal.js.
2. Navigate with the arrow keys or Space. Some slides reveal content step by step.
3. Press **S** to open speaker notes in a separate window. Press **F** for fullscreen and **Esc** for the slide overview.

## Adding screenshots
1. Save the screenshots into the `images/` folder:
   - `images/github-releases.png`: the GitHub repo's Releases page
   - `images/jira-fix-version.png`: a Jira ticket showing the Fix Version field
2. In `index.html`, find each `<div class="placeholder">…</div>` block and replace it with the `<img>` tag from the HTML comment just above it.

## Editing
- Each slide is a `<section>` in `index.html`.
- Speaker notes are in `<aside class="notes">` inside each slide.
- Remove `class="fragment"` from an element to show it immediately instead of step by step.
- Theme: change `night.css` in the `<head>` to another theme, such as `black.css` or `moon.css`.
