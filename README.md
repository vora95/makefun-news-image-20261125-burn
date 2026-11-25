# makefun-news-image-20261125-burn

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/vora95/makefun-news-image-20261125-burn/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/vora95/makefun-news-image-20261125-burn/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

**One Planet, One Day** — the world news of Wednesday, 25 November 2026,
summed up in a single 1024×1024 image.

Instead of a newspaper front page, the image is a world-map infographic:
six stories pinned on a stylised world map, six featured story cards
below it, and an "ALSO TODAY" ticker of nine more stories — 15 stories
in total, all first reported on 25 November 2026.

Featured stories (pinned on the map):

1. **Ukraine hits Russian ship** — Zelenskiy confirms a drone strike on a
   cargo ship in the Gulf of Finland; Norway urges caution.
2. **Houthis hit Riyadh tower** — drone attack wounds 11 at Riyadh's
   tallest tower, Saudi civil defence says.
3. **CIA and ODNI breached** — US spy agencies hit by a cyber breach
   exposing unclassified data, sources say.
4. **Huawei convicted in US** — jury finds the Chinese firm guilty of
   trade-secret theft and bank fraud.
5. **Tankers hit in Hormuz** — Iran says three oil tankers struck by
   naval mines in the Strait of Hormuz.
6. **Quake shakes Nepal** — a 5.4-magnitude quake hits Koshi Province
   near the Chinese border.

Also today: Trump awards Giuliani the Medal of Freedom; NATO to send
early-warning aircraft to Poland; EU announces new sanctions on Russia;
Sarkozy corruption case ordered to trial; England beat Australia by
8 wickets; Fort Hood shooter seeks stay of execution; UN raises alarm
over Gaza crisis; Trump pardons turkeys Freedom and Feathers; GTA 6
released worldwide on 19 November.

## Run it

```sh
python3 main.py
```

`main.py` (standard library only) copies the shipped `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`),
verifying its SHA-256, its 1024×1024 dimensions and its size (≤ 1 MiB)
first. Running it twice produces a byte-identical file.

The image itself was drawn with `draw_entry.py` (Pillow, DejaVu fonts,
fixed seed — fully deterministic).

---

<sub>Entered on [make.fun](https://make.fun/?ref=05axmjqh&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
