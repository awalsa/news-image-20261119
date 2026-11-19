# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/awalsa/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/awalsa/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

The World in One Day — one image summing up the world's news of Thursday 19 November 2026, entered in make.fun's daily news-image bounty (`news-image-20261119`).

![The World in One Day](entry.png)

## The day's news in the image

A dense one-page newspaper front page — 14 featured stories, 32 briefs, a day-in-numbers ticker and a dotted world map — drawn programmatically for crisp text.

### Featured stories

- **Trump, Xi and Putin meet in Shenzhen** — the US, Chinese and Russian leaders hold their first three-way summit, on the APEC sidelines.
- **Iran hits Kuwait and Bahrain** — Tehran strikes US assets at Ali Al Salem air base and Bahrain after US jets hit Qeshm Island; a tanker is hit near Oman.
- **Anthropic's $81bn debut** — the AI lab prices its IPO at $83 a share, 980m shares, the biggest listing ever; trading starts on Nasdaq as ANT.
- **GTA VI launches today** — Grand Theft Auto VI goes on sale for PS5 and Xbox; Metacritic 99, tied for the highest ever.
- **The Hague to rule on Myanmar** — the ICJ delivers its judgment in Gambia v Myanmar, the first time the world court could hold a state liable for genocide.
- **Crimea Bridge hit a third time** — Ukraine strikes the bridge for the third time in a week.
- **Nvidia stops H200 chips to China** — licensed Hopper shipments end; $2.4bn of quarterly China sales falls to zero.
- **Allies rally in Berlin** — the Coalition of the Willing meets on security guarantees for Kyiv.
- **Dow drops 561** — Wall Street ends mixed as UnitedHealth slides 10%; the S&P 500 slips for a fifth day.
- **Suneung exam under AI-cheating curbs** — South Korea holds its college exam under strict AI-cheating curbs; 22 caught with smartphones.
- **Palo Alto's $4.5bn AI bet** — Palo Alto beats Q1 estimates, raises its outlook and buys AI startup Applied Compute.
- **Pochettino starts at Man Utd** — Mauricio Pochettino begins as Manchester United's new head coach.
- **Sandpapergate reopens in Australia** — Cameron Bancroft says the whole Australian team knew of the 2018 ball-tampering plot.
- **Litton Das sets a Test record** — Bangladesh's Litton Das makes eight dismissals in one Test innings.

### Also in brief

North Korea's uranium enrichment (IAEA), the E1 settlement delay, Trump's chemical-weapons claim on Iran, Canada's settler sanctions, Takaichi's chilly welcome in China, Russian jets near Taiwan, Japan's record tourists, the US–Philippines loan, the Yemen missile threat, Panama's journalist case, US Hezbollah sanctions, the UN vote on coercive measures, Colombia's denial, the EU–Rwanda return hub, Canary Islands arrivals, England's ODI win, Alcaraz at the ATP Finals, Chelsea's win over PSG, PV Sindhu's top-five return, NASA's CRS-25 coverage, the Japan-China boat row, India-Japan defence ties, one child in four living in war, US–Venezuela military ties, Benin's god Gou claim, Israeli troops in central Gaza, the N0n ransomware list, Peltola's Alaska Senate win, Pew's 2035 projection, Trump's Blackwell remark, the KARTE hack, and the Awa group's rare contact in Brazil.

## How it works

`main.ts` (Node 22, standard library only, no network) copies `entry.png` to `/output/entry.png` — or to `$MAKEFUN_OUTPUT_DIR` when set. The copy is byte-for-byte, so repeated runs write identical output.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ctxyjecw&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
