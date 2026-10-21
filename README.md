# olehsamoilenko.github.io

Keeps the old address of the AIG course site, `https://olehsamoilenko.github.io/aig-materials/`,
working. On 2026-10-21 the site moved to https://autonomous-intelligence-group.github.io/
([Autonomous-Intelligence-Group/autonomous-intelligence-group.github.io](https://github.com/Autonomous-Intelligence-Group/autonomous-intelligence-group.github.io)),
and GitHub does not redirect a Pages site when its repo is transferred.

| Path | What it does |
|---|---|
| `aig-materials/**/index.html` | Redirects each page of the old site to its page at the new address, where `course/<slug>/` is `courses/<slug>/` |
| `404.html` | Redirects any other `/aig-materials/…` link, such as a lecture PDF, the same way |
| `aig-materials/logo.png`, `logo-text.png` | Copies, not redirects: the Lab 1 READMEs embed them as images, and an image cannot follow an HTML redirect |

Do not create a repo named `aig-materials` in this account: it would take the old address over
and break GitHub's redirect to the moved repo.
