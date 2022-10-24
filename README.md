# N-Tris
A spin-off of the classic game of Tetris!

Tetris relies on "Tetronimos", which are all the contiguous permutations of four unit squares, where each of the 7 such permutations are translated and rotated by the user to tesselate with the rest of the board. Once a row is filled, points are awarded according to the number of rows simultaneously completed and those rows are cleared. 

N-TRIS is the same concept, but for all the unique permutations of n unit squares (there can be a lot!). At the start of the game, press any number on the keyboard to change n to that number, and press space to play just like Tetris! There are a couple cool things about this game. The number of these unique shapes forms a pretty interesting pattern: 1, 1, 2, 7, 18, 60, 196, 704, 2500, 9189, ...  Playing with high numbers "n" becomes very difficult -- hence the higher points awarded for each row completion! For instance, for n > 7, holes can emerge inside of the shapes themselves so it is impossible for them to perfectly tesselate inherently. For n < 4, the game is extremely simple, almost boring. The shapes can get pretty funky, too. Hope you enjoy playing!

Utilizes the Pyret library (https://code.pyret.org/editor)

Worked on this project together with Woody Hulse
