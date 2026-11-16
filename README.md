# Gowtham Krishna Muthyala — Portfolio

Single-page portfolio site. Everything lives in `index.html` (HTML, CSS and JavaScript in one file).
It loads Three.js from cdnjs and fonts from Google Fonts, so it needs an internet connection but no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Host on GitHub Pages

1. Create a new repository on GitHub (for example `portfolio`).
2. Upload `index.html` and this `README.md` to the root of the repository.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute or two the site is live at `https://<your-github-username>.github.io/portfolio/`.

To use the root address `https://<your-github-username>.github.io/`, name the repository `<your-github-username>.github.io` instead.

## Notes

- The page includes `<meta name="robots" content="noindex, nofollow">`, so search engines are asked not to list it.
  Remove that line if you later want the site to appear in Google.
- A GitHub Pages site from a public repository is public to anyone with the link, and the source is visible on GitHub.
