## Overview

This is basically League of Legends the board game. It's a team based game where each player controls one hero, and all the heros are very different.

### The Map

The map is divided into different zones. There are the throne zones owned by each team where their heros will spawn. In between those are 3 zones that the minions can occupy where the majority of the fighting will occur. The zone that currently has minions is called the battle zone, and this center zone is the first battle zone of the game. There are also 2 zones that run along the map that heroes can move through

## Gameplay flow

The game is played in rounds, with each round consiting of 4 turns. Each turn, everyone will simultaneously choose a card from their hand and play it face down. Then, every one will flip their card at the same time. We will then resolve each card, with that player taking their turn, and this is determined by initiative order. After 4 turns, the round ends, players take cards back into their hand, and a new round begins.

### Turn Structure

#### Play a card

- Everyone selects a card from their hand and places it facedown
- You must play a card if able, even if your hero is not on the board
- If you have no cards left, you must announce that you are passing
- Once everyone has a card facedown or has announced that they're passing, flip cards face up

##### Initiative

- The number in the top left of a card is the initiative
- Turns are resolved by highest to lowest initiative
- In the event of a tie on oppostite teams, there is a token in the corner of the board that shows what team wins the tie. When a tie is won like this, flip the token over (so the other team will win the next tie)
- Players on the same team who tie must agree on who goes first without discussing it (more on that in a moment)

##### Table Talk

- Between turns, you are allowed to discuss strategy freely with your team, but it must be done out loud so the other team can hear you
- You are not allowed to show each other cards, but can read those cards out loud
- Use your best judgement when to discuss strategy publicly, and when to trust your teammates to do their thing
- Once action cards are revealed at the start of the turn, STRATEGY DISCUSSIONS MUST STOP
- Players can (and should) read the cards played by others to gauge their oponents and teammates intentions, but each player must make decisions on their own
- If teammates need to make a coordinated decision after action cards have been revealed, it must be done without discussing strategy, they may only stat their preference.
    - Example: If two teammates were tied in initiative you could only say "I would like to go first". You couldn't say "I need to go first to be next to that person to set you up for your turn"
- The rules around discussion may sound weird, but it is supposed to simulate the real time nature of the fight, and characters and cards are balanced around this

##### Perform One Action

Whenever you play a card, you will either resolve the primary action on the bottom of the card, or one of the secondary actions on the side of the card. The text on the card is only applied whenever you play the primary action at the bottom.

Primary actions always match the color of the card

![icons](images/guards_of_atlantis_2/action_icons.png)

##### Movement

- When you play a card for movement, you move your hero up to the number of spaces on the boot icon. You can't move through obstacles (heroes, minions, terrain, and tokens)
- Alternatively, you can use a movement action to fast travel. When fast traveling, you may move to any space in the same zone or an adjacent zone, as long as all of the following are true:
    - The destination space is either in the same zone or an adjacent zone
    - There are no enemy heroes or minions in the zone you are fast traveling from
    - There are no enemy heroes or minions in the zone you are fast traveling to
    - The movement value is ignored when you fast travel, and you only fast travel once.
- If the boot icon is the primary action of the card you use to move, you can move your hero and perform the text.
- If you use the movement icon to fast travel, do not apply the card text

##### Skill Action

When you perform a skill action, simply apply the card text. A skill action is always a primary action.

##### Hold Action

This action is not represented by a symbol.

- You can always choose to use a hold action
- When you perform a hold action, you do nothing
- Use case may be when the card you played has no legal move when it gets to your turn, or the situation has changed so much in the turn before you play that doing anything on your card would be disadvantageous.

##### Attack Action

You can use an attack action to attack enemy heroes or minions

- You can never attack friendly units
- Non ranged attacks can only target units adjacent to you
- Ranged attacks can target units based on the range value on the card (the arrow and bullseye)

Attacking a minion

- Minions cannot defend
- When an enemy is targeted with an attack, they are defeated
- Defeating minions earns you coins
    - Ranged and melee minions are worth 2 coins each
    - Heavy minions are worth 4
    - Heavy minions are immune and can't be targeted as long as there are still minions of that team's in the battle zone

Attacking a hero

- Heroes get the opportunity to defend by discarding a card and using the defense action of that card. The higher the attack value, the harder to defend against it
- Calculate attack total:
    - Attack value on card
    - +1 for every attack item you have (more on that later)
    - +/- from attack text (if any)

