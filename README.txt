GRAPHICS GENIX STUDIO 2.1 — INTRO + MOBILE EDITOR + PHOTO TRENDS

Static PWA project for GitHub Pages. This is a development build; run the main workflows in a browser before treating it as production-ready.

Updates in 2.1:
- First-launch cinematic welcome screen with Enter / Skip; dismissed intro stays dismissed in that browser.
- Refined interlocking GG app icon with glossy cyan/blue/violet gradients; updated SVG and PNG app icons.
- Clearer, higher-contrast undo/redo controls and larger touch targets.
- Mobile quick-action strip for Text, Photo, Shape, Color, Undo and Redo, plus a horizontally scrollable editor tool rail.
- Ten additional Photo templates inspired by current creator formats: photo dumps, film diaries, carousel covers, fit checks, visual journals, moodboards, monthly recaps and travel logs. These are trend-inspired formats, not a claim that a particular trend is universally popular.
- Updated service-worker cache version so browsers can fetch the new build.

Core workflows retained:
- Searchable templates and categories
- Editable text/shape/photo layers and photo replacement
- Canvas size and background controls
- Undo/redo, local autosave and saved projects
- PNG/JPG export
- Standalone photo adjustments and quick looks
- Responsive desktop/mobile interface and PWA manifest

Publish:
1. Back up the current GitHub repository contents.
2. Replace the existing site-root files with the files in this folder (keep files at repository root).
3. Commit and push to the branch/folder configured for GitHub Pages.
4. Wait for Pages to deploy, then hard-refresh. If the installed app shows old content, close it and reopen so the new service worker activates.

Notes:
- Project data is stored in this browser; local photos are not uploaded to a server. Export important work.
- This is not an AI image generator or full video timeline editor; no unavailable AI/video processing is represented as working.
