# Awesome Series @ Planet Open Data

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

## V2 -  What's News in 2022

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

Checkout this dataset also in: 
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), 
[data.world](https://data.world/dcereijo/player-scores),
[streamlit](https://transfermarkt-datasets.herokuapp.com/),
[awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_,
`ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names
and identifiers across datasets. Data is downloaded when needed and cached
locally.

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

_Explorations of match day traditions, supporter culture, and community identity across the English non-league pyramid._

- [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md) — Comprehensive research summary covering 12 key match day traditions, fan sentiment data (2,000+ respondents), resource directory, and further reading list
- [NON-LEAGUE-QUICK-REFERENCE.md](NON-LEAGUE-QUICK-REFERENCE.md) — Concise companion reference card with 12 traditions table, top grounds recommendations, and community platform links

### Key Themes at a Glance

| Tradition | Summary |
|-----------|----------|
| The Pub Signal | Match day begins at the local pub — cask ale, catching up, walking to the ground together |
| Intimate Grounds | Capacities from hundreds to thousands; every voice heard, close to the pitch |
| Freedom of the Terrace | Stand anywhere, change ends at half-time, no assigned seats, no barriers |
| Pie & Mash | Legendary steak & ale pies with creamy mash — the iconic non-league meal |
| Physical Programme | Paper programmes for a couple of pounds — local history, manager notes, player interviews |
| The Clubhouse | Community social club where fans, officials, and players mingle freely |
| Supporters' Trusts | Fan governance through Supporters Direct, MyFootballClub — real ownership power |
| Volunteer-Run | From chairman to kit man — entirely volunteer-run, genuine community pride |
| Local Derbies | Fierce, personal, organic rivalries rooted in geography and history |
| FA Cup Giant-Killings | Annual FA Cup/Trophy upsets create electric, unforgettable atmospheres |
| Groundhopping | Active community visiting and documenting non-league grounds across England |
| Non-League Day | Annual awareness event celebrating grassroots football match day culture |

### Community Discussion Platforms

- [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball/) — Reddit community for non-league football discussions
- [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) — Reddit community dedicated to the National League
- [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/) — Active forum for non-league match reports and discussions
- [Groundtastic](https://www.groundtastic.co.uk/) — Magazine for non-league ground culture and atmosphere
- [The 92nd Named Enemy](https://www.92ndnamedenemy.com/) — Groundhopper's guide to non-league grounds

### Fan Survey Highlights

- **LiveScore Survey (March 2026)** — 2,000+ non-league fans surveyed; affordability, community belonging, and authenticity rank as top motivations
- **FSA Away Day Experience Awards** — Annual awards recognizing outstanding non-league match day experiences
- **Non-League Day** — Annual awareness event drawing attention to the grassroots game

### Recommended Reading

- [The Perfect Matchday](https://www.thenonleaguefootballpaper.com/guest-posts/604687/) — Beginner's guide to non-league match day essentials (The Non-League Football Paper, Feb 2026)
- [The Heart & Soul of Football](https://www.thenonleaguefootballpaper.com/features/the-heart-and-soul-of-football/) — Chris Dunlavy argues non-league remains a haven for freedom, flare, and entertainment
- [Fan Culture in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/) — Deep analysis of community engagement and match day traditions

### Full Documentation

See detailed files: [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md) and [NON-LEAGUE-QUICK-REFERENCE.md](NON-LEAGUE-QUICK-REFERENCE.md)

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_