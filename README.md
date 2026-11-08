# European Urban Atlas

[Open the live atlas](https://rkeating1119.github.io/european-urban-atlas/)

A saved English and Spanish atlas of 417 cities across ten countries: Spain (60), France (51), Italy (50), United Kingdom (50), Ireland (25), Germany (50), Switzerland (30), Greece (35), Norway (31) and Sweden (35). There are 123 regional pages. City articles have a short opening, general overview and 15 sections covering geography, architecture, history, work, housing, neighborhoods, culture, food, transport, weather, education, politics, LGBTQ+ life and everyday society.

Maps distinguish city dots from clickable region names. Country menus open inside the site, city lists scroll horizontally, and return links restore the prior map view. Language and optional sound controls are included. Comparisons have seven explained editorial ratings and further qualitative descriptions.

Release `33e920cbab96` is live on GitHub Pages. Deployment run 42508762817 succeeded, the public archive checksum matches the tested build, and 49 public page/asset samples passed. The site does not depend on a local server or an open browser tab.

## Saved files

- `atlas-site.zip`: complete validated static website. Updating this file on main triggers the permanent Pages workflow.
- `atlas-source.zip`: maintained source, saved English/Spanish content, packaged geography, build scripts and final audit/continuation instructions. Unzip and read README.md, PROJECT-STATUS.md and RELEASE-REPORT.md. Original task attachment and historical screenshots remain in local Git history.
- `.github/workflows/pages.yml`: established permanent publication workflow.

The strict build and reader audit pass for all 417 profiles and 1,112 routes. All 18,963 prose fields are present in both languages. The final source sweep covers 2,425 URLs; blocked/transient sources and missing comparable population values are documented honestly. Scores are qualitative editorial judgments, not measured rankings.

## Continue development

Install the locked dependencies with pnpm and use `pnpm build` and `pnpm test`. Requires Python 3.13+, Node 22+ and pnpm 11. Normal builds use saved JSON; translation models are optional and are not required. Keep the `/european-urban-atlas` base path for this host. The enclosed README.md explains content maintenance, attribution and the authorized publishing flow.
