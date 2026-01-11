# Research Paper Template

A [Quarto Manuscript](https://quarto.org/docs/manuscripts/) template for academic research papers.

## Overview

This template provides a structured starting point for writing research papers with Quarto. It includes:

- A well-organized paper structure with common sections (Introduction, Background, Methods, Results, Conclusions)
- Guidance comments on content and length for each section
- Bibliography support via BibTeX
- Multiple output formats (HTML with Hypothesis annotations enabled, with options for PDF/Typst)
- Execution caching with `freeze: true`

## Getting Started

1. Clone this repository
2. Edit `index.qmd` with your paper content
3. Update `references.bib` with your citations
4. Customize `_quarto.yml` as needed

## Rendering

Preview the manuscript:

```bash
quarto preview
```

Render the final output:

```bash
quarto render
```

## Structure

| File | Description |
|------|-------------|
| `index.qmd` | Main paper content |
| `_quarto.yml` | Quarto project configuration |
| `references.bib` | Bibliography entries |
| `_manuscript/` | Rendered output directory |

## Output Formats

The template is configured for HTML output by default with [Hypothesis](https://hypothes.is/) annotations enabled for collaborative review. Uncomment the relevant lines in `_quarto.yml` to enable PDF or Typst output.

## Further enhancements

* manage your bibliography with `Zotero`, i.e. automatically export to the `.bib` file

## License

Feel free to use and adapt this template for your research.
