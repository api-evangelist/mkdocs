# MkDocs

MkDocs is a fast, simple, and beautiful static site generator designed for building project documentation from Markdown source files. Written in Python, it reads a single YAML configuration file (`mkdocs.yml`) and converts a directory of Markdown documents into a self-contained static HTML site.

MkDocs supports multiple built-in themes (`mkdocs`, `readthedocs`), a rich plugin ecosystem via Python entry points, a live-reloading development server (`mkdocs serve`), and one-command deployment to GitHub Pages (`mkdocs gh-deploy`). Its plugin API exposes a comprehensive set of build pipeline event hooks that allow third-party plugins to customize every phase of the build, from configuration loading and file discovery through Markdown rendering and final HTML output.

- **Website:** https://www.mkdocs.org
- **Documentation:** https://www.mkdocs.org/user-guide/
- **GitHub:** https://github.com/mkdocs/mkdocs

## Artifacts

| Type | File | Description |
|------|------|-------------|
| JSON Schema | [json-schema/mkdocs-config-schema.json](json-schema/mkdocs-config-schema.json) | Schema for the `mkdocs.yml` project configuration file |
| JSON Schema | [json-schema/mkdocs-plugin-schema.json](json-schema/mkdocs-plugin-schema.json) | Schema for describing MkDocs plugin definitions and event hooks |
| JSON-LD | [json-ld/mkdocs-context.jsonld](json-ld/mkdocs-context.jsonld) | Linked data context mapping MkDocs entities to standard vocabularies |
