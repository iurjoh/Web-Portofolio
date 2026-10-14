# Web portfolio prototype

[Português (Brasil)](README.pt-BR.md)

## Demo

[![Open demo](https://img.shields.io/badge/demo-live-2ea44f)](https://csb-5ehnre.netlify.app/)

Open in your browser. No installation or terminal required. Historical prototype with placeholder projects and links.

## Idea and process

A historical static personal-portfolio prototype. Source reviewed on 2026-10-01. No dated plan, wireframes or development diary was found in the reviewed files. Existing biography text is historical page content, not newly verified credentials. This update does not change personal claims or contact destinations.

## Architecture and design

index.html and style.css define navigation, avatar/introduction, about, four project placeholders and social links. package.json comes from CodeSandbox's static template: start uses serve and build only echoes that no bundler is involved. Default branch is gh-pages, preserved here.

The project entries have placeholder titles/descriptions and # images. Navigation and Download CV links are also # placeholders. Root-relative /style.css and /images paths depend on hosting at a domain root; review them before deploying under a repository subpath. Check avatar alternative text and keyboard focus.

## Preview and deployment

```bash
python3 -m http.server 8000
```

Local command suggested, not run here. The original Netlify preview returned page content on 2026-10-01, including the four placeholder projects. That read does not prove all assets, links or mobile layout work. No deploy was changed.

## Testing and snapshots

No automated test script appears in the reviewed manifest. No browser/manual tests were run. Before using this as a current portfolio, verify project links, CV destination, assets, mobile layout and current owner-approved biography. No screenshot was added or verified; future dated captures under docs/assets/ should label placeholders honestly and avoid private CV/contact data.

## Credits and licensing

Original third-party template/code/assets and credits are preserved below. No new license is applied. The existing manifest credits CodeSandbox static-template and Ives van Hoorne and declares MIT; that declaration remains unchanged.

---

## Technology and effort snapshot

Captured from repository sources on 2026-10-14. This is a source snapshot, not a claim about production versions or the technology available at the original launch.

- **Stack at this snapshot:** HTML and CSS; package.json retains a CodeSandbox static template. Template tooling is not claimed as an original application framework.
- **Earlier record:** The original development window was not established from the reviewed files; third-party template credits remain intact.
- **Observed calendar window:** 2026-10-10 to 2026-10-10: visible PR creation/update records only. Full implementation window not established.
- **Pull requests:** 1 visible PRs: 0 open, 1 closed, captured 2026-10-14 before this documentation change. Closed does not mean merged. Deleted/recreated history is excluded.
- **Decision and reason:** A static portfolio prototype records the early structure; placeholder projects and links remain explicitly historical, not current portfolio evidence.
- **Estimated active effort:** unavailable. No reliable time log or bounded work-session reconstruction was established. Commit count and elapsed calendar time are not converted into hours.

Evidence: current dependency/source files named above, retained Git history and the repository PR list. Versions and counts are fixed to this snapshot, not live counters.
