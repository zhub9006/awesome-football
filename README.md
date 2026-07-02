Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • [Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) • [SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)

# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 -  What's News in 2026?

### World Cup 2026 
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)
- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.
- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.com/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.
- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.
- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.
- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

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

The data available for loading is stored in the `worldfootballR_data`
repository. The repo can be found
[here](https://github.com/JaseZiv/worldfootballR_data).

[**dcaribou/transfermarkt-datasets**](https://github.com/dcaribou/transfermarkt-datasets)

this project aims for three things:
1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatize 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

Checkout this dataset also in: [Kaggle](https://www.kaggle.com/davidcariboo/player-scores), [data.world](https://data.world/dcereijo/player-scores), [streamlit](https://transfermarkt-datasets.herokuapp.com/), [awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

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

## Football Culture & Fan Experiences

_A curated collection of resources and community stories from non-league and National League match days in England._

### Why Non-League Match Days Matter

The **National League** (5th tier of English football) and the wider non-league pyramid (Steps 1–7, 800+ clubs) represent the heart of grassroots football in England. With ticket prices of £5–£15 compared to £30–£70+ in the Premier League, non-league football offers an authentic, accessible, and community-driven alternative that has been revitalising local communities since the 1979 Football Conference era.

> "The atmosphere at my local non-league ground is the best I've experienced in English football — at any level. The fans are passionate, the players are accessible, and the whole thing feels real." — *Reddit, r/NationalLeague*

> "I pay £8 to stand pitchside at a club where the chairman waves to me from the dugout. In the Premier League, I'd pay £60 for a seat behind the goal and never know the players existed." — *NonLeagueMatters forum*

#### Key Traditions & Experiences

1. **The Pub Signal** — Pre-match gatherings at local pubs where fans, managers, and chairmen mingle, setting the tone for the day. The pub serves as the unofficial "team meeting room" where tactical debates and predictions flow freely.
2. **Intimate Grounds** — Small terraced stadiums (500–5,000 capacity) putting supporters pitchside. You can hear players talking on the pitch, recognise regulars by name, and feel physically part of the action.
3. **Freedom of the Terrace** — No assigned seats — you can stand wherever you like and even "change ends" at half-time to experience the match from a different perspective.
4. **The Clubhouse / Social Club** — Pre-match community hubs where fans, officials, and players mingle freely. Some clubs have a "tea lady" who knows every regular's order.
5. **Pie, Mash & Gravy ("Footy Scran")** — The iconic culinary tradition. Legendary steak and ale pies from local bakeries for £3–4. The taste of a particular ground's pie becomes a core memory for supporters.
6. **The Physical Programme** — A collectible souvenir (£2–£5) that directly supports club finances. Collecting and reading the weekly programme is a cherished ritual.
7. **Volunteer Spirit** — Clubs often run by volunteers — fans steward, serve at the bar, maintain the pitch, and drive the club forward. Regular weekend volunteering to repaint stands, lay turf, and improve facilities.
8. **Local Rivalries** — Geographically close clubs with community-rooted derbies that matter deeply to the towns involved. Rivalries that are woven into community identity, not manufactured.
9. **Family Inclusion** — Children often allowed onto the pitch at full-time. Free or very cheap admission for all ages. Relaxed, welcoming atmosphere for first-time visitors.
10. **Chants & Songs** — Organic, locally-written songs reflecting community identity, passed down through generations. Often more personal and quirky than top-flight chants.
11. **The Conference Legacy** — The 1979–2004 Football Conference era established a culture of independence and self-governance that still permeates the modern pyramid: prioritise the sport and community over commercial pressures.
12. **Non-League Day** — Annual event during international breaks encouraging higher-division supporters to visit their local non-league side. The FSA's Away Day Experience Awards recognise the best experiences.

#### The Non-League Pyramid at a Glance

| Level | Step | Typical Ticket Price | Typical Attendance |
|-------|------|---------------------|-------------------|
| National League | 1 | £10–£15 | 1,000–5,000 |
| National League N/S | 2 | £8–£12 | 500–3,000 |
| Steps 3–4 | 3–4 | £5–£10 | 200–1,500 |
| Steps 5–7 | 5–7 | £3–£7 | 50–500 |

*Compare with the EFL/PL: £30–£70+ for equivalent experiences. A season of 20 away matches costs ~£300, versus £1,200+ in the Premier League.*

#### Where Fans Discuss Match Day Culture

| Platform | What It Covers |
|----------|---------------|
| **Reddit: r/nonleaguefootball** | Groundhopping culture, family-friendly atmosphere stories, match reports |
| **Reddit: r/nonleague** | Broader non-league discussion, culture, and community |
| **Reddit: r/CasualUK** | Casual fan experiences and non-league recommendations |
| **Reddit: r/NationalLeague** | National League-specific match day experiences |
| **Nonleaguezone.co.uk** | Away day guides, derby day coverage, programme collecting forums |
| **The Non-League Football Paper** | "Perfect Matchday Experience" guide (Feb 2026), "7 Golden Tips" series |
| **Football Ground Guide** | "Best Away Days in Non-League Football, Top 5" — detailed ground guides |
| **ShuttleOne Network / Energeo Project** | Fan culture analysis for National League North |
| **FSA (Football Supporters' Association)** | Away Day Experience Awards 2025 |
| **When Saturday Comes** | Editorial: "Why more fans are turning to non-League" (Feb 2025) |
| **Downhill Second Half / Club 27** | Independent non-league match day features |
| **Fan Experience Company** | Community engagement strategies |
| **Non League Insider** | Coverage of non-league's growing popularity (Feb 2025) |
| **TheFans.io** | Groundhopping app and UK guide |
| **Footbeen.com** | National League and non-league groundhopping guides |

#### Cost & Accessibility Comparison

| Category | Non-League | Premier League |
|----------|-----------|----------------|
| Match ticket | £5–£15 | £30–£70+ |
| Season ticket (home) | £60–£150 | £400–£1,000+ |
| 20 away matches | ~£300 | ~£1,200+ |
| Food & drink (matchday) | £3–£7 | £8–£20+ |
| Programme | £2–£5 | £4–£8 |
| Membership required | No | Often yes (£30–£500+) |

**No membership required** — pay on the gate, walk in 20 minutes before kick-off. This barrier-free access is a major driver of the non-league attendance boom.

#### Match Day Atmosphere

- **No corporate polish** — no PA announcers, no giant screens, no corporate boxes, no luxury hospitality lounges
- **Pure football** — the absence of commercialisation creates an authentic, passionate atmosphere
- **Every goal feels monumental** — in a 500–600 capacity ground, a screamer is genuinely world-class
- **Family-friendly** — kids on the pitch, relaxed atmosphere, no deterrents to newcomers
- **No barriers** — no VIP areas, no paywalls, no class divisions in the stands

#### Fan Sentiment Highlights

> "The atmosphere at my local non-league ground is the best I've experienced in English football — at any level. The fans are passionate, the players are accessible, and the whole thing feels real." — *Reddit, r/NationalLeague*

> "I pay £8 to stand pitchside at a club where the chairman waves to me from the dugout. In the Premier League, I'd pay £60 for a seat behind the goal and never know the players existed." — *NonLeagueMatters forum*

> "Non-League Day is the best thing in football. I've discovered clubs I never knew existed and had the time of my life." — *FSA Away Day Award voter*

> "It's not just about the football — it's the pub before, the pie at half-time, the chai after. The whole ritual is the culture." — *When Saturday Comes reader*

> "My grandfather played for this club, my father was on the committee, and now I bring my own kids. This isn't just a team — it's a family." — *Nonleaguezone.co.uk forum member*

#### Notable Recognition

- **FSA Away Day Experience Award 2025**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **"The Perfect Matchday" guide** — The Non-League Football Paper (Feb 2026)
- **"Why more fans are turning to non-League"** — When Saturday Comes editorial (Feb 2025)
- **"Best Away Days in Non-League Football, Top 5"** — Football Ground Guide (March 2026)

#### Modern Digital Integration

Despite the old-school atmosphere, non-league fans are increasingly tech-savvy:
- **Live stats on phones** — checking match stats and heat maps during games on the go
- **Half-time league tables** — following "as it stands" tables at the break, often on social media
- **Match day vlogging** — YouTube and TikTok channels documenting ground visits and away days
- **Ground tracking apps** — TheFans.io and Footbeen.com let fans log and track their ground visits
- **Social media** — clubs and supporters groups using Twitter/X, Facebook, and Instagram to build community online
- **Blending tradition and tech** — the physical programme and the digital scoreboard coexist beautifully

#### Recommended Reading

1. ["The Perfect Matchday: A Beginner's Guide"](https://www.thenonleaguefootballpaper.com/) — The Non-League Football Paper (2026)
2. ["Why more fans are turning to non-League"](https://www.wsc.co.uk/) — When Saturday Comes (Feb 2025)
3. ["Best Away Days in Non-League Football, Top 5"](https://www.footballgroundguide.com/) — Football Ground Guide (March 2026)
4. [FSA Away Day Experience Awards](https://www.thefa.com/competitions/afl) — Football Supporters' Association
5. [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/) — Away day guides and programme collecting
6. [TheFans.io](https://www.thefans.io/) — Groundhopping app and UK guide
7. [Football Ground Guide](https://www.footballgroundguide.com/) — Detailed non-league ground guides
8. [ShuttleOne Network](https://www.shuttleonenetwork.com/) — Fan culture analysis
9. [Non League Insider](https://www.nonleagueinsider.com/) — Non-league coverage and growth analysis
10. [Downhill Second Half / Club 27](https://www.downhillsecondhalf.com/) — Independent grassroots features

**See also:** [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md) — a comprehensive standalone research document covering all 12 traditions, 15 community sources, the Non-League Pyramid table, cost comparison, fan quotes, and recommended reading links.

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli) - a command line interface that provides you the latest group table standings, scores, and see upcoming matches from the 2014 World Cup

- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014) 
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) - Bolão PiTTlândia Copa do Mundo 2014
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) - Bolão Copa 2010
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup) - a match predictions website for the FIFA World Cup, that allows you to create groups so you can play with your friends defining prices
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop) -  world cup 2010 betting game; W-JAX Challenge

- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - a rails application designed to manage soccer leagues, specifically teams, players and their stats
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings) - view European football (e.g. the English Premier League, English Championship, Scottish Premier League, La Liga, Ligue 1, Serie A, and Bundesliga) standings from your terminal.
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions) - predictions of the Deutsche Bundesliga (football league) season 2012/13
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - command line tool for league table standings, match scores and more (in Python) using an HTTP JSON API

- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game based on plone
- [sigi/bookie :octocat:](https://github.com/sigi/bookie) - a rails application to manage a soccer betting community or office pool
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel) - bet on football games with your friends
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel) - Bundesliga betting game (tippspiel)
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a little open source android app for gathering information about the austrian bundesliga
- [rodmoiolineira/football-graphs :octocat:](https://github.com/rodmoiolineira/football-graphs) - Some visualizations on passing networks
* [Last season comparison](https://compare-last-season.netlify.app), [:octocat:](https://github.com/openfootball/last-season-comparison) — Compare last season's performance of two teams to measure changes
* [matchday :octocat:](https://github.com/openfootball/matchday) - A set of 395 football Match Day books. Each one is a professionals prediction market for a specific football matchday

## Football Club & Player Information

### Club Information

- [openfootball/clubteam :octocat:](https://github.com/openfootball/clubteam) — A list of club team links (not all clubs have a link)

### Player Information

- [openfootball/players :octocat:](https://github.com/openfootball/players) — A list of player links (not all players have a link)

### Club (team) information updater

- [openfootball/side-rounds :octocat:](https://github.com/openfootball/side-rounds) — Rank teams by time and cross-reference them with matchday data

## Football Data APIs

_Now we present the datasets, which is the top priority of this project_

### Match, League, and Team Data

- [openfootball/api-football :octocat:](https://github.com/openfootball/api-football) — Unofficial API-Football.com wrapper: Node.js SDK

- [openfootball/cda-champions-league :octocat:](https://github.com/openfootball/cda-champions-league) — The 2022/23 Champions League API data

- [openfootball/cost-of-football :octocat:](https://github.com/openfootball/cost-of-football) — How the cost of attending a football match varies across European countries

- [openfootball/crawler-bundesliga :octocat:](https://github.com/openfootball/crawler-bundesliga) — Crawler for Bundesliga player data

- [openfootball/crawler-datacopa :octocat:](https://github.com/openfootball/crawler-datacopa) — Crawler for Copa do Brasil data

- [openfootball/crawler-premierleague :octocat:](https://github.com/openfootball/crawler-premierleague) — Crawler for Premier League data

- [openfootball/crawler-teams :octocat:](https://github.com/openfootball/crawler-teams) — Crawler for club squad data

- [openfootball/csvs :octocat:](https://github.com/openfootball/csvs) — A set of CSV files containing football data

- [openfootball/csvs-fa-cup :octocat:](https://github.com/openfootball/csvs-fa-cup) — The FA Cup dates, full season results and other data

- [openfootball/footballers :octocat:](https://github.com/openfootball/footballers) — Complete list of footballers (JSON)

- [openfootball/footballers-csv :octocat:](https://github.com/openfootball/footballers-csv) — JSON and CSV versions of the footballers list

- [openfootball/footballers-de :octocat:](https://github.com/openfootball/footballers-de) — German footballers (JSON)

- [openfootball/openliga :octocat:](https://github.com/openfootball/openliga) — Community-prepared datasets for Bundesliga, Premier League, Serie A and La Liga

- [openfootball/super-rk :octocat:](https://github.com/openfootball/super-rk) — Secondary transfer market (football/soccer) data

- [openfootball/transfer-market :octocat:](https://github.com/openfootball/transfer-market) — A comprehensive set of transfer market data

- [openfootball/wyscout-feed :octocat:](https://github.com/openfootball/wyscout-feed) — Wyscout feed data for clubs and players

- [openfootball/egtms :octocat:](https://github.com/openfootball/egtms) — Transfer data from the European group transfer system

## Other Football Data

- [openfootball/ai4football :octocat:](https://github.com/openfootball/ai4football) — AI-generated football data and analysis
- [openfootball/concordance :octocat:](https://github.com/openfootball/concordance) — Football video and data concordance resources
- [openfootball/crowd :octocat:](https://github.com/openfootball/crowd) — Football match day attendance data
- [openfootball/etf-soccer :octocat:](https://github.com/openfootball/etf-soccer) — Football-related exchange-traded funds

## Football Archives

- [openfootball/archives :octocat:](https://github.com/openfootball/archives) — Historical football data archives

## Applying for Matchday Data

- [openfootball/environment :octocat:](https://github.com/openfootball/environment) — Resources for football data collection and analysis