# softyways.github.io

The Softyways site: static pages, no build step, no dependencies.

| Page | Why it exists |
| --- | --- |
| `index.html` | The partner homepage linked from the Atlassian Marketplace profile |
| `privacy.html` | The privacy policy for **Permission Review for Jira**, required by the Marketplace listing |
| `privacy-mermaid.html` | The privacy policy for **Mermaid SVG Diagrams for Confluence** |
| `documentation.html` | User documentation for **Permission Review for Jira** |
| `documentation-mermaid.html` | User documentation for **Mermaid SVG Diagrams for Confluence** |
| `security.html` | The **security policy**, partner-level: covers both apps. Required by the *Security and compliance* section of the Privacy & Security tab |

`privacy.html` is the published form of `PRIVACY.md` in the app's own repository.
**When one changes, the other has to change with it** — a privacy policy that
disagrees with the app is worse than none.

⚠️ **`security.html` makes claims tied to both apps' `manifest.yml`** (scopes,
`permissions.external`, storage, pinned dependency versions). If a manifest changes,
this page changes with it — a security policy that disagrees with the manifest is what
a reviewer looks for. Added 2 Sep 2026, after `ECOHELP-160119` asked for a security
document **separate from the privacy policy**.

Edit the files, commit, push. GitHub Pages serves the root of `main`.
