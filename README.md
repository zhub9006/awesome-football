# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 -  What's News in 2026?

### World Cup 2026 
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)

- [uanalyse World Cup 2026 predictions](https://github.com/uananalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

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

## Football Culture & Fan Experiences

_A curated collection of resources, traditions, and community stories from non-league and National League match days in England._

### Overview

The **National League** (Steps 1–4 of the English football pyramid) and the wider non-league system represent grassroots, community-driven football that has been revitalising local communities since the 1979 Football Conference era. As a [2025 WSC editorial](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non-leagues-affordable-community-culture/) documents, an attendance boom is underway — twelve clubs at Step 3 alone are averaging over 1,000 matchday attendees, and more fans are turning to non-league football for its affordability, authenticity, and sense of belonging that higher-tier football increasingly cannot offer.

This section captures the intangible culture — the match day rituals, fan traditions, and community bonds — that makes grassroots football special. It complements the project's existing data and infrastructure focus by celebrating the human side of the sport.

### 12 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | **The Pub Signal** | Pre-match gatherings at local pubs where fans, managers, and chairmen mingle, debating lineups and setting the tone for the day. |
| 2 | **Intimate Grounds** | Small terraced stadiums putting supporters pitchside — close enough to hear the crunch of a tackle and the keeper's shouts. |
| 3 | **Freedom of the Terrace** | No assigned seats, no barriers — you can stand wherever you like and even "change ends" at half-time. Pure, unfiltered football. |
| 4 | **The Clubhouse / Social Club** | A welcoming pre-match hub where fans, club officials, and players mingle freely over cheap drinks — the heart of the community. |
| 5 | **Pie, Mash & Gravy** | The iconic "Footy Scran" culinary tradition — legendary steak and ale pies from local bakeries, far superior to factory-made hotdogs. |
| 6 | **The Physical Programme** | A collectible paper souvenir for a couple of pounds that directly supports club finances, filled with local history and player interviews. |
| 7 | **Volunteer Spirit** | Clubs powered by volunteers and supporter communities, creating genuine ownership rather than a customer experience. |
| 8 | **Local Rivalries** | Geographically close clubs with community-rooted derbies tied to local identity, history, and pride — the oldest being Sheffield FC vs Hallam FC. |
| 9 | **Family Inclusion** | Children on the pitch at full-time, free or cheap admission — genuinely welcoming spaces for the next generation of fans. |
| 10 | **Chants & Songs** | Organic, locally-written songs reflecting community identity — not copied from radio playlists, but created by and for the fans. |
| 11 | **The Conference Legacy (1979–2004)** | The Football Conference era established a distinctive culture of independence and self-governance that persists today. |
| 12 | **Non-League Day** | Annual awareness event during the international break encouraging higher-division supporters to visit their local non-league side, bridging the pyramid tiers. |

### Fan Sentiment Highlights

> "The whole town stops to watch" — local derby culture, Nonleaguezone.co.uk

> "No VAR, no big screens — pure football" — r/nonleaguefootball groundhopping community

> "Supporters are the lifeblood of their clubs, forging deep connections beyond the ninety minutes" — ShuttleOne/Energeo Project

> "78% said non-league offers a more authentic experience than top-flight" — LiveScore Fan Survey (March 2026, 2,000+ respondents)

> "Price is the top reason, but the community atmosphere is what keeps us coming back" — LiveScore Fan Survey

### Where Fans Discuss Match Day Culture

| Platform | What's Discussed |
|----------|-----------------|
| **r/nonleaguefootball** (Reddit) | Groundhopping culture, bakehouse food, family stories, volunteer spirit |
| **r/CasualUK** (Reddit) | First-timer non-league experiences, cross-sport community discussions |
| **Nonleaguezone.co.uk** | Best away day guides, derby day coverage, programme collecting |
| **NonLeagueMatters Forums** | Groundhopping discussions, blog recommendations |
| **The Non-League Football Paper** (Feb 2026) | "Perfect Matchday Experience" guide, "7 Golden Tips" for fan experience |
| **ShuttleOne Network / Energeo Project** | Fan culture analysis: Community Identity, Proximity, Traditional-Digital Blend |
| **Football Ground Guide** (2026) | Top 5 away day guides from National League to Step 4 |
| **Downhill Second Half / Club 27 blog** | Independent non-league coverage of supporters and stadiums |
| **FSA** | Non-League Day, Away Day Experience Awards |

### Notable Recognition

- **FSA Away Day Experience Award 2025**: Falmouth Town (Bickland Park), FC Halifax Town (The Shay), Torquay United (Plainmoor), Lewes FC (The Dripping Pan)
- **Non-League Day**: Annual event during international breaks with photo contests (#NLD2025), organised with FSA support
- **WSC Editorial (March 2025)**: "Why more fans are turning to non-League's affordable community culture"
- **LiveScore Non-League Fan Survey (March 2026)**: 2,000+ respondents confirming non-league's authenticity and affordability

### Top Recommended Grounds

| Ground | Club | Tier | Highlights |
|--------|------|------|-----------|
| Bickland Park | Falmouth Town | National League South | FSA Award winner, Cornwall coast setting |
| The Shay | FC Halifax Town | National League Premier | 14,000+ capacity, historic town |
| Plainmoor | Torquay United | National League South | English Riviera, sea views |
| The Dripping Pan | Lewes FC | National League South | South Downs, craft beer, WSL connection |
| Memorial Ground | Farnham Town | Southern League | Innovative pricing, community food |
| Sandygate | Hallam FC | Northern Premier | One of the oldest football grounds in the world |

### Groundhopping Culture

Groundhopping has found a natural home in non-league football: no barriers to entry, pure atmosphere (no VAR, no big screens), and community bonding through shared tips and route recommendations. Key resources include the [Football Ground Guide away day guides](https://footballgroundguide.com) and [footbeen.com's non-league groundhopping guide](https://footbeen.com/blog/non-league-groundhopping-lower-league-football).

### Modern Digital Integration

Despite the old-school atmosphere, non-league fans are increasingly tech-savvy — checking live stats on phones, following "as it stands" league tables at half-time, and blending grassroots tradition with digital engagement via podcasts, social media, and dedicated apps.

### Why This Matters for the Project

Adding a fan culture section diversifies awesome-football beyond pure data and technology. Non-league match day culture represents the community-powered heart of English football — authentic, accessible, and increasingly studied by researchers. It aligns with the open-source ethos of openness and community participation, and documents the intangible heritage that IS the sport for millions of supporters.

### Recommended Reading

1. [The Perfect Matchday Guide](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — *The Non-League Football Paper*, Feb 2026
2. [Fan Culture in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/) — *ShuttleOne / Energeo Project*
3. [Why more fans are turning to non-League](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non_leagues-affordable-community-culture/) — *When Saturday Comes*, March 2025
4. [Best Away Days in Non-League Football (Top 5)](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) — *Football Ground Guide*, 2026
5. [Passion Beyond the Premier League: Non-League Football Fan Engagement](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) — *The Non-League Football Paper*

### Conference Legacy & Pyramid Structure

The non-league pyramid below the National League (Steps 2–4) includes the **Northern Premier League**, **Southern Combination Football League**, and **Isthmian League**, each covering different regions of England. The 1979–2004 Football Conference era established the precedent for independent, community-governed football that continues to define the culture today. Clubs at every level benefit from the FSA's support programmes and the annual **Non-League Day** celebration.

### Sources

The Non-League Football Paper | ShuttleOne/Energeo Project | FA National League System | Football Ground Guide 2026 | r/nonleaguefootball | r/CasualUK | Nonleaguezone.co.uk | NonLeagueMatters | Downhill Second Half / Club 27 | FSA (Away Day Experience Awards, Non-League Day) | LiveScore Fan Survey (March 2026) | When Saturday Comes | The Perfect Matchday Guide (Feb 2026) | Energeo Project

---

*This section documents not just the data and infrastructure of football, but also the culture, community, and human experiences that make the sport meaningful to millions of supporters. Contributions welcome — see the [help repo](https://github.com/openfootball/help) or open an issue/PR.*

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
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygubs.org/gems/standings) - view European football standings from your terminal
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions) - predictions of the Deutsche Bundesliga (football league) season 2012/13
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - command line tool for league table standings, match scores and more (in Python) using an HTTP JSON API


- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game based on plone
- [sigi/bookie :octocat:](https://github.com/sigi/bookie) - a rails application to manage a soccer betting community or office pool
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel) - bet on football games with your friends
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel) - Bundesliga betting game (tippspiel)
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a little open source android app for gathering information about the austrian bundesliga
- [rodmoioliveira/football-graphs :octocat:](https://github.com/rodmoioliveira/football-graphs) - Some visualizations on passing networks
* [Last season comparison](https://compare-last-season.netlify.app), [:octocat:](https://github.com/nurgasemetey/compare-last-season) - Last season comparison tool



## Meta

**License**: The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?** Yes, you can. More than welcome. See [Help & Support »](https://github.com/openfootball/help)