# How the Game Works

The game board consists of sixteen "cards" arranged in a grid. The deck is made up of eight different pairs of cards, each with different symbols on one side. The cards are arranged randomly on the grid with the symbol face down. The gameplay rules are very simple: flip over two hidden cards at a time to locate the ones that match!

Each turn:

The player flips one card over to reveal its underlying symbol.
The player then turns over a second card, trying to find the corresponding card with the same symbol.
If the cards match, both cards stay flipped over.
If the cards do not match, both cards are flipped face down.
The game ends once all cards have been correctly matched.


# Project Specification

## Game Behavior

- The game randomly shuffles the cards. Player wins once all cards have successfully been matched.
- When a player wins the game, a modal appears for congratulations and asks for one more game. It tells the player how much time it took to win the game, and what the star rating was.
- A restart button allows the player to reset the game board at any time of the game: the timer, and the star rating.
- The game displays a star rating (from 1-3) that reflects the player's performance. At the beginning of a game, it should display 3 stars. After some number of moves, it should change to a 2 star rating. After a few more moves, it should change to a 1 star rating. The number of moves needed to change the rating is at 16 moves, at 20 moves.
- When the player starts a game, a displayed timer should also start. Once the player wins the game, the timer stops.
- Game displays the current number of moves a user has made.

## Interface Design

- Application uses CSS to style components for the game.
- All application components are usable across modern desktop, tablet, and phone browsers. It is tested and running well at the latest Chrome, Firefox and Safari browser (March 2018).

## Documentation

- A README file is included detailing the game and all dependencies.
- Comments are present and effectively explain longer code procedure when necessary.
- Code is formatted with consistent, logical, and easy-to-read formatting as described in the Udacity JavaScript Style Guide.

