CS455 Module 2 DV1: Dijkstra   
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M2.DV1/ to play the game :)

# Behaviors
Dijkstra Path Follower: Assets/Scripts/PathFollower_Dijkstra.cs   
Dijkstra's Algorithm: Assets/Scripts/Dijkstra/Dijkstra.cs   
Dijkstra Graph Nodes: Assets/Scripts/Dijkstra/Node.cs   

# Notes
1. The Dijkstra Path Follower first runs Dijkstra's Algorithm to determine the best path to the target, then passes that path to the previously developed PathFollower steering behavior.  
2. Each Node has a list of nodes it has a path to, entered manually.   

# Bugs/issues
1. The paths between nodes are in no way displayed to the user - this makes the path the node takes appear somewhat arbitrary, for one does not know what paths actually exist.  
2. Each node has to be added to the Dikstra Path Follower manually or else it'll crash.  
 
