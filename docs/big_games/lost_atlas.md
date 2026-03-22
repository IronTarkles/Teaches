## Overview

A sort of intro 18XX game. We're investors that are buying stocks in companies and whoever has the majority share gets to build tracks and run trains for those companies. Companies can pay out dividends to investors to raise their stock price, or withhold earnings to improve their infrastructure. The game is played over a number of cycles made up of rounds. Stock rounds where players will invest, and operating rounds where companies will do train stuff. At the end of a set number of cycles, whoever has the most money will win.

## Important Concepts

Acting as a player vs acting as a president

- There are separate money pools for each player and each launched company
- In stock rounds, players use their personal money to build their portfolio
- In operating rounds, companies use money from their treasuries under the direction of their president

Change of ownership

- You do not explicitly own any company, the person with the majority shares of a company is the one that runs it... for now
- Majority can change over the course of the game, so companies can change hands
- This means you can manipulate stocks to take a company from someone, or have a company taken out from under you
- Owning two shares of a company means you're at risk of becoming the president, so be careful you don't get a poor company dropped in your lap

Stock Track

- This shows how valuable a share of a given company is
- Share price also dictatces turn order in the operating round
- Actions we take can cause stock price to go up or down, detailed on the bottom of the stock track. We'll talk about those as they come up
- The maximum value is set by the color on the track
- Yellow is the first phase of the game, so in the first phase, stock price can never go above 904

Earnings board

- Everyone hates math, this board makes it easy

Map building

- We'll build the map for the game together, but we'll go over rules before we do that lets go over how the game works

## Stock Round

This is where players take turns using personal capital to grow their net worth. On a stock round turn, you have 3 options

1. Initiate a minor company auction
2. Sell shares and/or purchase a single share
3. Pass

The current priority player will pick an action to take, and then we'll keep going clockwise

### Initate a minor company auction

There are stacks of minor companies that we can bid on. Each minor company has a special ability for how it plays. Later in the game, we can merge minor companies together, and the created major company will retain the special powers of the minor companies used to make it. Minor companies are on the board in stacks, only the topmost company in a stack is available. We're not bidding for a specific company, whoever wins the bid will select one of the available minor companies to launch.

- Bids are a minimum of 120
- Minimum bid increment is 5
- The final bid sets the initial stock price of the launched company (half of the bid, rounded down)
- The auction is a hard pass
- Once everyone but one player has passed, that player chooses an available company to launch
- This ends the auction, and the next player clockwise from who initiated the auction (not who won it) takes the next stock round turn

#### Launching a company

These are the steps to launch a company:

