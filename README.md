## 8-puzzle

A.I - Implemented BFS, DFS, A* and IDA* to solve the n-puzzle problem. The scripts prints the results to output.txt

### Algorithms

1. bfs (Breadth-First Search)
2. dfs (Depth-First Search)
3. ast (A-Star Search)
4. ida (Iterative-Deepening-Star Search)

### Usage

driver.py ast 0,8,7,6,5,4,3,2,1

### Results

1. path_to_goal: ['Right', 'Down', 'Down', 'Right', 'Up', 'Up', 'Left', 'Down', 'Down', 'Left', 'Up', 'Right', 'Down', 'Right', 'Up', 'Up', 'Left', 'Left', 'Down', 'Right', 'Up', 'Right', 'Down', 'Left', 'Down', 'Right', 'Up', 'Up', 'Left', 'Left']
2. cost_of_path: 30
3. nodes_expanded: 12893
4. fringe_size: 6327
5. max_fringe_size: 6328
6. search_depth: 30
7. max_search_depth: 30
8. running_time: 1.80822521
9. max_ram_usage: 7.44400000
