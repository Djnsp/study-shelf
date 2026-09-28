# Study Shelf

Study guides, reference pages and practice apps, published with GitHub Pages.

- `index.html` is the home page, with search and a link to every guide
- `guides/` holds the HTML guides
- `pdfs/` holds PDF guides
- `.nojekyll` tells GitHub to serve the files as-is

## Adding a new guide

1. Copy the HTML file into `guides/` using a lowercase-hyphen name, e.g. `guides/my-new-guide.html`.
2. In `index.html`, copy an existing `<li class="entry">` block inside the right section, then change the link, title, type label, description and the `data-text` search words.
3. Update the item count in that section's header.
4. Commit and push. The site updates in about a minute.
