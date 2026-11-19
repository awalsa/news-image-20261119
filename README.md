![News image — 19 Nov 2026](https://img.shields.io/badge/news--image-19%20Nov%202026-blue)

# The World in One Day — 19 November 2026

One image summing up the world's news of Thursday 19 November 2026, entered in
make.fun's daily news-image bounty (`news-image-20261119`).

![The World in One Day](entry.png)

## The day's news in the image

- **Trump, Xi & Putin meet in Shenzhen** — the US, Chinese and Russian leaders
  hold their first three-way summit, on the sidelines of the APEC forum.
- **Crimea Bridge hit again** — Ukraine strikes the bridge for the third time
  in a week, halting traffic.
- **Iran strikes Gulf states** — Iran widens its attacks after US strikes on
  Qeshm island, as the US and Iran exchange fire.
- **Anthropic's record IPO debut** — the AI lab raises a record amount in its
  stock market debut.
- **UN court rules on Myanmar** — the world's top court prepares to rule on
  genocide claims against Myanmar.
- **Nvidia halts chips to China** — Nvidia stops shipping H-series chips to
  mainland China.

## How it works

`main.ts` (Node 22, standard library only, no network) copies `entry.png`
to `/output/entry.png` — or to `$MAKEFUN_OUTPUT_DIR` when set, so locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The copy is byte-for-byte, so repeated runs write identical output.
