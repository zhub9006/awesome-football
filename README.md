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
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) - reproducible backtest of a open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930-2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks [settled publicly](https://footytips.io/track-record/) after each match, including the misses.

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
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), [data.world](https://data.world/dcereijo/player-scores), [streamlit](https://transfermarkt-datasets.herokuapp.com/), [awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats

Statsbomb : https://statsbomb.com/

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, `ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

To learn how to install, configure and use SoccerData, see the [Quickstart guide](https://soccerdata.readthedocs.io/en/latest/usage.html). For documentation on each of the [example notebooks](https://soccerdata.readthedocs.io/en/latest/datasources/) and [API reference](https://soccerdata.readthedocs.io/en/latest/reference/).

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

## ⚽ Football Culture & Fan Experiences

A new section documenting the match day traditions, community practices, and supporter experiences of the National League and wider non-league football pyramid.

#### The 3 A's Framework: What Defines Non-League Match Days

| Principle | Non-League | Premier League |
|-----------|-----------|--------------|
| **Affordability** | £5–15 tickets; ~£300 for 20 away days | £30–100+ tickets; £1,500–£3,000+ |
| **Accessibility** | Walk-on gate, 20 min entries before kick-off | Book in advance; 45+ min queue before kick-off |
| **Accountability** | Volunteer-run; chairman knows your name | Anonymous corporate ownership |

#### 13 Core Match Day Traditions
1. 🍺 **The Pub Signal** — Pre-match pub gatherings where fans debate team news
2. 🚶 **The Walk to the Ground** — Communal stroll through town streets, building camaraderie
3. 🎫 **The Turnstile Ritual** — Purchasing a paper programme and ticket at the gate
4. 📝 **The Programme Purchase** — A £2–4 paper collectible supporting club finances
5. 🥧 **The Pie, Mash & Gravy** — The culinary centrepiece: local bakery pies, creamy mash, rich gravy
6. 🏠 **The Social Club / Clubhouse** — Volunteer-run hub where fans, officials, and players mingle freely
7. 🏟️ **The Terraces** — Open standing, change ends at half-time, no barriers to the action
8. 📣 **The Manager's Half-Time Chat** — Direct, intimate address to the terrace
9. 👁️ **The Post-Match Digestion** — Staying to replay key moments after the final whistle
10. 🍻 **The Pub Finish** — After-game pints in the social club or nearby pub
11. 🤝 **The Away Day Reception** — Welcoming visitors with open arms and local recommendations
12. 🏙️ **The Community Connection** — The club *is* the community
13. 💪 **The Loyalty Cycle** — Watching through ups and downs, loyalty becomes pride

#### Fan Sentiment Highlights
> "Walk into any non-league ground on a Saturday afternoon and you'll see it: handshakes at the gate, familiar nods at the bar, and someone talking tactics over a pint of bitter." — *The Non-League Football Paper, 2025*
> 
> "Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging." — *The Non-League Football Paper, 2025*
> 
> "The best part of the non-league experience is the freedom of movement. Most grounds allow you to stand wherever you like." — *The Non-League Football Paper, 2026*
> 
> "55% of PL fans are now open to attending NL matches." — *LiveScore NL Fan Survey, 2026*

#### Cost Comparison: Non-League vs. Premier League (per away day)

| Item | Non-League | Premier League | Difference |
|------|---------|----------|---|
| Ticket | £5–15 | £30–100+ | 4–5× |
| Programme | £2–4 | £5–8 | ~2× |
| Food & Drink (pie + pint) | £5–8 | £12–18 | ~2× |
| **Total per match day** | **£12–25** | **£50–148** | **4–8×** |

#### Notable Recognition (2025–2026)
- 🏅 FSA Away Day Experience 2025: Falmouth Town AFC (Cornwall)
- 🏅 FGG Best Away Days 2026: Falmouth, Halifax, Torquay, Farnham Town, Lewes
- 📊 LiveScore NL Fan Survey 2026: NL South & Isthmian Premier hit 10-year high attendances
- 📅 Non-League Day 2026: 15th anniversary of annual open-doors events

#### Community Discussion Platforms
| Platform | URL |
|----------|-----|
| Reddit: r/nonleaguefootball | reddit.com/r/nonleaguefootball |
| Reddit: r/nonleague | reddit.com/r/nonleague |
| Reddit: r/NationalLeague | reddit.com/r/NationalLeague |
| NonLeagueMatters | nonleaguematters.co.uk/forums |
| TheFans.io | thefans.io |
| Football Fanbase Forum | footballfanbase.com/forum |

#### Publications
The Non-League Football Paper (match day guides, fan interviews), Football Ground Guide (away day reviews), When Saturday Comes (journalism), Lower Block (culture analysis), Non League Insider, MatchCentre, Verge Magazine

> 📄 **Full deep-dive research document** (traditions, timeline, verbatim quotes, regional variations, bibliography) →  [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)

## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - World Cup 2014 information
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli) - WC 2014 standings and scores CLI
- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers
- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - Rails app for managing soccer leagues
- [standings gem :octocat:](https://github.com/scottluptowski/standings) - Terminal European football standings
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - Python CLI for league tables and scores

[more apps in original repo...]

# Meta

_This awesome series is curated for the open data / football community._

**Contributions welcome.** PRs and issues are open. All content is dedicated to the public domain.

The repository owner is [@openfootball](https://github.com/openfootball).