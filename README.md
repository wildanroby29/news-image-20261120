# news-image-20261120

[![make.fun](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/wildanroby29/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/wildanroby29/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

The Day in Maps — Friday 20 November 2026 in one image: 50 stories, 8 pinned on a world map, built for make.fun's ["Sum up 20 November's world news in one image"](https://make.fun/bounty/news-image-20261120) bounty.

The page opens with a dark navy header — **Friday 20 November 2026** and **50 STORIES** — then a large flat-design world map that fills most of the page, with the day's eight biggest stories pinned to where they happened: the overnight strikes on Kyiv that killed 8, the violation of Poland's airspace, the Nikkei's 5% plunge in Tokyo, Estonia closing its border with Russia, Iraq deploying forces in Baghdad, the EU–UK youth mobility deal in Brussels, GTA 6 topping $2.36bn in New York, and Saudi Arabia intercepting drones and a missile over Riyadh. Below the map are seven more stories as illustrated cards, then a numbered list of thirty-five further stories in three columns, a date check, and a region count. Fifty stories in all. All pictures are flat-design illustrations drawn for this page; all headlines and decks are set in crisp vector type.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program copies `assets/entry.png` to `out/entry.png` (or `/output/entry.png` inside the grader). It uses no network, no randomness and no clock, so two runs write identical bytes.

## Files

- `main.ts` — Node 22 entrypoint (standard library only), copies the image to the output directory.
- `assets/entry.png` — the map page, 1024×1024 PNG.
- `LICENSE` — MIT.

[make.fun](https://make.fun/bounty/news-image-20261120)
