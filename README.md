# Chroma Chess

**Chess variant where you can change square colors to affect piece movement**

Have you ever wondered what would happen if squares could change color on a chess board, and piece movement rules change accordingly? Here's my interpretation of the idea.

## Rules

Every turn, you may change the color of any one square instead of playing a normal move. 

Piece movement is now defined using square colors: 
 -  bishops may move through a path containing only same-colored squares without turning 90 degrees or more
 -  knights may move to any differently colored square exactly 2 king steps away
 -  rooks must move through alternating square colors without turning 90 degrees or more
 -  queens can move both like a rook or a bishop
 -  pawns can move forward (including diagonally) to any differently colored square and capture forward on any same-colored sqaure; they can still move two steps on their first move
 -  kings' moves are unchanged

Currently, en passant and castling are unsupported due to possible path ambiguities (different paths may lead to teh same target square). Also there are no checks - capture the king to win.

## Playing

Click to select one of your pieces. Click a target valid square (highlighted with dots) to move or capture. Right click (or use the Paint Mode button) to paint a square its opposite color. Beware - square color changes can cause large changes in the controlled area of pieces.

## Board editor

You can toggle the Edit Mode button to edit the position. When Edit Mode is active, select a piece type/color from the Edit mode piece area on the right side, and left-click on a square to add/change or remove the piece of the chosen type and color. If you don't select any piece type/color, left-clicking will remove existing pieces. Right clicking or activating Paint Mode in Edit Mode will allow you to paint any number of squares without using up a turn.

Happy painting!
