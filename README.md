# Premier League Control Room Guide

## What This Game Is

Premier League Control Room is a browser football-management game built from the FC26 Premier League player database. The published game includes 609 Premier League players, player cards, team budgets, transfer negotiations, squad building, training mini-games, injuries, youth academy, league seasons, cup matches, penalties, and multi-season career progression.

The published website file is:

`index.html`

This is a static HTML game. It can be uploaded to GitHub Pages or another static website host and played from a normal web link.

## What Is Included Now

- 609 Premier League player cards
- Clickable team budget table
- Transfer Market with buying, selling, swaps, budget filters, and negotiations
- Starting XI builder with drag and drop
- More formations and smarter Auto XI selection
- Live matches and quick sims
- 38-game Premier League season
- Multi-season career mode
- Team-dependent board expectations and new-season budgets
- Player rating changes over many seasons
- Training Center with 30 yearly training sessions
- Training mini-games that affect next-season stats
- Position Lab for trying players in new positions
- Youth Academy with 15-17 year old high-potential players
- Tiredness, injuries, Recovery Center, and Break Center
- Premier Cup with league phase, knockouts, and penalties
- Starting XI intro and lineup placement animations

## How To Play

### 1. Choose A Team

Start from the main dashboard. The budget table shows every Premier League team and its starting money for transfers.

Click a team in the table to filter the game to that club. You will see only that team's player cards and can begin building the squad.

### 2. Browse Player Cards

Each player card shows:

- overall rating
- position or positions
- face image
- club
- nationality
- age
- shirt number
- main stats
- potential
- market value
- fitness and injury status when relevant

Outfield players show PAC, SHO, PAS, DRI, DEF, and PHY. Goalkeepers show DIV, HAN, KIC, REF, SPD, and POS.

### 3. Use The Transfer Market

The Transfer Market lets you improve the squad before and between seasons.

You can:

- buy players
- sell players
- offer cash
- offer a player plus money
- accept or reject counter offers
- search players by budget range

The market is negotiated instead of automatic. Other clubs can reject, counter, or accept. Selling is also balanced, so buyers do not always accept market price.

Completed deals show a small signing animation, and bought players become part of your team.

### 4. Build The Starting XI

Use the Starting XI area to build your team.

You can:

- choose a formation
- drag players into positions
- use Auto XI
- clear the XI

The game blocks impossible choices, such as putting a goalkeeper at striker. Auto XI tries to use the highest-rated team possible, including reasonable alternate positions.

When a player is placed, the game shows a big visual announcement like:

`THIS IS MANCHESTER CITY ST, E. HAALAND`

### 5. Train Players

The Training Center gives 30 training sessions per season.

Training does not upgrade the player immediately. It creates next-season improvement. Younger and higher-potential players improve more. Older players can still improve, but usually only a little.

Training mini-games include:

- shooting and passing
- pace and dribbling
- defending and physical
- goalkeeper saves

The grade you get in the mini-game changes how much the player can improve. For example, pace and dribbling training helps PAC and DRI, while goalkeeper training helps GK stats.

Each drill shows a small player animation with the selected player's shirt, name, and number.

### 6. Try New Positions

The Position Lab lets you test players in new positions. It can be used for up to 8 players in a season.

A player does a small position trial. If it goes well, the new position can be added to that player's position list.

### 7. Manage Fitness And Injuries

Players can get tired during the season. Tired players perform worse and may ask to be substituted during matches.

Injuries can happen, but they are designed to be noticeable without taking over the game.

Injury types:

- small injury: 2-4 games
- medium injury: 3-7 games
- serious injury: 10-30 games, rare and mostly for very tired players

Use the Recovery Center for injured players. Without recovery, injured players do not properly heal.

Use the Break Center for tired players. A player who rests for one game returns fresh, like at the start of the season.

### 8. Play League Mode

League Mode is a full Premier League season.

Rules:

- win = 3 points
- draw = 1 point
- loss = 0 points

You choose one team and play through its fixtures. After every match, the table updates.

You can play matches live or use quick sim. Quick sim still gives points, updates fitness, and counts like a real match.

### 9. Play Matches

Live matches include:

