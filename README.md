# GitHub Pages copy

This folder contains the static website files served by GitHub Pages. The
original files in the repository root are left in place; update this copy when
you want to publish site changes.

## Publish

The repository workflow at `.github/workflows/deploy-github-pages.yml` deploys
this folder when changes are pushed to `main` or `master`, and can also be run
manually from the Actions tab. In the repository's **Settings → Pages**, set
the build and deployment source to **GitHub Actions**.

The public address will be `https://<owner>.github.io/<repository>/` for a
project site, or `https://<owner>.github.io/` when the repository is named
`<owner>.github.io`.
