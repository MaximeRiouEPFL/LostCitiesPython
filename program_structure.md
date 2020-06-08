# Program Sructure

## Data structure

### card
- color
- number of card

Question
-  Should the card know where in what pile it is located or should it be stored in a different place

=> This should be stored in a different place

### piles

There are different 4 different zones where a card can be stored
- the stock pile
- the player's hand
- the played pile
- the discard pile

#### Stock pile
- list of cards left
- number of cards left
- take the first card on top
- shuffled deck

#### player's hand
- list of 6 cards
- ability to play one card
- replace it with another

Bonus
- ability to reorder the cards to your liking

#### played pile
- color of pile
- ordered sequence of card
- ability to count the points for this pile

#### discard pile
- color of pile
- list of discarded cards
- ability to take last card from pile

## Game structure

### game
- stock pile
- list of discarded cards for each colors
- ability to start a new game
- abiltiy to stop the game when finised
- ability to show end screen

### player
- list of cards in hand
- list of played card

# other structures
- the resources will be stored in an xml file
- the images will be stored in a sprite sheet