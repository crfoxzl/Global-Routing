# Global-Routing
This programming assignment asks you to write a global router that can route 2-pin nets (connection between two points). The problem description below is a simplified routing problem. Given the problem size (the number of horizontal and vertical tiles), capacity, and a netlist, the global router routes all nets in the routing region. The main objective is to minimize the total overflows. Here the overflow on a tile boundary is calculated as the amount of demand that excesses the capacity, i.e., overflow = max(0, demand- capacity).

# Input
The file format for the global routing is illustrated, with comments in italics (these will not be in actual input files). The 1st line gives the problem size in terms of the number of horizontal and vertical tiles. Each global routing tile (tile in short) has a capacity on its four boundaries to measure the available space, which is the maximum number of routing paths passing through boundaries. The capacity value is given by the 2nd line. The 3rd line gives the number of nets and following indicate each net, including starting position and terminal position.

# Output
All the routes in the output could only be horizontal lines and vertical lines. For example (18, 61)-(19, 62) is not acceptable, because it is diagonal. Remember that each route could be different either in the x or y location only, and the difference must be 1.

# Example
<img width="599" alt="2017-06-04 6 10 27" src="https://cloud.githubusercontent.com/assets/28750963/26760652/32e57e7c-4951-11e7-8b4a-82abd9cb0ca6.png">
<img width="1020" alt="2017-06-04 6 10 43" src="https://cloud.githubusercontent.com/assets/28750963/26760659/439cec96-4951-11e7-8ea2-fba3248baaa6.png">

# Compile

# Usage

# REMARK
This is a homework of Algorithm Lesson NTUST 2017 fall semester. By using Dijkstra shortest path algorithm and some BFS techique.
