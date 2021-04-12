# Chess_Game_Using_Min_Max_Algo

The Chess game is developed by using Min max Algorithm and Alpha-beta pruning . 
The approach is more efficient as compared to brute force method of building the chess 
game . This game is executed on a web brower (https://jsfiddle.net/q76uzxwe/1/) using JavaScript programming 
language and JSON .

**➔ Alpha–beta pruning** is a search algorithm that seeks to decrease the number of nodes that are 
evaluated by the minimax algorithm in its search tree. It is an adversarial search algorithm used 
commonly for machine playing of two-player games (Tic-tac-toe, Chess, Go, etc.). It stops 
evaluating a move when at least one possibility has been found that proves the move to be worse 
than a previously examined move. Such moves need not be evaluated further. When applied to a 
standard minimax tree, it returns the same move as minimax would, but prunes away branches
that cannot possibly influence the final decision.

**➔ Minimax** is a recursive algorithm which is used to choose an optimal move for a player assuming that the other player is also playing optimally. It is used in games such as tic-tactoe, go, chess , checkers, and many other two-player games. Such games are called games of perfect information because it is possible to see all the possible moves of a particular game.

**Minimax** is a kind of backtracking algorithm that is used in decision making and game theory to 
find the optimal move for a player, assuming that your opponent also plays optimally. It is 
widely used in two player turn based games such as Tic-Tac-Toe, Backgamon, Mancala, Chess, 
etc.

In Minimax the two players are called maximizer and minimizer. The maximizer tries to get the 
highest score possible while the minimizer tries to get the lowest score possible while minimizer 
tries to do opposite.

Every board state has a value associated with it. In a given state if the maximizer has upper hand 
then, the score of the board will tend to be some positive value. If the minimizer has the upper 
hand in that board state then it will tend to be some negative value. The values of the board are 
calculated by some heuristics which are unique for every type of game.

[]!(https://github.com/kushalshrini/Chess_Game_Using_Min_Max_Algo/blob/master/Result.gif)

There are 5 modules in our program, They are:
      
      1. Move generation and Board visualization.
      2. Position evaluation
      3. Search Tree using Minimax
      4. Alpha-Beta pruning
      5. Improved evaluation function
  




  
      


