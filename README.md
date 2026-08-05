# Souvik Ghosh — original academic website framework

A custom Hugo website for an academic research portfolio. The framework, layouts, styling and components were created specifically for this site and are released under the MIT License.

## Replace the two homepage images

Put your files in `static/images/` using these names:

- `condensates.jpg` — microscopy condensates image
- `reaction-network.jpg` — reaction network cartoon

Then edit `layouts/index.html` and replace:

- `images/condensates-placeholder.svg` with `images/condensates.jpg`
- `images/reaction-network-placeholder.svg` with `images/reaction-network.jpg`

Landscape, portrait and square images all work; portrait or near-square images are recommended.

## Add your LinkedIn profile

Open `hugo.toml` and replace:

`linkedin = "REPLACE_WITH_YOUR_LINKEDIN_PROFILE_URL"`

with your complete LinkedIn profile URL.

## Local preview

```bash
hugo server
```

## GitHub Pages

The included GitHub Actions workflow builds and publishes the Hugo site automatically.
