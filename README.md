# AlgorithmsAndDataStructures

## Sliding Window

When to use:
* If we need result over a sequence of data( subarray, substring)
* When we need to stop when a condition is met ( sum is K, or K distict character)

Sample Problems:
* Longest substring containing k disticnt character
* Longest subarray with sum K 


## Graph Traversal Algorithms

* DFS - Recursive(Using Stack). As u visit push to stack. Pop and see if all adjacent nodes are visited.
* BFS - Using Queue. Push all adjacent nodes.


Knights Tour

* Minimum steps to reach target by a Knight: Using BFS. The first hit that matches the target will be the minimum distance.Because in BFS we try all position of same distance always.

* Must visit all cells : Back Tracking. Backtracking is an algorithmic paradigm that tries different solutions until finds a solution that “works”. Recursively try to solve. If cannot solved, then backtrack and try other possibilities.
