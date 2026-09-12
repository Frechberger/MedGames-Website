# MedGames Website

Static GitHub Pages website for MedGames. The files live in the repository root so GitHub Pages can publish them from `main` and `/(root)`.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish on GitHub Pages

1. Create a new **Public** repository on GitHub.
2. Keep the repository empty when creating it (no README or `.gitignore`).
3. Add the GitHub repository as the `origin` remote.
4. Push the local `main` branch.
5. Open **Settings → Pages**.
6. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then **Save**.

The website URL will normally be `https://<github-username>.github.io/<repository-name>/`.

Before launch, replace `[support email to be added]` with the real support address in `privacy.html` and `support.html`, and replace the “Coming to the App Store” label when an official App Store URL exists.
