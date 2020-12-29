#Blokusgame

Team members: Arshia Giri, Nasredene Elyamani , Mohamed Abdalla, Justin Hsu

Key Idea: To implement an interactive 4 player, board game, Blokus.

Key features:
- 21 unique pieces per player (1 monomino, 1 dominos, 2 trominos, 5 tetrominoes, 12 pentominoes)
- 20 x 20 board
- The first piece played by each player must touch a corner of the board.
- A valid move requires that a piece touch exactly one corner of a piece of the same color.
- A player is eliminated when they have no more valid moves. The game ends when all players have been eliminated.

Narrative description:

We recreated a text-based terminal game of the board game known as Blokus. This is a 20 by 20 square board game with essentially 21 pieces per player for 4 players. Of those 21 unique pieces, there is 1 piece of only one square, 1 piece of two squares, 2 pieces of three squares, 5 pieces of four squares, and 12 pieces of five squares. The first piece that is played by each player must cover a corner space on the board. After that a player is allowed to place a piece wherever as long as it touches the corner of their piece. During each player’s turn, we would show them the available pieces and then they can choose the piece, the orientation and coordinate they want to place. If it is valid, we allow that. If not, their turn is skipped. If a player thinks they have no more valid moves remaining with the calculated based upon the number of pieces that each blocks has on the board.
