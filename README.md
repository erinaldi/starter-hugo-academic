# Enrico Rinaldi — personal website

Source for <https://erinaldi-1.netlify.app/>, built with [Hugo](https://gohugo.io) (extended)
and the free, MIT-licensed [HugoBlox kit](https://github.com/HugoBlox/kit) (`modules/blox`), deployed on Netlify.

## Requirements

- Hugo **extended** — version pinned in `netlify.toml` (`HUGO_VERSION`)
- Go (for Hugo Modules) and Node.js 20+ with pnpm (Tailwind CSS v4 and the Pagefind search index)

## Local development

```bash
pnpm install
hugo server --disableFastRender      # live preview at http://localhost:1313
hugo --gc --minify && pnpm run pagefind   # production build into public/
```

## Layout

| Path | Content |
|---|---|
| `data/authors/me.yaml` | Profile: name, role, affiliations, links, interests, education |
| `content/_index.md` | Home page sections |
| `content/publications/` | One folder per paper (`index.md` + optional `cite.bib`, `featured.*`) |
| `content/events/` | Talks |
| `content/projects/` | Research projects |
| `static/uploads/cv.pdf` | CV linked from the menu and home page |
| `layouts/index.redirects` | Netlify redirects, including legacy URLs from the old Wowchemy site |
| `layouts/index.headers` | Netlify security headers (local fix of an upstream template bug) |

## Updating HugoBlox / Hugo

```bash
hugo mod get -u github.com/HugoBlox/kit/modules/blox && hugo mod tidy
```

Then bump `HUGO_VERSION` in `netlify.toml` and check a Netlify deploy preview before merging.
