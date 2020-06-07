# LostCitiesPython
Recreate the board game lost cities using python and tkinter as basic GUI

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
