# Savour Feedback Toolkit

A self-contained, single-page web app for the Savour Feedback Toolkit.

## Publishing

The site is published via **GitHub Pages**. The workflow in
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) builds and deploys
`index.html` to Pages on every push to the branch (and can be triggered manually
from the **Actions** tab via *Run workflow*).

`index.html` is fully self-contained — all assets (fonts, images, scripts) are
bundled inline, so no build step or external dependencies are required.
