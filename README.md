# nmaahc.github.io

Documentation of audiovisual and time-based media processes at the
Smithsonian National Museum of African American History and Culture.

Built with [MkDocs](https://www.mkdocs.org/) and the
[Material theme](https://squidfunk.github.io/mkdocs-material/).

## Preview locally

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Site will be at http://127.0.0.1:8000 with live reload.

## Adding or editing content

All Markdown lives under `docs/`. Update the `nav:` block in `mkdocs.yml`
to place new pages in the sidebar.

## Deploy

```sh
mkdocs gh-deploy
```

This builds the static site and pushes it to the `gh-pages` branch, from
where GitHub Pages serves it.

## Legacy Jekyll site

The previous Moonwalk/Jekyll site is preserved in
[`_jekyll_arch/`](_jekyll_arch/) for reference.
