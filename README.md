[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/rebahan149/news-image-20261119-frontpage/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/rebahan149/news-image-20261119-frontpage/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# The Day in Full — Thursday 19 November 2026

Entry for the make.fun bounty [news-image-20261119](https://make.fun/bounty/news-image-20261119): sum up 19 November 2026's world news in one image.

A single front page that sums up one full day of world news — Thursday 19 November 2026: **36 stories, six continents, one page**, with **13 illustrated panels**.

## What the page shows

- **13 illustrated panels**, each with an original flat-vector drawing: the first Trump–Xi–Putin trilateral in Shenzhen; GTA VI's launch day, 13 years on; Anthropic's $81.3bn market debut, the biggest float on record; verdict day at The Hague in The Gambia v. Myanmar; COP31 in Antalya going to the wire with 21 issues still open; 50,000 fleeing Cyclone Akvan in Odisha; Ukraine's allies rallying in Berlin; Xi pledging $20m as APEC gathers in Shenzhen; floods shutting schools in four Florida counties; a missile threat countered over Riyadh; the UN halting refugee registration in Malaysia; Takaichi raising a detainee case with Putin; floods killing six in Kenya.
- **A "Where it happened" world map** with pins 1–13 matched to the panel stories.
- **23 more stories** (briefs 14–36): Banxico's 3–2 rate-cut minutes, Delhi's fog-bound airport, the Taliban's Herat beard order, Putin backing the draft Shenzhen Declaration, Anthropic's $26bn side placement, Volusia schools shut into Friday, the Jal Board asset seizure — and more.
- **A DATE CHECK box**: stories first reported on earlier days — the Van Gogh record sale, the Derna drug seizure, the Nature "missing billion years" paper — are named and explicitly NOT counted as Thursday news.

## How it was made

The page is a single self-contained `index.html` (offline fonts, inline SVG illustrations drawn for this entry) rendered to a 1024×1024 PNG. It was designed and built in-session with Muse, modelling the leaders' recipe — many illustrated panels, a map, dense briefs — with an original masthead, layout and artwork. Every headline and brief was checked against the day's reported record before the page was drawn; `STORIES.md` keeps the per-story verification notes, including the leads that failed the Thursday test. `main.py` emits the judged image and its dossier.

## Files

- `entry.png` — the judged image: 1024×1024 PNG, under the 1 MiB cap.
- `index.html` — the front page itself, fully self-contained (no external assets).
- `STORIES.md` — the verification record: every panel and brief with its source, plus the DATE CHECK list.
- `main.py` — the entrypoint: copies `entry.png` to the output directory and prints the dossier line.

Referred by [@anjars](https://make.fun/r/eskhvp8c) — join make.fun: https://make.fun/r/eskhvp8c
