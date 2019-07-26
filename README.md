# medieval_chess
Chess engine that allows to play multiplayer chess using medieval rules
Based on XIV and first half of XV century rules.

1.1 Chess board
* h1 rule doesnt apply to white pieces, bottom right square has to be black for white pieces
* pieces are not mirrored, queen is always on the left side of the king

1.2 Pieces
1.2.1 King
* in the first move:
  * can move up to 2 square in any direction
  * can move as the knight or the bishop
  * can jump over other pieces
  * does not check other king
  * cannot perform castling
* following moves:
  * 1 square in any direction
* between kings there have to be at least one square of a distance

1.2.2 Queen
* cannot move if king have not been moved yet
* in the first move:
  * can move up to 2 square diagonally, vertically or horizontally
  * can jump over other pieces
  * does check the king
* following moves:
  * 1 square diagonnaly

1.2.3 Bishop
* moves by exactly 2 squares diagonnaly
* jumps over other pieces

1.2.4 Knight
* moves as L, two horizontally/vertically and one on the side
* jumps over other pieces

1.2.5 Rook
* moves any number of squares horizontally or vertically
* does not jump over other pieces

1.2.6 Pawn
* in the first move:
  * can move by 1 or 2 squares vertically
* following moves:
  * 1 square vertically
  * attacks 1 square diagonnaly
  * there is no 'en passant'
* promotes always to a queen (which first move will appy)
