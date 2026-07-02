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

#### Where Fans Discuss Match Day Culture

| Platform | What It Covers |
|----------|---------------|
| **Reddit: r/nonleaguefootball** | Groundhopping culture, bakehouse food, family-friendly stories, match day vlogs |
| **Reddit: r/nonleague** | Broader non-league discussion, culture, and community |
| **Reddit: r/CasualUK** | Casual fan experiences and non-league recommendations |
| **Reddit: r/NationalLeague** | National League-specific match day experiences, neutral fan guides |
| **Nonleaguezone.co.uk** | Away day guides, derby day coverage, programme collecting forums |
| **NonLeagueMatters Forums** | National League discussion, away day guides, programme collecting |
| **The Non-League Football Paper** | In-depth features on match day experiences and fan engagement |
| **Football Ground Guide** | "Best Away Days in Non-League Football" with detailed ground guides |
| **ShuttleOne Network / Energeo Project** | Fan culture analysis for the National League North |
| **Football Supporters' Association (FSA)** | Non-League Day & Away Day Experience Awards (2024, 2025) |
| **Downhill Second Half / Club 27 blog** | Independent non-league coverage and match day features |
| **When Saturday Comes** | Editorial: "Why more fans are turning to non-League" (Feb 2025) |
| **Fan Experience Company** | Strategic approach to non-league community engagement and growth |
| **Non League Insider** | Coverage of non-league's growing popularity and analysis |
| **TheFans.io / Footbeen.com** | Groundhopping apps and UK guides for beginners |

#### Notable Recognition

- **FSA Away Day Experience Award 2025**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **FSA Away Day Experience Award 2024**: Multiple non-league grounds recognised
- **"The Perfect Matchday" guide** — The Non-League Football Paper (Feb 2026) documents the seven essentials: social club, food culture, programmes, terrace freedom, and digital integration
- **"Why more fans are turning to Non-League"** — WSC Editorial (Feb 2025)
- **"Best Away Days in Non-League Football, Top 5"** — Football Ground Guide (March 2026)

#### Cost & Accessibility

| Level | Step | Typical Ticket | Typical Attendance |
|-------|------|---------------|-------------------|
| National League | 1 | £10–£15 | 1,000–5,000 |
| National League N/S | 2 | £8–£12 | 500–3,000 |
| Steps 3–4 | 3–4 | £5–£10 | 200–1,500 |
| Steps 5–7 | 5–7 | £3–£7 | 50–800 |
| **Premier League** | — | **£30–£70+** | **20,000–75,000** |

- **No membership required**: Pay on the gate, walk in 20 minutes before kick-off
- **Season cost**: 20 away matches ≈ £300 (vs. £600–£1,400+ in the Premier League)
- **Food & drink**: £3–7 for a full matchday meal

Non-league football has seen a significant **attendance boom** in recent years, with COVID-19 accelerating a trend of fans seeking more authentic, community-focused football experiences.

#### Modern Digital Integration

Despite the old-school atmosphere, non-league fans are increasingly tech-savvy:
- Checking live stats on phones during matches
- Following "as it stands" league tables at half-time
- Blending grassroots tradition with podcasts, social media, and live-tweeting
- Using apps like TheFans.io to track grounds and plan away days

#### Fan Sentiment Highlights

> "It's not just about the football — it's the pub before, the pie at half-time, the chai after. The whole ritual is the culture." — *When Saturday Comes reader*

> "Non-League Day is the best thing in football. I've discovered clubs I never knew existed and had the time of my life." — *FSA Away Day Award voter*

> "The match doesn't end at the final whistle; it continues in the pub, discussing what went right, what went wrong, celebrating the goals." — *Non-league fan community*

#### Recommended Reading

1. [The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — *The Non-League Football Paper*, Feb 2026
2. [Passion Beyond the Premier League: Non-League Football Fan Engagement](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) — *The Non-League Football Paper*
3. [Making Non-League Day Happen Weekly](https://fanexperienceco.com/2021/09/making-non-league-day-happen-weekly/) — *Fan Experience Company*, Sep 2021
4. [Best Away Days in Non-League Football, Top 5](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) — *Football Ground Guide*, March 2026
5. [Fan Culture and Community Engagement in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/) — *ShuttleOne Network*
6. [WhyMore fans are turning to non-League's affordable community culture](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non-leagues-affordable-community-culture/) — *WSC Editorial*, Feb 2025
7. [How Has Non-League Grown in Popularity](https://www.nonleagueinsider.com/leagues/how-non-league-has-grown-in-popularity/) — *Non League Insider*
8. [The Enterprise National League + North & South Community (Facebook Group)](https://www.facebook.com/groups/1454597365016494/) — *Largest National League fan community on Facebook*

#### Contributing

This section is part of the [awesome-football](https://github.com/openfootball/awesome-football) project, which is dedicated to the public domain. Contributions welcome — add new traditions, update community sources, or improve the research. Send in a pull request or open an issue with your findings!

See [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md) for a standalone research document with full source references and detailed findings.