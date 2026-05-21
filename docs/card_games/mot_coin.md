## Overview

A game about virtual currency! We're buying virtual currency and trying to make sure we don't get burned by it later on

This is a bidding game where we use dice to bid and track how much currency is worth (in a weird way). We'll never be rolling the dice

## Setup

- 20 coin cards and the hard fork cards (the x2 cards) will all be shuffled together to form the bid deck
- Players receive dice
    - 3 players = 9 dice each
    - 4 players = 8 dice each
    - 5 players = 7 dice each
- Players each receive a stable coin
    - This is the min x1 card (7 in box)
    - Each player places 3 of their available dice on their stable coin set to values 4, 3, and 2
    - These are called price fluctuation dice
    - Set remaining stable coins aside, they will be used

## Round overview

The game is played over two rounds

- In the first round, we'll be flipping two cards from the bid deck
    - We'll discard the higher value card
    - We'll auction off the lower value card
- Once the deck runs out, we'll shuffle up the discard and start the second round
    - In the second round we'll just reveal a single card to auction off
    - Once the 4th hard fork card (2x min card) is revealed, the game will end

### Auctions

Cards have a point value on the center of them, a price fluctuation in the bottom left, and a price crash value in the bottom right

- Beginning with start player and going clockwise, players can bid or pass on the auctioned card
- You can only bid with available dice, you can never use price fluctuation dice (the ones that are on cards)
- Whenever you bid, you set the dice to whatever value you want. You can bid as many die as you want
- A new bid must beat a previous bid
- A bid is considered stronger if it has a higher value die than the previous bid
- If bids are equal, compare the next highest number, and so on
- Bidding examples:
    - A bid of four 5's would be beat by a single 6
    - That single 6 could then be beat by a single 6 with three 1's
    - That bid could then be beat by a single 6 and a single 5
- If the bid comes back around to someone who had their previous bid beaten, they take all their dice they bid back before making a new bid or passing
- Instead of bidding, you can pass. Passes are a hard pass, you can't get back in that auction
- When all but one player passes, the player wins the auctioned card.
    - All dice they bet now move onto the card as price fluctuation dice, retaining their values.
    - These dice are now locked on the card and can't be used to bid until they are freed up.
- If no one bids and everyone passes, the card is removed from the game, and the starting player remains the same
- Keep your acquired cards separate in front of you so you don't mix up the dice on them

### Special auctions

For cards with the value 13 (also shows text in the bottom left instead of a value), the auction works a little different

- Winner receives the coin as usual
- Last player to pass (2nd highest bid) gets one of the stable coins set aside in set up
- That player places the die from their bid on the stable coin card
- The stable coin is only awarded if there is a 2nd highest bid. If ther is only a single winning bid, it just doesn't get awarded
- Both the player that won the auction and the 2nd highest bidder who got the stable coin will not benefit from the price fluctuation bonus
- The price fluctuation bonus is to remove the lowest value die (from a single card or all cards?, need to check translation)

### Price fluctuation

- The player that acquired the card informs the table of the price fluction value on the bottom left of the card
- This is either a negative or positive value
- All other players (expect the person who won the card) will increase or decrease the value of all of their price fluctuation dice on all of their acquired cards by this value
- If no one bids on an auction card and it is discarded, all playhers reduce their price fluctuation dice by 1
- Dice can never go above 6
- If dice at value one are reduced, they are removed from the card and are now available to bid with again

## End of round

- We'll keep running auctions like this until we go through the deck
- We'll start the second round, but now we'll just auction off the top card of the deck
- When the fourth hard fork card (2x min card) is revealed, there will be no auction, and the game will end immediately

## Scoring

There's a few steps to scoring

### Price increase

- Each player performs the following actions on all coins they own, starting with the lowest
- If the difference in price between that coin and the next highest is:
    - within 3 @ 3 players
    - within 4 @ 4 or 5 players
    - the coin is stacked under the next highest priced coin (this is a good thing)
    - if a number of coins are already stacked, tehy are also grouped together and stacked under the next
    - Move all price fluctuation dice to the top card
- Examples:
    - If someone had coins worth 15, 17, and 20, all the card would stack under the 20, and all the dice will go on top of the 20
- All stacked cards are worth the top value

### Hard fork cards

The minimum x# cards will be worth either 1x or 2x the lowest value card that you have

Price fluctuation dice on these cards will never move to other cards

You must have a coin card worth a number value for these to be worth anything

### The big plunge

- Calculate your losses on cards
- Each price fluctuation die will be worth negative points based on the bottom right crash value on a card
- Negative poitns equal to die value times the crash value
- So a die with a value of 5 left on a card with a price crash value of 7 is worth -35 poitns

