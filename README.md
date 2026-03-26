# Soochi

A quiet register of things I have made.

Minimal. Static. No build step.

------------------------------------------------------------------------

## What this is

Soochi is a small, vintage-styled index of projects.\
It reads from a single `data.json` file and renders a clean list in the
browser.

Projects are grouped into: - **Tools** --- things built with purpose -
**Toys** --- things built out of curiosity

------------------------------------------------------------------------

## Structure

    .
    ├── index.html
    └── assets/
        └── data.json

------------------------------------------------------------------------

## Adding a project

Edit `assets/data.json`:

``` json
{
  "name": "Project Name",
  "description": "Short note.",
  "url": "https://github.com/yourname/project",
  "type": "tool"
}
```

**Fields:** - `name` --- title shown - `description` --- one-line note -
`url` --- link target - `type` --- "tool" or "toy"

------------------------------------------------------------------------

## Running locally

Do not open with `file://`.

Use a simple server:

``` bash
python3 -m http.server
# or
npx serve
```

Then open: http://localhost:8000

------------------------------------------------------------------------

## Deploy

Works with GitHub Pages: - Push repo - Enable Pages - Done

------------------------------------------------------------------------

## Design notes

-   Serif fonts, parchment tones
-   Low noise, high readability
-   No build step

------------------------------------------------------------------------

## Name

Soochi (सूची) --- a list, an index.

------------------------------------------------------------------------

## License

MIT
