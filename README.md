# EEGManyPipelines Website

This repository contains the static website for EEGManyPipelines.

## Edit the website
- Main page content: `index.html`
- Styles: `css/style.css` (plus `css/css2*.css`)
- Images: `images/`
- Scripts: `script/`

### Quick edit workflow
1. Open `index.html`.
2. Make your text/content changes.
3. Save and preview locally in a browser.
4. Commit and push to GitHub.

## Add a News item
News items are in the `<ul>` under the `News` section in `index.html`.

- Keep newest items at the top.
- Use the same `<li>` format as existing items.
- Put links in quotes (for example: `href="https://..."`).

Template:

```html
<li><span class="date">Mon YYYY</span> Your update text. Optional link: <a href="https://example.org">Link text</a>.</li>
```

Example:

```html
<li><span class="date">Feb 2026</span> We published a new update. <a href="https://example.org">Read more</a>.</li>
```
