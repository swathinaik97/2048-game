# 2048-game
2048 game is confined within a 4*4 matrix. This is the basic thing you need. Nested lists would
be the quick choice to implement a 4*4 matrix in python. Next up the numbers within the 4*4
matrix are even numbers starting from 2. The combination of same numbers will result in their
sum. If you succeed to make a single block of 2048 then you win. You have four valid moves
namely left, right, down and up. Every time you make a move(left, right, up, down) a new
number(2) is generated at one of the positions within the 4*4 matrix where the value is
zero(nothing). If there are three same numbers in the format as shown below(for example), and
left move is made then the number closer to the extreme positions has a higher precedence then
that present somewhere middle of the matrix.
Taking only a single row as an example
2 2 2 16
When left move is activated, the above row becomes
4 2 16 0
