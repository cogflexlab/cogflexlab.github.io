# Cognitive Flexibility (CogFlex) Lab

**Understanding how minds change**

Website for the Cognitive Flexibility (CogFlex) Lab, built with [Jupyter Book](https://jupyterbook.org/) and deployed via GitHub Pages.

## Local Build

```bash
pip install -r requirements.txt
jupyter-book build book
```

The built site will be in `book/_build/html`.

## Deployment

Pushes to `main` that modify `book/**` automatically trigger `.github/workflows/deploy-site.yml`, which builds the Jupyter Book and publishes it to the `gh-pages` branch.

To enable GitHub Pages on the repository:
1. Go to **Settings → Pages**.
2. Set **Source** to **Deploy from a branch**, and select the `gh-pages` branch (`/ (root)`).
3. Your site will be live at `https://cogflexlab.github.io/`.
