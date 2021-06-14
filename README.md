# MancalaGame
Mancala Game is a two-player  game, each one has 6 pockets in front of him and his mancala,  each pocket has 4 stones in it, and he is allowed to choose any  pocket of the 6 to make his move (as long as this pocket is not  empty), The goal is to collect the biggest number of stones in your  own mancala. The game has 2 modes, with stealing and without stealing,  without stealing means that the player cannot steal stones from  his opponent pockets no matter what the situation, with stealing  means that the player can steal from his opponent pockets ONLY  IF he placed his last stone in an empty pocket (of his own pockets)  and the opposite opponent pocket’s has stones in it, so the player will take the stone he put in the empty place and the stones in the  opposite opponent’s pocket and put them in his mancala
# Implementation
we first build a human 
vs human version to make sure that we understand the game 
rules right, then we moved to the minimax with alpha-beta 
pruning to make the AI chooses the best available move in a given 
depth, then we update the board based on the game rules and 
the mode of the game
