# krzjablonski.github.io

## Legion Builder

[Open the landing page](https://kjablonski.tech/legion-builder/).

`legion-builder/` is the static landing page for the Legion Builder Android
app. The source lives in the legion_builder_v3 repo under `mobile/website/`;
copy that folder's contents here to update it.

The download links start as "Coming soon". To go live, change the attributes
on the page's `<html>` tag:

- `data-play="live"` shows the Google Play links.
- `data-apk="live"` shows the direct APK links. Put the file at
  `legion-builder/downloads/legion-builder.apk` first.

## Snejkmaster

[Play the showcase](https://kjablonski.tech/snejkmaster/).

`snejkmaster/` contains the static output of the Snejkmaster project's
`npm run build:showcase` command. It includes only the English showcase,
the `master-v2` model and its browser runtime; the lab is excluded.

To update it, replace this directory with the contents of a fresh
`dist-showcase/` build and merge into `main`. GitHub Pages publishes the
repository root. Reverting the deployment commit restores the previous site.
