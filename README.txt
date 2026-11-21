CLASSIC CODE
Static browser coding studio.
Features: HTML/CSS/JS tabs, syntax highlighting via CodeMirror CDN, run/preview, browser local save, JSON export, combined HTML download, PWA manifest and service worker.
Deploy to Cloudflare Pages:
- Create a new GitHub repository (example: classic-code).
- Upload all files in this ZIP.
- Cloudflare Pages > Connect to Git > choose the repository.
- Framework preset: None.
- Build command: leave empty (or `exit 0`).
- Build output directory: / (root).
- Deploy.
CodeMirror syntax highlighting loads from cdnjs; if unavailable, plain textarea fallback remains.
