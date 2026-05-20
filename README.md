# skilldiv
Documents

## Documentation site

I scaffolded a GitHub Pages documentation site under the `docs/` folder. You can add and edit documentation pages in the `docs/` directory; the site includes a starter set of pages:

- `docs/index.md`
- `docs/getting-started.md`
- `docs/architecture.md`
- `docs/api.md`
- `docs/contributing.md`

To publish using GitHub Pages, in your repository Settings → Pages, set the source to the `main` branch and the `/docs` folder. GitHub will publish the site automatically.

To preview locally using Jekyll:

```bash
gem install jekyll
jekyll serve --source docs --config docs/_config.yml
```

Notes:
- The site uses a minimal Jekyll config (`docs/_config.yml`) with the `minima` theme.
- If you prefer a different static site generator (MkDocs, Docusaurus), I can scaffold that instead.

