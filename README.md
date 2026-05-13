# HI RevealJS Slides Template

Reusable Quarto + Reveal.js presentation template using the HI color palette in `styles.css`.

## Template Configuration

Edit the Quarto YAML header in `index.qmd` for the talk metadata. The presenter details live in a nested `presenter:` block in the YAML frontmatter of `index.qmd`. The title slide reads the following values:

- From `index.qmd` frontmatter: `title`, `subtitle`, `author`, `institute`, `date`
- From the `index.qmd` frontmatter: the nested `presenter` fields for name, position, department, office, username, GitHub, and ORCID ID

The raw slide content lives in `slides.qmd`, while `index.qmd` is the wrapper that defines the metadata and includes the slides.

The email, GitHub URL, and ORCID URL are derived in `slides.qmd`, and the GitHub and ORCID links use Font Awesome brand icons.

Font Awesome is loaded from the web via CDN in `_quarto.yml`. If you want a local copy instead, download it from https://fontawesome.com/download and replace the CDN `<link>` with a local CSS file.

## Quick Start

Install Quarto ([get-started](https://quarto.org/docs/get-started/])), then render or 
preview:

```bash
quarto render index.qmd
quarto preview index.qmd
```

The rendered site is written to `docs/`, which can be used for GitHub Pages.

## Main Files

- `index.qmd`: Quarto wrapper entrypoint
- `slides.qmd`: raw slide body included by `index.qmd`
- `styles.css`: reusable HI theme styles
- `_quarto.yml`: project-level Quarto settings
- `img/`: place reusable background images and figures here

## Included Patterns

- Title and section divider slides
- Bullets, incremental bullets, columns, callouts, quotes, and tables
- Base R plots and optional `ggplot2` examples
- LaTeX notation with inline and display math
- Background color and background-image examples
- Speaker notes


## HI Colors

Primary:

- `#10099F`

Support:

- `#2DD2C0`
- `#00FFBA`
- `#FAC55B`
- `#FC8484`
- `#FFA05F`
- `#F5F5F5`
- `#262626`

Engineering:

- `#EB7125`
