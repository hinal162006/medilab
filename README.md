# Medilab

A healthcare landing page built with HTML, CSS, and Bootstrap 5.

## View it live

This repo is ready for **GitHub Pages** — no build step needed, it's a static site.

### Deploy in 3 steps

1. Create a new repository on GitHub and upload everything in this folder
   (`index.html` and the `images/` folder), keeping the same structure.
2. In your repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**,
   pick the `main` branch and `/ (root)` folder, then click **Save**.

GitHub will publish the site at:

```
https://<your-username>.github.io/<repo-name>/
```

It can take a minute or two to go live after the first deploy.

## Running it locally

No server or build tools required — just open `index.html` in a browser.

If you want to preview it the same way a real web server would (recommended,
since some browsers restrict local file access), run one of these from the
project folder:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## Project structure

```
.
├── index.html      # the whole site (HTML + CSS + JS in one file)
├── images/          # all photos used on the page
└── README.md
```

## Notes

- Built with [Bootstrap 5](https://getbootstrap.com/) and
  [Bootstrap Icons](https://icons.getbootstrap.com/), both loaded from CDN.
- Fonts (Poppins, Jost) are loaded from Google Fonts.
- All content is placeholder/sample text and images for demonstration
  purposes.
