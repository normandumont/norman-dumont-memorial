# Norman Arthur Dumont Memorial Website

A simple static memorial website designed for GitHub Pages.

## Files

- `index.html` — main memorial page
- `styles.css` — visual styling
- `images/` — replace placeholder images with family photos

## Photo filenames to add

Place your own images in the `images` folder using these exact names:

- `hero.jpg` — large banner image at top of page
- `norman-portrait.jpg` — portrait photo
- `family.jpg` — family photo
- `cottage.jpg` — White Mountains cottage photo
- `construction.jpg` — work, union, bridge, or construction-related photo

If you do not have all photos yet, the site still works. Missing images will simply show as broken until replaced.

## Publish on GitHub Pages

1. Create a new public GitHub repository, for example: `norman-dumont-memorial`.
2. Upload `index.html`, `styles.css`, and the `images` folder.
3. Go to repository **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ root`.
6. Save.
7. GitHub will publish the site at:

   `https://YOUR-GITHUB-USERNAME.github.io/norman-dumont-memorial/`

## Optional Guestbook

For a free guestbook, consider adding Giscus after enabling GitHub Discussions:

https://giscus.app

Paste the generated Giscus script near the bottom of `index.html`, inside the Share a Memory section.
