# European Urban Atlas

[Open the live atlas](https://rkeating1119.github.io/european-urban-atlas/)

Explore 161 cities across Spain (60), France (51) and Italy (50). Each city has a short opening, a general geographic overview and ten sections covering architecture, neighborhoods, work, housing, history, culture, food, transport, weather and atmosphere. Comparisons include seven explained editorial ratings and short descriptions of architecture, food and neighborhoods.

The maps use zoom-scaled city dots, permanent labels for the ten largest featured municipalities per country, and hover/tap cards for other places. Searchable menus open inside the site. All regions are represented. The public site runs on GitHub Pages independently of a local server or open chat.

## Saved files

- `atlas-site.zip`: the validated static website. Updating it on main triggers the saved Pages deployment workflow.
- `atlas-source.zip`: maintained source, editorial content, packaged geography, build scripts, audit records and continuation instructions. Unzip it and start with its README.md and RELEASE-REPORT.md. The original private commission attachment and historical screenshots are retained locally rather than published in this archive.
- `.github/workflows/pages.yml`: the permanent publication workflow.

The current audit passed for all 161 articles and 291 HTML pages, including 8,205 internal targets and 2,498 section links. All 538 source URLs were requested; inaccessible sources are recorded honestly. The reader prose now contains 135,102 words, about 55,300 more than the previous edition. Public menus, map, city reading and phone comparisons were checked after deployment. Ratings are explained editorial judgments, and population figures retain their dates.

## Build

Inside the extracted source folder, install locked dependencies with pnpm, then run `pnpm build` and `pnpm test`. The project uses Python 3.13+, Node 22+ and pnpm 11. The enclosed README.md explains publishing and source attribution. Keep the `/european-urban-atlas` project path for this host.
