# Backdoors & Breaches for PlayingCards.io

Backdoors & Breaches is a card game created by [Black Hills Information Security](https://www.blackhillsinfosec.com) designed to help facilitate infosec tabletop exercises. This repo is an online version of the game that allows for remote play through the site [playingcards.io](https://www.playingcards.io). If you play the playingcards.io version of the game, please consider supporting the original creators by buying a deck at [backdoorsandbreaches.com](https://www.backdoorsandbreaches.com).

## How to Play

Instructions on how to play can be found [here](https://www.blackhillsinfosec.com/wp-content/uploads/2020/05/BB-Visual-Guide-PRINT.pdf).

## Starting a New Game

To start a new game you first have to create a new room:
1. Download the backdoors-and-breaches.pcio file from this repo
2. Go to playingcards.io, click "Custom Room", then on the next page click "Start Blank Room", then "Enter" when prompted
3. Now go into edit mode by clicking the briefcase-looking icon in the upper left

![edit-button](https://user-images.githubusercontent.com/5123416/109735324-3206b080-7b88-11eb-8253-a59fd5593b3a.png)

Note: on smaller screens it may be in the lower left corner.

4. A drawer should open from the bottom of the screen (click the drawer tab to open it if its closed)
5. Click "Room Options", then "IMPORT FROM FILE", and select the .pcio you downloaded.
6. Once the upload finishes the part that says "Uploaded Image ##/##" will then say "Complete!". The board should then look like this:

![upload-complete](https://user-images.githubusercontent.com/5123416/109736639-4e0b5180-7b8a-11eb-8242-0966108a429e.png)

7. Finally click the edit button again to get back into the play view. You are now ready to play!

One thing to be aware of is that the upload process sometimes hangs on the last image being uploaded for several minutes. We recommend setting up new rooms for tabletop excerises in advance to prevent this from causing delays.

## Game Controls

To start a new game, simply click the "New Game" button. To reset the room to its starting configuration click "Reset". The spinner replaces the d20 for the game, and the counters on the right are used to track the current turn and number of consecutive failed procedures.

Pressing the "New Game" button will recall all the cards to their decks and shuffle them. It will also reset the counters. It will then distribute the procedure cards out and give the Incident Master their hand.

![new-game](https://user-images.githubusercontent.com/5123416/109738339-439e8700-7b8d-11eb-8969-a0596e86c019.gif)

## PlayingCards.io Mechanics

### Adding players to the game

To invite players to your room simply share the URL. Each player has their own view of the table. You can see other player's cursors as colored circles moving around the screen.

Be warned, anyone with the URL for your room can join, there's no limit to the number of players that can be in a room, and there's no way to kick someone out of your room. We recommend creating a new room for each play session to avoid issues with lingering players and leaked links.

### Moving cards

Cards are moved by clicking and dragging. To move an entire stack of cards, click and drag on the number in the upper left of the stack.

### Player's hands

Each player has a section on the bottom of the screen that is their "hand". Cards that a player drags there disappear from the table and are only visiable to them. The only player that needs to use their hand is the Incident Master who uses it to hold their attack cards.

### Flipping cards

Click cards to flip them over.

### Rotating cards

To rotate a card, hold right-click and hold on a card, then drag it in a direction to change its orientation. For this board only procedure cards can be rotated.

### Card zoom

If a player hovers their mouse over a card, an enlarged version of that card will be shown to them. Enlarged cards are only shown to the user hovering, not to other players. Note that this functionality doesn't seem to work well on touch screens.

## Room Lifetime

Rooms are automatically removed after 15 days of inactivity. If you would like to remove a room you've created sooner go into the edit view > Room Options > click the "DELETE" button.

