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


[**somdeep/Statball**](https://github.com/somdeep/qualstatball)

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

## Fan Culture & Match Day Experiences

_Exploring the human side of football: traditions, atmospheres, and community rituals._

### Non-League Match Day Culture

The National League and lower tiers of English football (often called "non-league") offer a uniquely authentic match day experience that stands apart from the commercialised top flight. Community-driven research, fan surveys, and club campaigns highlight several core traditions and values:

- **Non-League Day** – An annual event held during international breaks, organised by [nonleagueday.co.uk](https://nonleagueday.co.uk/) and supported by the [Football Supporters' Association](https://thefsa.org.uk/news/non-league-day-2025/). Top-flight fans are encouraged to visit their local non-league ground, promoting affordable, volunteer-led community football. Participants share photos on social media using #NLD and can win prizes including mystery football kits and £100 for their local club.

- **Authenticity & Community** – As described by fan culture researchers, non-league culture is "built on proximity, shared experience, and a deep-seated connection to the local community." Supporters are the lifeblood of their clubs, forging connections that extend far beyond the 90 minutes of match time. A 2026 LiveScore fan survey of 2,000+ non-league fans found that atmosphere, community, social connection, and being close to the action are the biggest reasons fans value the matchday experience.

- **The Social Club** – The pre-match ritual centres on the clubhouse or social club: a welcoming, affordable hub where fans, club officials, and sometimes players mingle freely — a world away from corporate hospitality.

- **Food & Drink** – The "Footy Scran" revolution: local bakeries serve legendary steak & ale pies with mash and gravy. The traditional pie remains king, but 2026 has seen gourmet stadium dining options emerge at non-league grounds.

- **Physical Programmes** – In an increasingly digital world, the matchday programme is one of the last tangible traditions — a few pounds that directly support club finances and provide a unique souvenir of local history, manager notes, and player interviews.

- **Freedom of the Terrace** – No assigned seats, no VAR delays — fans can stand anywhere, change ends at half-time, and experience football unfiltered and close to the action.

- **Traditions & Rituals** – Every club has its own pre-match traditions: specific pubs fans gather in, unique chants, and seasonal rituals. Taking part in these traditions deepens the connection between supporter and club.

- **Away Days** – Travelling to support the team at away grounds is a cherished tradition across the pyramid, with grounds like The Shay (FC Halifax Town, 14,000+ capacity) offering a "Football League feel" even at non-league level.

- **Digital Engagement** – Modern non-league fans are increasingly tech-savvy: checking live stats, following half-time league tables on phones, and engaging with supporters' groups on social media and forums — blending old-school atmosphere with digital innovation.

- **Memorabilia & Collecting** – From retro shirts of landmark seasons to signed footballs, memorabilia serves as a physical reminder of unforgettable moments and the legends who shaped the club.

### Key Sources

- [Non-League Day official site](https://nonleagueday.co.uk/)
- [Football Supporters' Association – Non-League Day 2025](https://thefsa.org.uk/news/non-league-day-2025/)
- [The Non-League Football Paper – Boosting Your National League Fan Experience: 7 Golden Tips](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/)
- [The Non-League Football Paper – The Perfect Matchday: A Beginner's Guide (Feb 2026)](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/)
- [ShuttleOne – Fan Culture and Community Engagement in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/)
- [Energeo – Fan Culture in the National League North: A Deep Dive](https://energeo-project.eu/fan-culture-in-the-national-league-north-a-deep-dive/)
- [LiveScore – Non-League Fan Survey (March 2026)](https://www.livescore.com/en/media/non-league-fan-survey/)
- [Football Fan Base – National League Complete Guide](https://www.footballfanbase.com/national-league-complete-guide/)
- [Football Ground Guide – Best Away Days in Non-League Football](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html)

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
- [rodmoioliveira/football-graphs :octocat:](https://github.com/rodmoioliveira/football-graphs) - Some visualizations on passing networks
* [Last season comparison](https://compare-last-season.netlify.app), [:octocat:](https://github.com/nurgasemetey/compare-last-season) - Last season comparison tool



## Meta

**License**

The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?**

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)