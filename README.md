# Description
Python implementation of automatic Tic Tac Toe game using random number. numpy and random Python libraries are used to build ,this game.play_game() is

The main function, which performs following tasks :

1.Calls create_board() to create a 9×9 board and initializes with 0.

2.For each player (1 or 2), calls the random_place() function to randomly choose a location on board and mark that location with the player number, alternatively.

3.Print the board after each move.

4.Evaluate the board after each move to check whether a row or column or a diagonal has the same player number. If so, displays the winner name. If after 9 moves, there are no winner then displays -1.


# Output

[[0 0 0]
 [0 0 0]
 [0 0 0]]
 
Board after 1 move

[[0 0 0]
 [0 0 0]
 [1 0 0]]
 
Board after 2 move

[[0 0 0]
 [0 2 0]
 [1 0 0]]
 
Board after 3 move

[[0 1 0]
 [0 2 0]
 [1 0 0]]
 
Board after 4 move

[[0 1 0]
 [2 2 0]
 [1 0 0]]
 
Board after 5 move

[[1 1 0]
 [2 2 0]
 [1 0 0]]
 
Board after 6 move

[[1 1 0]
 [2 2 0]
 [1 2 0]]
 
Board after 7 move

[[1 1 0]
 [2 2 0]
 [1 2 1]]
 
Board after 8 move

[[1 1 0]
 [2 2 2]
 [1 2 1]]
 
Winner is: 2

