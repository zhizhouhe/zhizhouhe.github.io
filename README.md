# Zhizhou He — personal website

A single-page academic site (`index.html`) for GitHub Pages. No build step.

## Publish on GitHub Pages

1. Create a new public repository named **`<your-github-username>.github.io`**.
2. Upload `index.html` (and `photo.jpg` if you add one) to the repository root.
3. Go to **Settings → Pages**, set *Source* to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-github-username>.github.io`.

## Editing

- **Publications**: edit the `journals` and `conferences` lists in the `<script>` block near the bottom of `index.html`.
  - `if` is the journal Impact Factor. Journals are sorted by it automatically, highest first.
  - Journals with `if: null` are shown after the ones with a value, in the order of `rank`.
- **Photo**: put `photo.jpg` next to `index.html` and replace `ZH` inside `<div class="avatar">` with `<img src="photo.jpg" alt="Zhizhou He">`.
- **GitHub / LinkedIn links**: uncomment the two lines in the header and fill in your URLs.
