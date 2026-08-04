# softyways.github.io

The Softyways site: two static pages, no build step, no dependencies.

| Page | Why it exists |
| --- | --- |
| `index.html` | The partner homepage linked from the Atlassian Marketplace profile |
| `privacy.html` | The privacy policy for **Permission Review for Jira**, required by the Marketplace listing |

`privacy.html` is the published form of `PRIVACY.md` in the app's own repository.
**When one changes, the other has to change with it** — a privacy policy that
disagrees with the app is worse than none.

Edit the files, commit, push. GitHub Pages serves the root of `main`.
