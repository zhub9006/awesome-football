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

- [lefProg/claudia](https://github.com/lefProg/claudia) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

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

### Non-League Match Day Culture & Traditions

The **National League** (5th tier of English football) and below represent the heart of grassroots football in England. Match day culture in non-league football is defined by intimacy, community, and volunteer spirit — across 800+ clubs in Steps 1–7+ of the pyramid.

- **Intimate community atmosphere** — Grounds typically seat 500–5,000 fans. Spectators know each other by name and the club is the social hub of the local area. The pre-match pub gathering, the terrace chatter, the post-match analysis — all happen within a community that genuinely knows you.
- **Pre-match socializing** — The tradition of gathering at the local pub or the club's social clubhouse an hour or two before kickoff is a cornerstone of non-league culture.
- **Affordable access** — Match tickets are usually £5–£15, making football genuinely accessible for families and supporters on all budgets. Compare to £30–£70+ at Premier League level.
- **Volunteer-run clubs** — Many non-league clubs are sustained by volunteers — fans steward, serve at the bar, maintain the pitch, and drive the club forward.
- **Match day programmes** — Collecting and reading the weekly programme is a cherished tradition, offering match previews, player profiles, and local news. Directly supports club finances.
- **Club songs & chants** — Unique to each club, non-league chants are often more personal and local than those heard at higher levels. Organic, community-written, passed down through generations.
- **Post-match socializing** — The pub visit after the match, discussing what went right, what went wrong, is a key part of the ritual.
- **Supporter trusts** — Active supporter groups and trusts are common, often playing a formal role in club governance through the Fans United / Supporters Direct model.
- **Travel & away culture** — Despite the lower tier, dedicated followers travel to away matches, creating a strong sense of camaraderie. Fully-featured away day guides exist for top non-league grounds.
- **Ground improvement** — Fans frequently volunteer their weekends to repaint stands, lay turf, or improve facilities.
- **Charity & community links** — Non-league clubs organize charity days, youth coaching clinics, and local outreach. The club is often the largest community institution in a town.
- **The "Conference way"** — A culture that prioritizes the sport and community over commercial pressures — the original ethos of English football before the modern game's size and wealth.
- **Freedom of the terrace** — No assigned seats. Stand wherever you like. Change ends at half-time. No barriers between you and the play.
- **The "Footy Scran" revolution** — Legendary local bakery pies (£3–4), mash & gravy. Arguably better stadium food than the top flight.

#### Where Fans Discuss Match Day Culture

- **[r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball)** — Groundhopping culture, bakehouse food, family-friendly stories, match day vlogs
- **[r/nonleague](https://www.reddit.com/r/nonleague)** — Match day vlogs, travel experiences, international fan perspectives
- **[r/NationalLeague](https://www.reddit.com/r/NationalLeague)** — FC Halifax Town, Torquay United match day reactions and vlogs
- **[Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/)** — Away day guides, derby coverage, programme collecting forums
- **[The Non-League Football Paper](https://thenonleaguefootballpaper.com/)** — "Perfect Matchday Experience" guide (Feb 2026), "7 Golden Tips" series
- **[Football Ground Guide](https://www.thefootballgroundguide.com/)** — "Best Away Days in Non-League Football, Top 5" with detailed ground guides
- **[ShuttleOne Network / Energeo Project](https://www.shuttleone.co.uk/)** — Fan culture analysis for National League North
- **[FSA (Football Supporters' Association)](https://www.thefsa.org.uk/)** — Non-League Day & Away Day Experience Awards 2025
- **[When Saturday Comes](https://www.wsc.co.uk/)** — Editorial: "Why more fans are turning to non-League" (Feb 2025)
- **[Downhill Second Half / Club 27 blog](https://club27.co.uk/)** — Independent non-league match day features
- **[Fan Experience Company](https://fanexperiencecompany.co.uk/)** — Non-league community engagement strategies
- **[Non League Insider](https://nonleagueinsider.com/)** — Coverage of non-league's growing popularity
- **[TheFans.io](https://thefans.io/)** — Groundhopping app and UK guide
- **[Footbeen.com](https://footbeen.com/)** — National League and non-league groundhopping guides
- **[Football Fanbase Forum](https://footballfanbaseforum.com/)** — Match day experience discussions and ground guides

#### Notable Recognition

- **FSA Away Day Experience Award 2025**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **"Perfect Matchday" guide** — The Non-League Football Paper (Feb 2026)
- **"Why more fans are turning to non-League"** — When Saturday Comes editorial (Feb 2025)

#### Modern Digital Integration

Despite old-school atmosphere, non-league fans blend grassroots tradition with technology: checking live stats on phones, following "as it stands" league tables at half-time, live-tweeting match action, following match day vloggers on YouTube/TikTok, and using ground-tracking apps like TheFans.io.

#### Recommended Reading

1. ["Why more fans are turning to non-League"](https://www.wsc.co.uk/) — When Saturday Comes, Feb 2025 editorial
2. ["Perfect Matchday Experience"](https://thenonleaguefootballpaper.com/) — The Non-League Football Paper, Feb 2026
3. ["Best Away Days in Non-League Football, Top 5"](https://www.thefootballgroundguide.com/) — Football Ground Guide
4. [Fan Culture Analysis — National League North](https://www.shuttleone.co.uk/) — ShuttleOne Network / Energeo Project
5. [FSA Away Day Experience Awards 2025](https://www.thefsa.org.uk/) — Football Supporters' Association
6. ["Fans explain why more are turning to non-league"](https://fanbanter.co.uk/fans-explain-why-more-and-more-are-now-turning-to-non-league-instead-of-watching-the-higher-levels/) — Fan Banter
7. ["The Ultimate Matchday Experience"](https://fanbanter.co.uk/the-ultimate-matchday-experience-how-fans-make-the-most-of-football/) — Fan Banter
8. [Match Day Traditions Beyond the Final Whistle](https://www.walthamstowfc.com/match-day-traditions-that-extend-beyond-the-final-whistle/) — Walthamstow FC

For a deeper dive, see the companion document: **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — featuring the full research summary, cost comparison tables, fan sentiment quotes, detailed community sources, and 10 recommended reading links.

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
