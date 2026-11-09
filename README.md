# speedysrvservice.com

**Looking for Speedy's RV Service? Visit [speedysrvservice.com](https://speedysrvservice.com/).**

This repository preserves the single-page retirement notice for Speedy's RV
Service. The business is no longer active. This is the website's source repository,
not a service booking or support channel.

## Website files

The original HTML, stylesheet, and logo are stored unchanged under `src/`:

```text
src/
  index.html
  content/
    root.css
    logo.jpg
```

There are no dependencies or build steps. Open `src/index.html` in a browser to
preview the page.

## Updates and deployment

Updates are committed and pushed directly to `main`. Do not create pull requests
for this repository.

Every push to `main` runs `.github/workflows/deploy-pages.yml`, which publishes
the contents of `src/` to GitHub Pages. The workflow can also be run manually
from the Actions tab.

The site is initially hosted at
[travisgosselin.github.io/speedysrvservice.com/](https://travisgosselin.github.io/speedysrvservice.com/).
The custom domain will be moved separately; no custom domain is configured by
this repository.
