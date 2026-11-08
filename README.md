# Felipe de León Sáenz Angel — academic website

This is the editable source of a single-page Quarto website. All public content is in `index.qmd`; Quarto generates the finished HTML in `_site/`.

The `gh-pages` branch is generated output. Do not edit its HTML by hand, because the next publication will replace those changes.

## Preview locally

1. Install Quarto from <https://quarto.org/docs/get-started/> if it is not already installed.
2. Open a terminal in this folder.
3. Run:

   ```bash
   quarto preview
   ```

Quarto will build the site, start a local preview, and refresh it when a source file changes.

To build the site without starting the preview server, run:

```bash
quarto render
```

The generated `_site/` directory is disposable build output and is ignored by Git.

## Publish to GitHub Pages

After reviewing the local preview, commit the source changes on `main` and publish the rendered site to `gh-pages`:

```bash
git add .
git commit -m "Update academic website"
git push origin main
quarto publish gh-pages --no-prompt
```

In the repository settings, GitHub Pages should use the `gh-pages` branch and the root directory.

## Content that still needs confirmation

- Replace the July 2026 CV PDF with a version reflecting the current Paris-Saclay/LMO affiliation.
- Confirm the preferred public email address.
- Add Google Scholar or other profiles only after confirming their URLs.
