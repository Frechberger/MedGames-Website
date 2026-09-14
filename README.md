# MedGames Website

Static website for MedGames. The public files live in `dist/` and include the responsive landing page, privacy policy, and support page.

## Support address

The public support address is `tobias@frech-online.net`. If it changes, update the `mailto:` links in `dist/privacy.html` and `dist/support.html`.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000 --directory dist
```

Then open <http://localhost:8000>.

## Publishing

The support email and privacy wording are in place. The site is deployed through the hosting configuration in `.openai/hosting.json`.

Before launch, replace the “Coming to the App Store” label when an official App Store URL exists.
