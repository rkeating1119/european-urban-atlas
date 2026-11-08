# European Urban Atlas

[Open the live atlas](https://rkeating1119.github.io/european-urban-atlas/)

A curated atlas of 161 cities across Spain (60), France (51) and Italy (50). Each city has a short summary and sections on neighborhoods, work, housing, history, culture, food, transport and weather. Compare places with seven explained editorial ratings. All regions are represented; country maps label their principal cities immediately.

The public site runs on GitHub Pages and does not depend on a local server or an open chat.

## Saved files

- `atlas-site.zip`: the validated static website. Updating this file on main triggers the permanent Pages deployment workflow.
- `atlas-source.zip`: the maintained source, editorial content, packaged geography, build scripts, audit records and continuation instructions. Unzip it and start with the enclosed README.md and RELEASE-REPORT.md. The original task attachment and historical screenshots are retained locally rather than published in this archive.
- `.github/workflows/pages.yml`: the saved publication workflow.

The reader audit passed for all 161 profiles, 57 regional jurisdictions, 291 HTML pages, 7,984 internal targets and 2,277 fragment links. Public navigation, city pages, maps and comparisons were checked at desktop, tablet and phone viewport sizes. Ratings are editorial judgments with explanations; population figures retain their dates.

## Build

Inside the extracted source folder, install the locked dependencies with pnpm, then run `pnpm build` and `pnpm test`. Python 3.13+, Node 22+ and pnpm 11 are used. Publication instructions and source attribution are in the enclosed README.md. Keep the `/european-urban-atlas` project path when rebuilding for this host.
