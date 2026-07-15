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

- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the I9⚽ Adding Non-League Match Day Culture & Fan Community Discussions to awesome-football

I've researched National League and wider non-league football match day culture and fan community discussions, and I'd like to contribute a comprehensive documentation file and README section to the awesome-football project.

### What This Includes

A new **NON-LEAGUE-MATCHDAY-CULTURE.md** file covering:

- **The 3 A's Framework**: Affordability, Accessibility, Accountability — the core principles that distinguish non-league match days
- **13 Core Match Day Traditions**: From The Pub Signal to The Loyalty Cycle, documenting the rituals that define non-league culture
- **The Perfect Match Day Sequence**: A full timeline from 11:00 AM to 5:00 PM showing the complete ritual flow
- **Fan Sentiment Highlights (2024–2026)**: Quotes compiled from The Non-League Football Paper, Reddit (r/nonleaguefootball, r/nonleague, r/NationalLeague), and community forums
- **Cost Comparison: Non-League vs Premier League**: Data showing non-league is 4–8× cheaper for a full match day experience
- **Regional Variations Across the UK**: North of England, Midlands, South/South West, London, and Scotland
- **Community Discussion Platforms**: Directory of Reddit communities, forums, publications, and Facebook groups
- **Notable Recognition (2025–2026)**: FSA Away Day Experience Awards, Football Ground Guide rankings, LiveScore NL Fan Survey data
- **Recommended Away Days for 2026**: Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC

### Proposed README Addition

A new **⚽ Football Culture & Fan Experiences** section should be added after the **Football Apps** section in README.md, containing a link to the new documentation file and a brief summary.

### How to Contribute

Per the openfootball/awesome-football contribution guidelines ("Contributions welcome. Anything missing? Send in a pull request."):

1. Fork the repository
2. Create a new branch (e.g., `non-league-culture-doc`)
3. Add `NON-LEAGUE-MATCHDAY-CULTURE.md` to the repo root
4. Update `README.md` to add the new ⚽ Football Culture section between Stadium Datasets and Football Apps
5. Create a Pull Request

The full content of NON-LEAGUE-MATCHDAY-CULTURE.md is ready to be added. These contributions are dedicated to the public domain and free to use, share, and build upon.