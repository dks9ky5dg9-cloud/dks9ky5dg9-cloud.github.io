# Gyro Block Crush Watch Site

Static marketing, support, and privacy pages for Gyro Block Crush Watch.

## Structure

- `index.html` - marketing page
- `support.html` - player support page
- `privacy.html` - privacy policy page
- `assets/` - copied web-ready assets used by the pages

The Watch version is described as an 8-stage Apple Watch edition, matching `GyroSmashEngine.watchLevels`.

The privacy policy text was adapted from the local download template, but the downloaded source file itself is not part of this repository.

## GitHub Pages

This directory is intended to be copied to the root of a dedicated `github.io` repository.

Example:

```bash
rsync -av --exclude='.DS_Store' ./project/gyro-block-crush-watch-site/ ~/Desktop/<owner>.github.io/
```

Before production launch, confirm:

- the support email address
- the legal operator name
- the final public Pages URL
