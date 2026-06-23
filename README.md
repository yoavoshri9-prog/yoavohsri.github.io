# Premier League Control Room Guide

## What This Game Is

Premier League Control Room is a browser football-management game built from the FC26 Premier League player database. It includes 609 Premier League players, player cards, team budgets, transfer negotiations, squad building, match simulation, substitutions, and a 38-game league season.

The main game file is:

`premier-league-cards.html`

This is a static HTML game. That means it can be uploaded to a normal static website host and played from a web link.

## Best Way To Put It Online

For the cleanest public web version, rename or copy:

`premier-league-cards.html`

to:

`index.html`

Then upload that `index.html` file to a static hosting service.

Recommended options:

1. Netlify Drop
   Fastest option. Create a folder with `index.html`, then drag the folder into Netlify Drop. Netlify gives you a public link.

2. GitHub Pages
   Best option if you want to keep updating the game later. Put `index.html` in a GitHub repository, then enable Pages in the repository settings.

3. Vercel
   Good option if the project later becomes a bigger web app. Connect a GitHub repository or deploy from the Vercel dashboard/CLI.

Important: the database CSV and Python generator are not needed for people to play the current game online. They are only needed when regenerating or changing the HTML.

## Full Gameplay Steps

### 1. Choose A Team

Start from the Premier League Control Room dashboard. The top of the page shows the number of players, average overall rating, and top-rated player.

Use the budget table to click a Premier League club. When you click a team, the page filters the cards so you only see that club's players.

Each team starts with a transfer budget. For example, Manchester City starts with 200M and Liverpool starts with 150M.

### 2. Browse Player Cards

Each player card shows:

- overall rating
- position
- face image
- club
- nationality
- age
- shirt number
- main stats
- potential
- market value

Outfield players show PAC, SHO, PAS, DRI, DEF, and PHY. Goalkeepers show DIV, HAN, KIC, REF, SPD, and POS.

### 3. Use The Transfer Market

The Transfer Market is used before the league starts.

To buy a player:

1. Choose your club.
2. Choose a target player.
3. Enter a cash offer.
4. Optionally add a player swap.
5. Click Make Offer.

The other club does not always accept immediately. The coach/director reacts to the offer, and the player can also react with emoji faces. A strong offer may be accepted quickly. A weak offer may be laughed at, rejected, or countered.

To sell a player:

1. Choose one of your players.
2. Set an asking price.
3. Click Find Buyer.
4. Negotiate with the interested club.
5. Accept, counter, or walk away.

Selling is not automatic. Buyers may reject high prices, counter with a lower fee, or leave the table.

When a deal is completed, a Signing Moment animation appears with the player, new club, fee, and contract signing animation.

### 4. Build The Starting XI

Use the lineup builder to select your starting eleven.

Steps:

1. Choose a formation, such as 4-3-3 or 4-4-2.
2. Drag players into the pitch slots.
3. Fill all 11 positions.

The game blocks positions that do not make sense. For example, a goalkeeper cannot be placed as a striker.

You can also use Auto Lineup to quickly create a sensible team.

### 5. Start League Mode

League Mode lets you choose one Premier League team and play a full 38-game season.

Rules:

- win = 3 points
- draw = 1 point
- loss = 0 points

Before each match, prepare the next fixture. Your league table updates after regular matches and quick sims.

### 6. Play A Match

In the Match Room, choose:

- your team
- the computer opponent
- formation
- computer formation

You can play the match live or quick sim it.

Live match:

- the game runs with highlights
- stronger teams have a higher chance
- critical moments pause for decisions
- players can get tired
- players can ask to be substituted
- you can make tactical substitutions

Quick sim:

- instantly gives the result
- shows match highlights
- gives league points just like a regular match

### 7. Make Substitutions

During a live match, use the substitution panel.

Important rules:

- a player can only be subbed in once
- a player who was subbed out cannot come back in
- position logic is checked
- tired players may ask for a substitution

### 8. Continue The Season

After the match ends, the league table updates. Prepare the next fixture and continue until the 38-game season is complete.

## Suggested Screenshots For NotebookLM

Yes, you should add snapshots. They will make the video guide much better because NotebookLM can connect the explanation to real visuals.

Recommended screenshots:

1. Main dashboard with the title, summary, and budget table.
2. Player cards grid after clicking a team.
3. Transfer Market buy section.
4. Transfer negotiation chat with emoji reactions.
5. Signing Moment animation after a completed deal.
6. Starting XI formation builder.
7. Match Room during a live match or decision pause.
8. League table after a match.

On Mac, press `Command + Shift + 4` and drag around the area you want to capture.

## 1-2 Minute Video Guide Script

Use this as the narration plan for NotebookLM.

0:00-0:10
Welcome to Premier League Control Room, a football-management game built from the FC26 Premier League database with 609 players.

0:10-0:25
Start by choosing a club from the budget table. Each team has a starting transfer budget, and clicking a club filters the player cards to show only that squad.

0:25-0:45
In the Transfer Market, you can buy, sell, and swap players. Offers are negotiated with the other club, and both the coach and player react with emoji-style messages. If a deal is completed, a signing animation confirms the transfer.

0:45-1:05
Next, build your Starting XI. Pick a formation, drag players onto the pitch, or use Auto Lineup. The game prevents unrealistic positions, like putting a goalkeeper at striker.

1:05-1:25
In League Mode, choose a team and play a 38-game Premier League season. Wins give 3 points, draws give 1, and losses give 0.

1:25-1:45
Matches can be played live or quick simulated. Live matches include highlights, tactical choices, tired players, and substitutions. Quick sim instantly gives a result and updates the league table.

1:45-2:00
The goal is to manage transfers, build the best squad, make smart match decisions, and climb the Premier League table.

## NotebookLM Prompt

After uploading this guide and the screenshots, use this prompt:

Create a 1-2 minute video guide for Premier League Control Room. Explain the game as an exciting football-management experience. Cover choosing a team, using the transfer market, negotiating deals, seeing the signing animation, building the Starting XI, playing matches, quick sim, substitutions, and the 38-game league table. Use a friendly, energetic tone for a young football fan. Keep the explanation simple and visual.

## Best Video Structure

Use this order:

1. Start with the dashboard.
2. Show team selection and player cards.
3. Show transfer negotiations.
4. Show the signing animation.
5. Show the formation builder.
6. Show the Match Room.
7. End on the league table.

This gives the video a clear story: choose a club, build the squad, play matches, and chase the league title.
