---
weight: 20
---

# Documentation

Thanks for helping improve Gaea's documentation.

## Documentation Structure

The documentation sources live under `docs/docs/`.

- `docs/mkdocs.yml`: MkDocs configuration.
- `docs/docs/`: all Markdown pages shown on the website.
- `docs/docs/assets/`: images used in documentation pages.
- `docs/_custom/`: MkDocs theme customizations.

Inside `docs/docs/`, the main sections are currently:

- `the-basics/`: general guides and how-tos for using Gaea.
- `tutorials/` : step-by-step guides for specific generation techniques.
- `contributing/`: guidelines for contributing to the documentation and code.
- `graph_nodes/`: detailed information about Gaea's graph nodes. Theses are generated using the internal **Gaea Documentation Toolkit** plugin.

## Local Setup

From the repository root, install documentation dependencies:

```bash
pip install -r ./docs/requirements.in
```

Then start a local preview server:

```bash
mkdocs serve --livereload
```

The docs will be available at:

`http://127.0.0.1:8000`

## Writing Guidelines

### Tone and Language

- Write in clear English.
- Prefer concise, practical explanations.
- Explain *why* a step is needed, not just *what* to click.

### Page Structure

- Use one H1 title (`#`) per page.
- Use H2/H3 sections to keep long pages scannable.
- Keep paragraphs short.
- Use ordered lists for step-by-step workflows.

### Front Matter and Navigation Order

This project uses [`mkdocs-nav-weight`](https://github.com/shu307/mkdocs-nav-weight).

If you want to control page order in a section, add front matter:

```yaml
---
weight: 10
---
```

Lower weights appear earlier.

### Links and References

- Use relative links between pages (for example `../the-basics/generator.md`).
- Prefer stable links to external resources.
- Verify every new link in local preview before opening a PR.

### Images

- Put images in `docs/docs/assets/` (or a relevant subfolder).
- Use descriptive filenames.
- Keep images focused and readable.
- Add meaningful alt text in Markdown image syntax.

## Contributing Graph Node Documentation

Most pages in `docs/docs/graph_nodes/` are generated with the internal **Gaea Documentation Toolkit** plugin.

When working on node documentation:

1. Update node descriptions and metadata in the corresponding node scripts when possible.
2. Regenerate node docs/images with the toolkit.
3. Copy generated files into the documentation tree.
4. Verify rendering locally with MkDocs.

## Pull Request Checklist

Before opening your PR, check that:

1. The page renders correctly with `mkdocs serve`.
2. New links are valid.
3. New images load and are not oversized.
4. The change is scoped (one topic per PR whenever possible).
5. Grammar, spelling, and headings are reviewed.

## Where to Report Documentation Issues

If you find a docs bug (broken link, outdated content, typo), open an issue in the documentation repository:

- https://github.com/gaea-godot/rtd-docs

For addon code issues, use the main repository issue tracker instead:

- https://github.com/gaea-godot/gaea/issues

## Thank You

Small fixes are valuable. A typo fix, a clearer sentence, or a missing step can save a lot of time for other users.

