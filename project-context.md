# 전기기능사 필기·실기 문제풀이 marketing site context

## Identity and scope

- Service ID: `KOR-0031`
- Android package / iOS bundle: `app.mcyj.examprep.kor0031`
- Public repository: `MCYJ/korean-electrician-craftsman-exam-prep-web`
- Production URL: `https://mcyj.github.io/korean-electrician-craftsman-exam-prep-web/ko/`
- Source service files are read-only; this repository contains only the public app marketing/study site.

## Store state verified 2026-09-18

- Google Play exact package page returned HTTP 200.
- Apple public lookup returned one exact bundle match, track ID `6797304717`, version `1.0.1`.
- Both Store badges point only to the exact verified public records.

## Current official facts

- Q-Net item code `7780`; administering body 한국산업인력공단.
- Written: electrical theory, electrical machines and electrical installations; 60 four-option items in 60 minutes.
- Practical: electrical installation hands-on task, 270 minutes.
- Passing: written and practical each require at least 60 out of 100.
- The current specification is dated 2024-01-01 through 2026-12-31.
- Q-Net provides a public practical task and warns it can change. Session-specific supplied materials, required tools and safety clothing must be rechecked.
- The 2026 required-tools notice includes long trousers, trainers or safety shoes, and cotton or other protective gloves.

## Product and design

- Korean primary locale plus English explanation; the Korean exam is not represented as English-delivered.
- Ten substantive guides per locale plus FAQ, privacy, terms, support and contact.
- Electric-sky wiring-board visual system derived from the app's `electric_sky` design family, clearly distinct from the apricot electrical-engineer site.
- Global `word-break: keep-all` and `overflow-wrap: break-word`; only long source/contact links use `overflow-wrap: anywhere`.
- Product claims stay within the public listing: 500 independently authored questions, five mock exams, explanations, on-device progress and no required account.

## Build and QA

- `npm run build` creates static pages with canonical, hreflang, Open Graph, JSON-LD, sitemap, robots and custom 404.
- `npm run check` verifies routes, metadata, output count, global keep-all and both exact live Store identities.
- GitHub Actions publishes `dist/` to GitHub Pages.

## Work log

- 2026-09-18: Created the bilingual site with current Q-Net facts and electric-sky wiring-board design. Production evidence will be appended after publication.
