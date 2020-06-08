# LostCitiesPython
Recreate the board game lost cities using python and tkinter as basic GUI

## Game Rules
The game is a 1v1 game. The goal of the game is to have more points than your opponent.
You gain points by completing explorations. 
There are five explorations that you can do, represented by a family of cards. In each family there are 3 investment cards that serve as score multiplier and cards from 2 to 10 that correspond to score.

The player each start with 8 cards in their hand
Each turn a player places card and picks a card up.
The player can start an exploration by placing a card from a family not already started.
The player can continue an exploration by placing a card of higher value on a card of the same family. Investment cards can only be placed before any number are placed.
Player can discard a card on the discard pile of the family. The discard pile is common for both players

The player can then take a card from the pile or the top of one of the discard piles. The player cannot take a card that he just discarded.

The game ends when there are no more cards in the pile.
Each started expedition start with a negative point of -20.
The points on the cards are summed.
Depending on the number of investement card the score for the exploration is either double, tripled, or quadrupled

## Goals
### Displayed information
- First goal is to have a graphical interface to be able to see the game
  - 2D top down interface
  - See your card
  - See the number of card remaining in the deck
  - See the number of opponents card
  - See the cards put by you
  - See the card put by the opponent
  - See the discarded cards
  - See the cards move between the different piles

- Starting screen
  - screen containing the image of the game
  - start game button
  - option to select between on the network game or not later
### interactions
- Actions during your turn
  - select the card you want to place
  - select if you want to discard it or place it
  - select the card you want to pick, either from the stack or from a discard pile
  
- Game modes
  - 1v1 turn based on the same computer
  - 1v1 on the network
  - 1vcomputer - this requires to build an A.I. which is a whole other project

### Business logic - unit tested
- Shuffled deck
- Automatic ending of the game
- Automatic calculations of scores
- Move a card from the stack, to your hand, to a pile or the discard pile
- illegal moves should not be possible

# Good practice goals
- unit tests
- documentation
- use github to track progress
- all text is stored in resource

## Plan
1. think about basic structure
2. design gui to know what is the business logic to implement
3. create unit tests for business logic
4. implement business logic
5. implement graphical interface

# Convention
- no camel case
- classes start with an upper case
- constants are written in full upper cases
