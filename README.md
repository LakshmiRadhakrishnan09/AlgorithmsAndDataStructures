# AlgorithmsAndDataStructures

## Sliding Window

When to use:
* If we need result over a sequence of data( subarray, substring)
* When we need to stop when a condition is met ( sum is K, or K distict character)
* It’s used on arrays, lists or strings to find subarrays or substrings that meet conditions like maximum sum or target values.
* 2 nested for loops to single loop. O(n ^2) to O(n).

Sample Problems:
* Largest sum of 5 consecutive items in an array(Maximum Sum Subarray of Size K)
* Longest substring containing k distint character
    * Use sliding window + a Map to store character frequencies in the current window
* Longest subarray with sum K ( only non negative numbers)
    * if array contains negative numbers , we cannot use sliding window. In this case use prefix sum + hash map. O(n) time and O(n) space.
    * Compute prefix sums in the array and store these prefix sums in a hash table. And check if current prefix sum - k is already present. If current prefix sum - k is present in the hash table and is mapped to index j, then subarray from j to current index has sum equal to k.


## Graph Traversal Algorithms

* DFS - Recursive(Using Stack). As u visit push to stack. Pop and see if all adjacent nodes are visited.
* BFS - Using Queue. Push all adjacent nodes.


Knights Tour

* Minimum steps to reach target by a Knight: Using BFS. The first hit that matches the target will be the minimum distance.Because in BFS we try all position of same distance always.

* Must visit all cells : Back Tracking. Backtracking is an algorithmic paradigm that tries different solutions until finds a solution that “works”. Recursively try to solve. If cannot solved, then backtrack and try other possibilities.
