=> Minimax computes the minimax decision from the current state.
=> Uses a simple recursive computation of the minimax values of each successor state, directly implementing the defining equations.
=> The recursion proceeds all the way down to the leaves of the tree.
=> After reaching the node the minimax values are backed up through the tree as the recursion unwinds.
=> Performs a complete depth-first exploration of the game tree.
=> Not a practical solution for real world of games.
=> Forms basis for the mathematical analysis of games.

### Time-Space Complexity
- $m$ - maximum depth of the tree
- $b$ - legal moves at each point
- Time Complexity - $\mathbb{O}(b^m)$
- Space Complexity
	- $\mathbb{O}(bm)$ - Algorithm generating all actions at once
	- $\mathbb{O}(m)$ - Algorithm generating actions one at a time

