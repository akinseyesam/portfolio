# Academic Site — Quick Deploy

This folder contains a minimal static academic portfolio ready for GitHub Pages or other static hosts.

What is included (root of this package):
- `index.html` — main page (recommended filename for root URL)
- `Image/` — image assets (profile image is `sam-profile.png`)
- `CV.pdf` — downloadable CV
- `Academic Folder/Accademic.html` — original page (kept for reference)
- `.github/` — repository helper files (if present)

How to publish on GitHub Pages (web upload):
1. Create a repository named `akinseyesam.github.io` on GitHub (public).
2. On the repo page click **Add file → Upload files**.
3. Drag & drop the contents of this ZIP (all files and folders) into the upload area so `index.html` is at the repository root.
4. Commit the upload.
5. Go to **Settings → Pages**, choose **Branch: main** and **Folder: / (root)**, then Save.
6. Wait a couple minutes. Your site will be available at `https://akinseyesam.github.io/`.

Notes & troubleshooting:
- Keep `index.html` at repo root. If `index.html` is inside a folder, the URL will include that folder name.
- Paths in `index.html` expect `Image/` and `CV.pdf` to be at the repository root.
- Avoid renaming image files with spaces; this repo uses `sam-profile.png`.
- If images or the CV 404 after publish, check the file paths and that files were uploaded to the repo root.

Next steps I can help with:
- Create a git commit and push (if you install Git locally).
- Configure a custom domain (e.g., akinseye.com).
- Optimize images (convert to WebP, compress) for faster loading.

If you want, upload the ZIP contents via GitHub now and tell me when done — I will help verify and troubleshoot.
