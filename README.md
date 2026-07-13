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

This package is designed to allow users to extract various world
football results and player statistics from the following popular
football (soccer) data sites:

- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid
loading of pre-collected data through the use of `load_` functions.

The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found
[here](https://github.com/JaseZiv/worldfootballR_data).


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

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, 
`ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and 
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names
and identifiers across datasets. Data is downloaded when needed and cached
locally.

To learn how to install, configure and use SoccerData, see the
`Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the
supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.





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

⚽  Football Culture & Fan Experiences

This section documents the community-driven, cultural side of English football — grassroots match day experiences, fan traditions, and the human stories that make the sport meaningful locally. It complements the project's existing data and technology focus.

### The "3 A's" of Non-League Culture

| Pillar | Description |
|--------|-------------|
| **Affordability** | Tickets typically £5–£15, matchday pies £3–4, season tickets a fraction of Premier League cost. For the price of one PL programme, you can go to 10 non-league grounds. |
| **Accessibility** | Walk-on gates, no booking required, small grounds with 20-minute average entry, town-centre locations. Fans are welcomed as part of the community, not processed as customers. |
| **Atmosphere** | Intimate, family-friendly, volunteer-run, with direct player-fan interaction. "The chairman knows your name. The player shakes your hand." (r/nonleaguefootball) |

### 13 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | The Pub Signal | Pre-match pub gatherings that serve as the unofficial kickoff |
| 2 | Intimate Grounds | Small terraced stadiums (500-5,000 capacity) where you sit close enough to hear the ball hit the woodwork |
| 3 | Freedom of the Terrace | Open standing, no assigned seats — walk in and watch |
| 4 | The Clubhouse / Social Club | Volunteer-run, affordable, where the match continues long after the final whistle |
| 5 | Pie, Mash & Gravy | The iconic £3-£4 matchday pie — as much a part of non-league as the 90 minutes |
| 6 | Physical Programme | Paper collectible programmes (£2-3) that are swapped and discussed |
| 7 | Volunteer Spirit | Fans steward, serve teas, sell programmes, mow the pitch — clubs are community-owned |
| 8 | Local Rivalries | Deep-rooted geographic derbies with community-not-commercial character |
| 9 | Chants & Songs | Organic, humorous, locally-written chants that evolve across generations |
| 10 | Family Inclusion | Kids run free, families sit together on the terraces, dogs often welcome |
| 11 | The Conference Legacy | The Football Conference (1979-2004) established the community-over-commercial ethos |
| 12 | Non-League Day | Annual open-doors event encouraging PL fans to visit local non-league clubs |
| 13 | Post-Match Socialising | Clubhouse stays open beyond full-time, players sit with fans, the ground becomes a community hub |

### Cost Comparison

| Metric | National League (Step 1) | Lower Non-League (Steps 2-7) | Premier League |
|--------|--------------------------|-------------------------------|----------------|
| Match ticket | £5-£15 | £3-£10 | £30-£70+ |
| Matchday pie | £3-£4 | £2-£3 | £5-£8 |
| Season ticket (avg.) | ~£200-£350 | ~£100-£200 | ~£1,500-£3,000+ |
| 20 away games | ~£300 | ~£100 | ~£1,500-£3,000+ |
| Entry time (avg.) | ~20 min | ~10-15 min | ~45+ min |

### Key Community Discussion Platforms

| Platform | URL | Members / Reach |
|----------|-----|-----------------|
| r/nonleaguefootball | https://reddit.com/r/nonleaguefootball | 30k+ |
| r/nonleague | https://reddit.com/r/nonleague | 40k+ |
| r/NationalLeague | https://reddit.com/r/NationalLeague | 15k+ |
| r/CasualUK | https://reddit.com/r/CasualUK | 3M+ |
| NonLeagueMatters | https://NonLeagueMatters forum | Forum |
| Nonleaguezone.co.uk | https://nonleaguezone.co.uk | Forum |
| TheFans.io | https://thefans.io | Community hub |
| Footbeen.com | https://footbeen.com | Podcast & community |
| The Non-League Football Paper | https://thenonleaguefootballpaper.com | Publication |
| Football Ground Guide | https://footballgroundguide.com | Ground reviews |
| When Saturday Comes | https://whensaturdaycomes.co.uk | Football culture mag |
| Lower Block | https://lowerblock.com | Culture analysis |
| FSA | https://thefa.com | Fan awards & advocacy |
| LiveScore NL Survey | https://vergemagazine.co.uk/non-league-fan-survey | Annual survey |

### Fan Sentiment Highlights

> "Walking into a non-league ground for the first time, I felt like I'd walked into someone's living room." — r/nonleague

> "For the price of one PL programme, you can go to 10 non-league grounds." — r/CasualUK

> "The chairman knows your name. The player shakes your hand." — Football Fanbase Forum

> "You hear the ball hit the woodwork. That's part of the game." — When Saturday Comes

> "Non-league is the best kept secret in English football." — r/nonleaguefootball

### Notable Recognition (2025-2026)

- **FSA Away Day Experience 2025** — Winner: Falmouth Town AFC; Honours: FC Halifax Town, Torquay United, Lewes FC
- **Football Ground Guide Best Away Days 2026** — Top 5 from National League to Step 4 (FLG, Mar 2026)
- **LiveScore NL Fan Survey 2026** — 55% of PL fans now open to grassroots attendance; attendance at lowest tiers at an all-time high
- **The Economist** (May 2026) — "Why football attendance is booming outside the Premier League"
- **When Saturday Comes** (Feb 2025) — Editorial on the growing appeal of non-league culture
- **Verge Magazine** (2026) — Livescore survey reveals why fans love the grassroots game

### Fan Sentiment Quotes (2024-2026)

- "It feels like family." — r/nonleaguefootball
- "Volunteer Spirit: the chairman knows your name. The player shakes your hand." — Football Fanbase Forum
- "Pie, Mash & Gravy: the £4 matchday pie is as much a part of non-league as the 90 minutes." — The Non-League Football Paper
- "For the price of one PL programme, you can go to 10 non-league grounds." — r/CasualUK
- "You hear the ball hit the woodwork. That's part of the game." — When Saturday Comes  
- "Non-League Day was the best thing that ever happened to me." — FSA Away Day Experience family

### Further Reading & Sources

- [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md) — Comprehensive research document with 3 A's framework, 13 traditions, cost comparison, verbatim quotes, 15+ discussion platforms, away day recommendations, and source bibliography
- [The Non-League Football Paper - "The Perfect Matchday"](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) (Feb 2026)
- [Football Ground Guide - Best Away Days 2026](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) (Mar 2026)
- [FSA Away Day Experience Awards 2025](https://thefa.com) — Falmouth Town AFC (Winner), FC Halifax Town, Torquay United, Lewes FC
- [LiveScore NL Fan Survey 2026](https://vergemagazine.co.uk/non-league-football-in-the-uk-livescore-survey-reveals-why-fans-love-the-grassroots-game/) — Why fans love the grassroots game
- [Lower Block - Football Terrace Culture](https://lowerblock.com/articles/what-is-football-terrace-culture/) (Jan 2025)
- [When Saturday Comes - Non-league attendance boom](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non-leagues-affordable-community-culture/) (Feb 2025)

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_