- highlights
- stronger teams having better chances
- critical decisions
- substitutions
- tiredness
- injury risk
- computer team substitutions

The result is not fully random. Team strength, player ratings, form, fitness, lineup quality, and match events all affect the match.

Before a match or quick sim, the game can show a short Starting XI intro with cards.

### 10. Play The Premier Cup

The Premier Cup has two parts.

First, there is a short league phase of 5 games. Teams get points like a league:

- win = 3 points
- draw = 1 point
- loss = 0 points

After the 5 games, the top 16 teams qualify.

Then the cup becomes knockout:

- Round of 16
- Quarter Final
- Semi Final
- Final

The cup screen shows the next big match clearly, such as Round of 16, Quarter Final, Semi Final, or Final.

If a knockout match is a draw, it goes to penalties.

### 11. Penalty Mini-Game

Before penalties, you choose your penalty takers.

During penalties:

- choose where to shoot
- defend against the computer
- dive as the goalkeeper
- use 6 zones: down left, down middle, down right, up left, up middle, up right

The penalty animation shows small human players wearing the club shirt, name, and number.

### 12. Continue Across Seasons

At the end of a season, the game evaluates your year.

The next budget depends on:

- which team you manage
- where the team was expected to finish
- where you actually finished
- how good or bad the season was

A big club that underperforms gets a worse budget. A smaller club that overperforms gets rewarded.

Player ratings also change between seasons. Young high-potential players are more likely to grow. Older stars are more likely to drop.

If the team has more than one very bad season, the board can sack the manager.

## Publishing To GitHub Pages

For the website version, upload the files in this folder:

`/Users/lioros/work/Fifa/publish`

The most important file is:

`index.html`

On GitHub, replace the old `index.html` with the new one and commit the change. GitHub Pages usually updates in a few minutes.

If player images do not appear online, upload the full published version again. The game uses image links and embedded data from the generated HTML, so the newest `index.html` should be the file used online.

## Suggested Screenshots For NotebookLM

Good screenshots for a video guide:

1. Main dashboard with the title and budget table.
2. Player cards after selecting a team.
3. Transfer Market with budget filters.
4. Transfer negotiation with reactions.
5. Signing animation after a completed deal.
6. Starting XI builder with formation.
7. Training Center mini-game.
8. Recovery Center or Break Center.
9. Match Room with highlights.
10. Premier Cup knockout or penalty screen.
11. League table after matches.
12. End-of-season career summary.

On Mac, press `Command + Shift + 4` and drag around the area you want to capture.

## 1-2 Minute Video Guide Script

0:00-0:10
Welcome to Premier League Control Room, a football-management game built from the FC26 Premier League database with 609 players.

0:10-0:25
Choose a club from the budget table. Each team has a starting transfer budget, and clicking a club filters the player cards to that squad.

0:25-0:45
Use the Transfer Market to buy, sell, and swap players. Offers are negotiated with other clubs, and completed deals show a signing animation.

0:45-1:05
Build your Starting XI by choosing a formation, dragging players onto the pitch, or using Auto XI. The game checks positions and shows a lineup announcement when players are placed.

1:05-1:25
Train players through mini-games. Good grades help improve stats next season, especially for young high-potential players.

1:25-1:45
Play the Premier League season, manage tiredness and injuries, use substitutions, or quick sim matches when you want to move faster.

1:45-2:00
Compete in the Premier Cup, survive knockout rounds, win penalty shootouts, grow your squad over many seasons, and try to become the best manager in the league.

## NotebookLM Prompt

Create a 1-2 minute video guide for Premier League Control Room. Explain it as an exciting football-management game for a young football fan. Cover choosing a team, player cards, transfers, negotiations, squad building, training mini-games, injuries, league mode, Premier Cup, penalties, and multi-season career progression. Keep the tone friendly, clear, and energetic.

## Best Video Structure

1. Start with the dashboard.
2. Show team selection and player cards.
3. Show the Transfer Market.
4. Show a negotiation and signing moment.
5. Show the Starting XI builder.
6. Show a training mini-game.
7. Show the Match Room.
8. Show the Premier Cup or penalties.
9. End on the league table or next-season summary.
