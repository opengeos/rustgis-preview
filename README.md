# RustGIS previews

Pull request previews of [RustGIS](https://github.com/opengeos/RustGIS): its docs and web app, built
by the `docs-preview` workflow and served by GitHub Pages at
`https://preview.rustgis.app/pr-<number>/` (the app under `app/`).

The `gh-pages` branch is rewritten by that workflow on every deploy (one commit holding the open pull
requests' previews and the `CNAME` file naming `preview.rustgis.app`); a preview is removed when its
pull request closes. Nothing here is edited by hand.
