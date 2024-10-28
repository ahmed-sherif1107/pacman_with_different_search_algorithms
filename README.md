# pacman_with_different_search_algorithms
this is a python project which solves pacman using different search algorithms like : UCS , DFS , BFS , A#


to try out this game , download the folder and write the following commands in the CLI :

python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5 
python pacman.py -l trickySearch -p AStarFoodSearchAgent 
python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic 
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=ucs,heuristic=manhattanHeuristic 
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=bfs,heuristic=manhattanHeuristic 
