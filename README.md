# Md Fokrul Akon — Portfolio

A single-file, self-contained portfolio site (`index.html`). No build step, no dependencies to install.

## Host it on GitHub Pages

1. Create a new repository on GitHub — for a personal site, name it `mdfokrulakon.github.io` (this gets you a live site at `https://mdfokrulakon.github.io` with no extra setup). Any other repo name works too, just with a `/reponame` path.
2. Upload **both** `index.html` and `Fokrul-Akon-CV.pdf` to the root of that repository (drag-and-drop on the GitHub web UI works fine, or `git add`, `git commit`, `git push`). The "Download CV" button on the site links to `Fokrul-Akon-CV.pdf` by relative path, so it must sit in the same folder as `index.html` — if you rename the PDF, update the two `href="Fokrul-Akon-CV.pdf"` links in `index.html` to match.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**, pick the `main` branch and `/ (root)` folder, then **Save**.
5. Wait a minute or two — GitHub will give you a live URL at the top of that Pages settings screen.

## Editing later

Everything — layout, colors, copy — lives in the one `index.html` file: CSS is in the `<style>` block at the top, content is in the `<body>`, and the project filter script is at the bottom. Open it in any text editor, change it, and push again to update the live site.
