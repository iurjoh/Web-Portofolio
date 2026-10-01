# Web portfolio prototype

[Português (Brasil)](README.pt-BR.md)

## Idea and process

A historical static personal-portfolio prototype. Source reviewed on 2026-10-01. No dated plan, wireframes or development diary was found in the reviewed files. Existing biography text is historical page content, not newly verified credentials. This update does not change personal claims or contact destinations.

## Architecture and design

index.html and style.css define navigation, avatar/introduction, about, four project placeholders and social links. package.json comes from CodeSandbox's static template: start uses serve and build only echoes that no bundler is involved. Default branch is gh-pages, preserved here.

The project entries have placeholder titles/descriptions and # images. Navigation and Download CV links are also # placeholders. Root-relative /style.css and /images paths depend on hosting at a domain root; review them before deploying under a repository subpath. Check avatar alternative text and keyboard focus.

## Preview and deployment

```bash
python3 -m http.server 8000
```

Local command suggested, not run here. The original [Netlify URL](https://csb-5ehnre.netlify.app/) returned page content on 2026-10-01, including the four placeholder projects. That read does not prove all assets, links or mobile layout work. No deploy was changed.

## Testing and snapshots

No automated test script appears in the reviewed manifest. No browser/manual tests were run. Before using this as a current portfolio, verify project links, CV destination, assets, mobile layout and current owner-approved biography. No screenshot was added or verified; future dated captures under docs/assets/ should label placeholders honestly and avoid private CV/contact data.

## Credits and licensing

Original third-party template/code/assets and credits are preserved below. No new license is applied. The existing manifest credits CodeSandbox static-template and Ives van Hoorne and declares MIT; that declaration remains unchanged.

---

## Original README

To access the live website please click on the link: [(https://csb-5ehnre.netlify.app/)](https://csb-5ehnre.netlify.app/)
