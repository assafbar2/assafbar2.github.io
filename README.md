# assafbar2.github.io

The root landing page for `assafbar2.github.io` — a static index of the projects published on this domain.

Before this existed, the domain root returned a 404, so agents and crawlers had no entry point to the project sites hosted underneath it. This repo is plain static HTML with no build step: GitHub Pages serves it directly.

## Contents

| File | Purpose |
|---|---|
| `index.html` | Landing page: project index, contact, JSON-LD `Person` schema |
| `llms.txt` | Machine-readable site guide, including when an agent should use this domain |
| `robots.txt` | Crawl rules, with named AI crawlers explicitly allowed |
| `sitemap.xml` | Every valid URL on the domain |
| `404.html` | Recoverable 404 pointing at the index, `llms.txt`, and the sitemap |

Project sites themselves live in their own repos and are unaffected by this one.
