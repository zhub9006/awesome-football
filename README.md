Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) •
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) •
[SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)

# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 -  What's News in 2026?

### World Cup 2026 
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)

- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.

- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) - reproducible backtest of an open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930-2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks [settled publicly](https://footytips.io/track-record/) after each match, including the misses.

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.

- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.

- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 -  What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[**JaseZiv/worldfootballR**](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world football results and player statistics from the following popular football (soccer) data sites:

- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid loading of pre-collected data through the use of `load_` functions.

The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found [here](https://github.com/JaseZiv/worldfootballR_data).

[**dcaribou/transfermarkt-datasets**](https://github.com/dcaribou/transfermarkt-datasets)

this project aims for three things:

1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatate 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

Checkout this dataset also in: 
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), 
[data.world](https://data.world/dcereijo/player-scores),
[streamlit](https://transfermarkt-datasets.herokuapp.com/),
[awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats

Statsbomb : https://statsbomb.com/

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, `ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

To learn how to install, configure and use SoccerData, see the `Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.



## V1  - Before 2022

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.



## Football Data Guides / Articles

_Where's the open football data?_

- [Guide to Football Data and APIs](http://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/) - The Definite Football Data List collected by Joe Kampschmid  
- [Article: Using open football data - Get ready for the World Cup in Brazil 2014 @ The Data Wrangling Blog (Open Knowledge Foundation (OKFN) Labs)](http://okfnlabs.org/blog/2014/05/06/open-data-world-cup.html) by Gerald Bauer

## Football Datasets

### World Cup

- [openfootball/world-cup :octocat:](https://github.com/openfootball/world-cup)
- [import-io/worldcup2014 :octocat:](https://github.com/import-io/worldcup2014) - World cup data
- [estiens/world_cup_json :octocat:](https://github.com/estiens/world_cup_json) - rails backend for a scraper that outputs World Cup data as JSON
- [sanand0/fifadata :octocat:](https://github.com/sanand0/fifadata) - scraping FIFA world cup data
- [pratapvardhan/FIFAWorldCup :octocat:](https://github.com/pratapvardhan/FIFAWorldCup) - FIFA World Cup data includes teams data, squad formations, clubs dominance

### England

- [engsoccerdata :octocat:](https://github.com/jalapic/engsoccerdata) - all top 4 tier football matches in England 1888-2014; collected by James Curley

### Misc

- [jokecamp/FootballData :octocat:](https://github.com/jokecamp/FootballData) - a hodgepodge of JSON and CSV football data
- [llimllib/soccerdata :octocat:](https://github.com/llimllib/soccerdata) - a collection of soccer results
- [milkysunshine91/sport_db.Football :octocat:](https://github.com/milkysunshine91/sport_db.Football) - general purpose football database
- [orlandoaleman/FootballAppResources :octocat:](https://github.com/orlandoaleman/FootballAppResources)
 

## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)


## ⚽ Football Culture & Fan Experiences

_New in 2026: Community-driven documentation on match day traditions, fan culture, and the non-league experience below the professional level._

### The 3 A's of Non-League

| Principle | Non-League | Premier League |
|-----------|-----------|----------------|
| **Affordability** | £10–25 per full away day | £50–148+ per full away day |
| **Accessibility** | Walk-on gates, no ticket lotteries, just turn up | Online releases, membership queues |
| **Accountability** | Volunteer-run clubs, chairman next to you, manager in the bar | Corporate structures, VIP boxes |

### Key Statistics (2024–2026)

| Metric | Value |
|--------|-------|
| r/nonleaguefootball members | 30,000+ (up 40%+ since 2024) |
| r/nonleague members | 40,000+ |
| r/NationalLeague members | 15,000+ |
| PL fans open to non-league matches | 55% (up from 49% in 2025) |
| Non-league fans attending in person | 73% (vs 21% of PL fans) |
| Non-league fans caring primarily about result | 23% (vs 69% PL fans) |
| Average non-league away day cost | £25–44 |
| Average PL away day cost | £70–148 |
| Non-League Day 2026 | 15th anniversary (28th March) |
| PL investment into National League clubs | £23.6M/year |

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."* — **The Non-League Football Paper**

### 13 Core Match Day Traditions

1. **The Pub Signal** — Pre-match meetup at the local pub 90 minutes before kick-off
2. **The Walk to Ground** — 5–15 minute communal stroll from the pub to the stadium, discussing last week's result
3. **The Turnstile Ritual** — No membership cards needed; just drop coins in the slot and nod at the steward
4. **Pie, Mash & Gravy** — The iconic tradition of picking up a hot pie and mash from a local bakery or clubhouse
5. **The Social Club** — Volunteer-run club where fans, officials, and sometimes players mingle for sponsorship-free pints
6. **The Terraces** — Standing areas where fans can stand anywhere, chant freely, and change ends at half-time
7. **The Manager's Half-Time Chat** — Managers address the crowd at half-time (a tradition extinct in the professional game)
8. **Post-Match Digestion** — Lingering after the final whistle to soak up the atmosphere
9. **The Pub Finish** — The post-match pint where the result is debated with pundit-level intensity
10. **Away Day Reception** — Home fans frequently welcome visiting supporters with genuine hospitality, pasties, and warmth
11. **Community Connection** — Players and managers know fans by name; clubs are embedded in local community life
12. **The Loyalty Cycle** — Following your team through promotion, relegation, and everything in between week after week
13. **The 12th Man Spirit** — Volunteer stewards, groundsmen, and bar staff who are fans first and workers second

### Fan Sentiment Quotes (2024–2026)

> *"Walk into any non-league ground on a Saturday afternoon and you'll see it: handshakes at the gate, familiar nods at the bar, and someone talking tactics over a pint of bitter."* — **The Non-League Football Paper**

> *"The best part of the non-league experience is the freedom of movement. Most grounds allow you to stand wherever you like, change ends at half-time."* — **The Non-League Football Paper**

> *"I've been to 30 different non-league grounds this season. In every single one, I've been made to feel welcome — by fans and staff alike. The managers and players are approachable; you'd never get that at Stamford Bridge."* — **r/nonleaguefootball user**

> *"The programme is the last physical connection to the club. You can't download a match day programme."* — **Fan survey response, r/nonleaguefootball**

### Notable Recognition

| Year | Event | Recipient |
|------|-------|-----------|
| 2025 | FSA Away Day Experience Award | Falmouth Town AFC |
| 2026 | FGG Best Away Days | Falmouth Town, FC Halifax, Torquay United, Farnham Town, Lewes FC |
| 2026 | Non-League Day 15th Anniversary | Celebrated 28th March |

### Community Discussion Platforms

| Platform | Type | Members/Description |
|----------|------|---------------------|
| [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball) | Reddit | 30k+; match threads, away day reports, discussions |
| [r/nonleague](https://www.reddit.com/r/nonleague) | Reddit | 40k+; broader non-league topics across all levels |
| [r/NationalLeague](https://www.reddit.com/r/NationalLeague) | Reddit | 15k+; National League (Step 1) specific |
| [NonLeagueMatters](https://nonleaguematters.co.uk) | Forum | Dedicated non-league discussion forum |
| [TheFans.io](https://thefans.io) | Forum | Football fan forum with strong non-league sections |
| [Football Fanbase Forum](https://footballfanbase.com/forum) | Forum | Community discussions on all levels of the pyramid |
| [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com) | Publication | Free daily publication; guest posts on fan culture |
| [Football Ground Guide](https://www.footballgroundguide.com) | Guide | Ground reviews, away day recommendations |
| [Lower Block](https://lowerblock.com) | Publication | Non-league culture and matchday features |
| [When Saturday Comes](https://www.wsc.co.uk) | Publication | Senior football magazine with non-league coverage |

### Top 5 Recommended 2026 Away Days

1. **Falmouth Town AFC** — Bickland Park, Cornwall. FSA Award 2025 winner. Hillside ground overlooking the coast. Local pasties and authentic Cornish welcome. The most recommended away day in 2026.
2. **FC Halifax Town** — The Shay. 14,000-capacity traditional ground with a real "Football League feel." Accessible town centre with good pubs and chip shops. Generous away support.
3. **Torquay United** — Plainmoor (the "Riviera Turn"). English seaside location. Beautiful setting combining beach, food, and football. Best for a weekend break.
4. **Farnham Town** — Memorial Ground. Innovative ticket pricing. Town-centre location rare for non-league. Emerging favourite for fans who want fresh geography. Quality food at reasonable prices (£7.50 sweet chilli fried chicken).
5. **Lewes FC** — The Dripping Pan, South Downs. Community-run club with notable equality initiatives. Locally sourced food and craft beer. Scenic setting near Brighton coast.

### Cost Comparison: Non-League vs Premier League

| Expense Category | Non-League | Premier League |
|-----------------|------------|----------------|
| Match ticket | £5–15 | £25–85 |
| Programme | £2–4 | £5–9 |
| Food & Drink | £10–20 | £20–50 |
| Travel | £5–15 | £15–40 |
| **Total per day** | **£25–44** | **£70–148** |
| **20 away days/season** | **£500–880** | **£1,400–2,960** |

Non-league match days are **4–8× cheaper** than Premier League away days.

### Full Research Document

For the complete, detailed research with the full matchday sequence timeline, regional variations, sources, and bibliography, see: **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)**

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results