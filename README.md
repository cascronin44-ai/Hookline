# Hookline

**Learn the part of the song everyone knows.**

Hookline is a concept for a beginner guitar app. It teaches the hook of each trending song, simplified to the chords you already know, and measures your progress in songs unlocked.

This repo has an interactive UI kit for the app: 8 phone screens (onboarding, home, hook lesson, mic practice, tuner, learning plan, library, record & share) that you can customize in the browser.

## Using the UI kit

Open `index.html` in a browser, or visit the GitHub Pages site for this repo.

- **Themes:** 6 presets, including Mahogany with wood grain, plus color pickers for every theme color
- **Type & shape:** font pairings, corner roundness and zoom
- **Edit layout & text:** drag home tiles, tab icons, home sections and whole screens; click any text to rewrite it; click a tile to change its icon, label or style
- **Show or hide** home sections and screens
- **Copy config** exports your setup as JSON

Changes are saved in your browser's local storage. Song and artist names are placeholders.

It's a single HTML file with no build step. Fonts load from Google Fonts and drag-and-drop uses [SortableJS](https://github.com/SortableJS/Sortable) from cdnjs.
