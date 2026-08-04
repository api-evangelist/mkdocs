# MkDocs

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