1. Collect all of the shares, tokens, and any additional components associated with that company.
2. Take the presidents certificate (worth 2 stock shares) and put it in front of them.
3. Place their winning bid into that companies treasury, this is now the company's money
4. The rest of the stock shares are placed into the company's treasury.
5. Place a token on the stock track indicating the initial stock value for that company (half the winning bid, rounded down)
6. The phase of the game dictates the maximum stock price. In the yellow phase of the game, the max stock price would be 90.Even if you won the bid with 200 in this phase of the game, the stock price would be capped at 90 per share (even though the full 200 would end up in the company's treasury)
7. Place one company token on the earnings board.
8. Place one company token as a hub onto the company's starting space on the map

### Sell and/or buy shares

Starting an auction for a company was the first action you can take in the stock round. Sellings shares, and/or purchasing a share are another action you can take

#### Selling shares

A player may sell any number of shares at current stock value and collect that money from the bank with the following restrictions:

- You may not sell a share that would leave a company without a president
- You may not sell a share of a minor company that has not performed an operating round yet (so in the first stock round of the game there are no shares that can be sold)
- No more than 50% of a company's shares may be in the bank pool at any time
- When stocks are sold, the price of that company's stock drops by 1 level, regardless of how many shares are sold.
- All shares a player wishes to sell on their turn must be done at the same time, and sales can only happen once per stock round. So you can't space things out to keep dropping a stock price

#### Buying a share

and/or after choosing wheter or not to sell shares a player may purchase one share at a company's current stock price

- Shares may be purchased directly from the treasury of a company. The stock value is paid directly into that company's treasury
- Shares may be purchases from the bank pool if there are any. The current stock value is then paid into the bank.
- No player may own more than 60% of a single company at any time
    - for minor companies this means the president share plus another single share
    - for major corporations this means the president share plus 4 other shares
- A player may not purchase a share of a company that they sold shares of this stock round

If at any time due to sales or purchases of stock a player other than the president of a company now owns more shares than the president, the presidency changes hands. This means that control of that company and its assests is now dictated by a new person. To indicate this, exchange the presidents certificate and two single shares between the players that the presidency is trading hands between. Move all of the company stuff in front of the new president.

#### Passing

Instead of choosing to start an auction or buy/sell, you can also choose to pass your turn in a stock round. This does not necisarily remove a player from the stock round. When play returns to that player they can again choose from stock round actions. If all players pass consecutively, the stock round ends.

If no minor companies were launched in the initial stock round, we would shuffle and redeal them. This is only for the first stock round of the game.

### End of the stock round

The player clockwise from the player who took the last non pass action takes the priority player marker (so they will act first in the next stock round)

## Operating round

This is when companies make changes to the map, run routes to generate revenue, and buy trains. All decisions in this phase are made by the presidents of companies, and all costs are spent from those companies treasuries.

Turn order for the operating round operate in descending stock price order. The following actions must be taken in order:

- Optionally purchase a leadoff train
    - The first operating round a minor company has in the game (meaning it was just launched in the previous stock round), there is an opportunity to buy a train from the bank pool at face value.
    - The full price must be paid from the company treasury
    - Trains purchases in this step will be able to run their route and generate revenue this turn
- Optionally, issue or redeem one share
    - A company may issue a share from its treasury to the bank.
    - The company then receives its current share value from the bank, and the share value drops one spot on the stock track
    - OR, a cpmany may redeem a share from the bank. The company pays its stock price and takes one of its shares from the bank to return to its treasury. This does not change stock price
- Optionally, lay track tiles
    - A company can place up to two yellow tiles, or upgrade one tile based on the game round. In the yellow phase of the game, only yellow tiles are available
    - Yellow and non city upgrade tiles must be placed in a way that the copmany can trace a route through at least some of the new track
    - City tiles must be placed so that a company can trace a route into that tile
    - Track can't run into the edge of a water hex, blank edge of a distant destination hex (red tiles),  the edge of a black border hex, or the edge of the map.
    - Yellow tiles can't be placed on water, distant destinations, black border hexes, or any hex that already contains track
    - Cities can't be created or removed while placing a tile
    - Upgrade tiles can only replace a tile from the previous phase (yellow replaces green, purple replaces green). Replaced tiles are again able to be used later
    - Upgrades must maintain the tracks that already exist exactly
    - All printed costs must be paid from the company when placing track (to place mountain space tracks its more expensive, normally no cost)
    - Tiles are finite, so all optiosn may not always be available.
    - Hub tokens are maintained as city tiles are upgraded
    - Printed hubs for unlaunched minor companies are reserved until that company launches. A tile can be placed on a spot with a minor company reservation on it, but use a token from that unlaunched company to place on top of it ( so it must be a city). That spot must remain unclaimed until that company enters the game. While in this state it is not considered to be blocked.
- Optionally, place a hub token
    - A company may place a toekn by paying its printed cost
    - The token can then be placed in a city that the company can trace a route to
    - A company can only have one hub token on a tile
- Run trains if able (more in a sec)
- Distribute earnings (more in a sec)
- Buy trains (more in a sec)
- Pass the turn and continue with the next company. If all companies have gone, the round tracker advances, and play continues in the new round.

### Train routes

- A route is a continuous traceable line of track that includes at leaste one city with the company's hub token and does not require any piece of track be touched more than once.
- Companies run routes equal to the number of trains that they own. Each train runs a separate route, and can never use the same section of track as any other train run by that same company. Route may cross each other at cities and some green and purple track tiles.
- A route may not pass through a city that is full of hub tokens unless a token of the operating company is present.
    - This means a route can be blocked by a city full of hub tokens
    - A "blocked" city can be the starting or stopping point of a route, you just can't pass through it on a route
- A single train may not include the same city or distant destination more than once in its route, although multiple trains may be able to count the same city if they use different track to get there
- Some tracks with forks have a directionality to those turns. A route can't use the sharp turns on these tiles. Cities operate as junctions, so any turn that doesn't run on track that has already been run by a train is allowed
- The value of a route is equal to the total value of stops touched by the train up to its number. So a three train could make up to 3 stops. 
- You can't skip over a city to extend a route.
- You're never prevented from running a train due to local routes
    - If you're in a situation where you have no other unique track out of a city you can just use a train to run a "local" route and deliver to the city your hub token is in
    - This only gives you the value of the city where the hub token is
    - Since no track is used, multiple local routes may be run
    - Worst possible option, but better than making no money at all
- The total value of routes dtermines a company's earnings
- If a company has no trains during this action, its revenue is considered to be 0 and its share price decreases by one increment when earnings would be distributed
- We'll use the earnings board to mark settled routes

### Distributing earnings

Once all routes are ran, the president decides how to distribute the earnings each operating round. The options are to pay out to the shareholders or withold the total amount.

- To pay out earnings
    - Each minor company share is 20% of the total payout
    - Each major corporation share is worth 10%
    - Money is taken from the bank and given to each shareholder, including the company itself if it still holds its own shares in its inventory
    - This number should be marked on the earnings track
    - If the total payout is greater than 0 but less than the current share price, no adjustment is made to the share price. The share token is then moved below any other tokens in the current share price column
    - If the total payout is equal to or greater than the current share price (but less than double), the share price increases by 1 increment
    - If the total payout is equal to or greater than double the current share price, increase the share price by 2 incrememnts
    - There are reminders for these on the stock tracker board
- To withold earnings
    - The company takes from the bank the total earnings and puts it in its treasure
    - The share price then drops by one incrememnt

### Train purchasing

- If the company has fewer trains than the current phase limit, it may purchase the top train of the available trains stack, a train from another company, or a train from the bank pool
- If the company does not own a train, it must purchase one before ending its operating round actions
- Companies may buy as many trains as they have space for in this part of the round
- Players may not contribute personal cash towards a train purchase unless during a forced train purchase
- Trains on the train stack and in the bank pool are available for face value
- A train may be purchases from another company for at least $1 as long as both presidents consent to the sale. Purchasing company pays price directly to selling company's treasury
- If you are the president of both companies, sell it for as cheap as you want!
- If a company does not have enough money in its treasury to buy a train, a forced train purchase is initiated
    - A company MUST have a train before ending its operating round actions
    - If a company can't pay, the president has to step in
    - Company money is contributed first, then money from the president
    - If that still isn't enough, the president must begin selling shares to cover the difference
    - Shares are sold one at a time until they can cover for the cheapest train or go bankrupt
    - Shares sold this way aren't moved during the one by one selling, but each company whose shares were sold during this process will go down one on the stock track (like during the stock round)
    - During this process the president can't sell shares of the struggling company that would force a new presidency, or would result in the bank owning more than 50% of that company

### Rust events

- Rust events happen wehen a new train is purchases or exported that eliminates an older type of train.
    - The first 4 train purchased rusts 2 trains
    - The first 6 train purchases rusts all 3 trains
    - The first 7 or infinite train purchased ruts all 4 trains
- If a train purchased from the train stack is the first of a type that triggers a rust event, it is resolved immediately
- Rusted trains are removed from the game

### Phase changes

- If a train purchased from the stack is the first train of its color the game advances to that phase immediately
- New train limits are imposed such that companies now over the train limiit must place a train of their chosice from their holdings into the bank pool
- New tiles are now available for use
- Range of initial stock prices expands when the green and purple phase are entered

## Merger round

After both operating rounds, there is a merger round. This round only happens if the first green train has been purchased.

In descending stock price order, each minor company may propose a merger with another minor company with at least one hub token they can trace a route to.

If one of the presidents declines the merger, that same merger may not be proposed again this round

- When both presidents agree to the merger
    - The president of the new corporation will be the player who owns the most shares of merging companies
    - If players are tied for the most shares, the presidency goes to whoever acted earlier in turn order
    - The president takes a corporation card, all matching tokens and stock certificates that go with it
    - Replace each merged company certificate with a corporation certificate
    - Give the newly created corporations president certificate to the new president
    - Turn the other company's president certificate into two single corporation certificates
    - Place the minor company charters side by side and place the corporation charter over top
    - A major corporation retains the abilities of both minor companies
    - One token is placed on to the earnings board
    - One token is placed onto the stock track at the average price of the two merged companies rounded down.
    - Remove the old comapnies tokens from the stock track and earnings board
    - For each hub token belonging to either merged company, replace it with the new corporations hub tokens
    - If this would result in two of that corporations hub tokens on the same tile, only one corp token goes on the tile, with the other going onto that corporations charter FREE spot
    - Two of the extra hub tokens are placed onto the charter in the rightmost spaces. Any leftover tokens go back in the box
    - Treasuries of the merged companies are combined for the new corporation
    - Trains of the merged companies are combined for the new corporation
    - Any trains over the limit go to the bank pool

## End of the phase

Each cycle of rounds, before going to the new stock round we will export a train

The top train of the trains stack is exported, which just means removed from the game

If a 2 train is exported, all remaining 2 trains in the train stack are removed with it, leaving the first train available for purchase in the new round as a 3 train

If exporting a train results in the first 4, 6, or 7 train going away, treat it as though the train were purchased. This means a rust event can be triggered, or a game phase advance

## End of the game

Game ends after 4 cycles for a short game, or 6 cycles for a long game.

Players will add their personal cash and the value of all shares they own to get their final score

Company treasuries are not considered during this count, only player treasuries.

