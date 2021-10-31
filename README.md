# Chess Game
This code implements, or tries to..., a chess game (https://en.wikipedia.org/wiki/Chess).

Your mission is to review this code and identify what kind of things are missing and/or you would do differently and why.

Some tips or points to consider:

- Think in the SOLID principles
- Think in the functionalities that a chess game should have




- All the information is mixed in the domain objects
- Domain objects should have the data relative of them 
- Pieces should have only information how to move them
- Player details only the colos
- Board has the pieces status and turn
- Create a new domain Rule where we can define all the rules 
- RuleEvaluator(new*) validates the movements and if the game is over against the rules
- Missing rules:
  - Alert check!
  - Player must clear the check, if not he loses
  - Player cannot kill his pieces
  - Pieces cannot go through other pieces(unless the knight)
  - Players can only move one piece per turn
  - White starts 
  - En passant capture (Captura al paso)
  - Castling (enroque)
  - If a pawn get the order side the player can change it by other piece
  - If a player has no movement without