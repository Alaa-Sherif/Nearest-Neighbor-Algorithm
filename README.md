# Introduction
This repository contains an implementation of the nearest neighbor heuristic algorithm for solving the Traveling Salesman Problem (TSP).

# What is TSP?
![tsp](https://co-enzyme.fr/wp-content/uploads/2020/06/tsp.jpg)

The Travelling Salesman Problem is a classic problem in computer science and optimization. In TSP we're trying to find the shortest route that visits a set of cities  only once then return to the starting point again.

# What is the Nearest-Neighbor-Algorithm?
The nearest neighbor heuristic algorithm is a simple and efficient approach to solving the TSP. It starts at a randomly selected city and repeatedly selects the closest unvisited city as the next stop on the tour. The algorithm continues until all cities have been visited, at which point it returns to the starting city to complete the tour.
- It works as follows:

   1. It starts at a randomly selected city
   2. Repeatedly selects the closest univisited city as the next stop
   3. Continues until all cities have been visited
   4. Then, returns to the starting city to complete the tour.

While heuristic algorithms don't reach an optimal solution but they reach a sub-optimal one, so it might not give us the absolute shortest route, it will give us a route that's close to the shortest one.

The NN is a greedy heuristic so it makes the best possible decision at each step based on the information available at that moment, without considering the consequences of that decision in the future.

# How the NN works for TSP
https://user-images.githubusercontent.com/43891138/223479079-40a34473-6a6d-4a43-86a7-323869cdaf33.mp4
