# Orderology Organizing

Website source for [orderologyorganizing.com](https://www.orderologyorganizing.com/).

This repository starts as a plain static site so it can be published with GitHub Pages. Add the website's HTML, styles, scripts, and assets here. The current `index.html` is a temporary placeholder.

## GitHub Pages setup

1. Create a GitHub repository and push this project to its default branch.
2. In **Settings → Pages**, set the source to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` deploys the repository root whenever you push to `main` (and can also be run manually).
4. In **Settings → Pages → Custom domain**, enter `www.orderologyorganizing.com` and save. The repository includes a `CNAME` file for that domain; DNS must also point to GitHub Pages before the domain will serve the site.

GitHub Pages serves static files. Features that require a server, such as private APIs or server-side form handling, need an external service or a separate backend.
