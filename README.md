# Saturday 21 November 2026: 37 stories, 9 regions

[![make.fun](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/zesty-pika-87/news-image-20261121-v4-entry/rank.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/zesty-pika-87/news-image-20261121-v4-entry/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A one-page newspaper front page summing up the world's news of Saturday,
21 November 2026: 37 stories from 9 regions, drawn as a single image.

## What is on the page

- **Masthead:** the date itself, giant serif — `Saturday 21 November 2026`.
- **Numbers band:** 6 real numbers from the day (37 stories, 9 regions,
  2 US bases struck in Bahrain, 11 dead in Mexico, 24 dead in Nigeria,
  $3.8bn for GTA VI on day one).
- **Region colour bar:** 9 regions, each with its own colour; the same
  colour marks every story from that region (kickers, map pins, index dots).
- **Heroes:** the 3 biggest stories of the day, tall illustrated panels —
  Iran strikes US bases in Bahrain, Mexico seizes cartel boss Chapo Isidro,
  a Russian missile hits Kryvyi Rih.
- **Middle grid:** 10 more illustrated stories, 2 rows × 5 columns, each
  with a dateline and a named source line (`MANAMA — AL JAZEERA`).
- **Bottom band:** a numbered world map (pins 1–37) plus a numbered index
  of all 37 stories.
- **Footer:** one-line date check — `DATE CHECK: All 37 stories are from
  Saturday, 21 November 2026.`

Every story was verified against reporting from 21 November 2026 only
(BBC, Al Jazeera, The Guardian, DW, UPI, RFI, CBC and others). No story
from any other date appears anywhere on the page.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png`. The image is 1024 × 1024 px, 357,156 bytes. Two
runs write byte-identical output (verified with `cmp`). Run it
locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Entry

- Competition: [news-image-20261121](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
- Built with [make.fun](https://make.fun/?ref=1aaz13gb)
