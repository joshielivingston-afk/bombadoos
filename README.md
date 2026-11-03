# bombadoos

A homepage for action, not thinking: **spontaneous**, **deep** (a one-hour session), and **archetypal** (creative and life desires that glow brighter each time you return to them), plus **center first**, one quiet minute.

- `bombadoos.html` is the whole site. Its music is generated in the browser, so there are no other files.
- On claude.ai (as an artifact) it saves to the artifact's database, synced across devices.
- On the GitHub Pages site it signs in by email link and syncs through Supabase (tables `items` and `timer`, row-level security per user). "this device only" skips sign-in and uses local storage.
- Opened as a local file it saves to that browser's local storage.
- Every push to `main` publishes it to GitHub Pages via `.github/workflows/deploy.yml`.
