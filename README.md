Download Link: https://assignmentchef.com/product/solved-cs312-lab-1-uninformed-search
<br>
<span class="kksr-muted">Rate this product</span>

Task 1: Uninformed Search

Teach Pacman how to intelligently find his food! The objective of this task is to simulate breadth- first search, depth-first search, and DFID in the state space. The state-space consists of an m x n grid. The start state is (0,0). The goal state is the position of (*) in the grid. The Pacman is allowed to move UP, DOWN, LEFT and RIGHT (except for boundary).

Compare the above search methods on two accounts:1. Length of the path (from the initial state to the goal state) that each algorithm finds2. Number of states explored (visited) during the search.(The length of the path and the number of visited states are two different things). Also, analyze whether or not the result depends on the order in which the neighbors of each node are added into the list should be done.

The format of the report can be as follows:

1. Pseudo Code for MoveGen() and GoalTest()2. Results (include table, plots if applicable)3. Dependence of results on the order of neighbors added

Input format:

&lt;ALGORITHM CODE&gt; // 0 for bfs, 1 for dfs, 2 for dfid &lt;MAZE of m x n size&gt;

Output format:

&lt;Number of states explored&gt; &lt;Length of path found&gt;&lt;Maze with path formed with 0s&gt;

Evaluation Criteria:

Correctness: 30 Report: 15 Code Quality: 5

Note

Penalty of 10% will be issues per day if the deadline is not met If found copied, 0% score will be awarded

Sample Input 1:

0

<pre>+--+--+--+--+   |||</pre>

+++++ |||+–+–+ +–+ |||

<pre>+  +  +--+  +||        *+--+--+--+--+</pre>

Sample Output 1:

42 24

0–+–+–+–+ 00 |0000| | +0+0+0+ + |0000 |0 | +–+–+0 +–+ | |0000 | + + +–+0+ || 000 +–+–+–+–
