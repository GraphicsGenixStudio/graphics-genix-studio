GRAPHICS GENIX STUDIO 2.0 — STATIC PWA

Files at the root of this folder are designed for static hosting such as GitHub Pages.

Included core workflows:
- Responsive home, template search and category filters
- Editable template text, shape and photo layers
- Drag to reposition layers; property controls for text, colors, sizing and rotation
- Add text, shapes, and local photo images; replace a photo layer without replacing other layers
- Undo/redo history, local autosave, saved projects
- PNG/JPG canvas export at the selected canvas size
- Standalone photo editor with brightness, contrast, saturation, warmth, fade and quick looks
- PWA manifest and cache versioning

Publish:
1. Back up the current GitHub repository contents.
2. Replace the existing site-root files with the files in this folder (keep the files at repository root).
3. Commit and push to the branch/folder configured for GitHub Pages.
4. Wait for Pages to deploy, then hard-refresh the site. If the old app remains cached, close installed tabs/app and reopen after the new service worker activates.

Notes:
- The app is local-first; project data is stored in this browser. Export important work as PNG/JPG.
- Local image files are not uploaded to a server. Browser storage can be cleared by the browser.
- This is not an AI image generator or a full video timeline editor. No AI/video processing is represented as working when it is not implemented.
- Google Fonts are an optional online enhancement; system fallbacks are included.
