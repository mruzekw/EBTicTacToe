_ _ _
_ _ _
_ _ _

x x o
o x _
_ x o

x _ _
o x _
o _ x

[
[null, null, null]
[null, null, null]
[null, null, null]
]

Spaces
(0, 0) (0, 1) (0, 2)
(0, 1) (1, 1) (1, 2)
(0, 2) (0, 1) (0, 2)

(null, 0, 1) => (blank, x, o)

Who won?
* Tally Xs and Os and compare to possible winning outcomes
* Traverse whole board for all outcomes (horizontal, vertical, diagonal)
* Did the player win from /that move/? => Traverse board for possible wins based on most recent move

For 3x3 board, Possible win after 5th, usually after the 7th turn
For NxN board, ...

Possible Winning Outcomes

Vertical

(0, 0)
(0, 1)
(0, 2)

(1, 0)
(1, 1)
(1, 2)

(2, 0)
(2, 1)
(2, 2)

Horizontal

(0, 0)
(1, 0)
(2, 0)

(0, 1)
(1, 1)
(2, 1)

(0, 2)
(1, 2)
(2, 2)

Diagonal

(0, 0) Corner
(1, 1) Center of Matix
(2, 2) Corner

(2, 0) Corner
(1, 1) Center of matrix
(0, 2) Corner