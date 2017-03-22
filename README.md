# 8-puzzle

A.I - Implemented BFS, DFS, A* and IDA* to solve the n-puzzle problem. The scripts prints the results to output.txt

### Algorithms
```
bfs (Breadth-First Search)
dfs (Depth-First Search)
ast (A-Star Search)
ida (Iterative-Deepening-ΑStar Search)
```
### Usage
```
python driver.py ast 0,8,7,6,5,4,3,2,1
```
### Results
```
path_to_goal: ['Right', 'Down', 'Down', 'Right', 'Up', 'Up', 'Left', 'Down', 'Down', 'Left', 'Up', 'Right', 'Down', 'Right', 'Up', 'Up', 'Left', 'Left', 'Down', 'Right', 'Up', 'Right', 'Down', 'Left', 'Down', 'Right', 'Up', 'Up', 'Left', 'Left']
cost_of_path: 30
nodes_expanded: 12893
fringe_size: 6327
max_fringe_size: 6328
search_depth: 30
max_search_depth: 30
running_time: 1.80822521
max_ram_usage: 7.44400000
```
