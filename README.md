# Crownbest School — Static Website

This is a static, single-file React app (compiled in-browser via Babel) with local placeholder images in the `images/` folder.

Quick preview (recommended):

- Using Python 3 built-in server (from project root):

```bash
# Windows / macOS / Linux
python -m http.server 8000
# then open http://localhost:8000 in a browser
```

- Using VS Code Live Server: install the Live Server extension and open the workspace; click "Go Live".

Deploy options:

- GitHub Pages: push the repo to GitHub and enable Pages to serve from the `main` branch root (index.html is at project root).
- Netlify / Vercel: drag & drop the repository or connect GitHub and deploy as a static site (build command: none; publish directory: project root).

Notes:

- The app entry file is `index.html` and all images live under the `images/` folder.
- I replaced remote images with local placeholder SVGs named `images/img1.svg` through `images/img25.svg`.
- If you want the original `code.html` preserved, restore it from your Git history or let me know and I can add a backup copy.

Next steps I can take:

- Recreate `code.html` as a backup at your request.
- Wire up a real image set (you can drop files into `images/` and I'll update references if needed).
- Initialize a Git repo and make a first commit.
