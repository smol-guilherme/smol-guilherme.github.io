# GitHub Pages Site

This repository can host a small static site with GitHub Pages.

GitHub Pages does **not** use `README.md` as the website. The README is shown
on the repository page only. The site itself should use an HTML entry point,
typically named `index.html`.

## Setup

1. Rename `root.html` to `index.html`, or create a new `index.html` in the
   repository root.
2. Add any styles, scripts, images, and additional HTML pages alongside it.
3. Push the files to GitHub.
4. In the repository, open **Settings** > **Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose the branch containing `index.html` (usually `main`) and the
   **/(root)** folder, then save.

After GitHub deploys the site, it is available at:

`https://<your-github-username>.github.io/<repository-name>/`

For a user or organization site named `<your-github-username>.github.io`, the
URL is simply:

`https://<your-github-username>.github.io/`

`index.html` is the default homepage. Other pages can be linked directly, for
example `about.html` is available at `/about.html`.
