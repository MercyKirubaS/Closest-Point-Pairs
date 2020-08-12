# The-Closest-Pair-Of-Points-Problem
Applying the closest pair algorithm to find the closest pair (distance) from a random pair of Values. A C++ program Implementation from scratch.

## Algorithm Description
To find the pair of points, whose distance is minimum in a set of n points are given on the 2D plane.
I have divided the problem into two halves. 
Then the smallest distance between two points is calculated in a recursive way. 
Using distances from the middle line, the points are separated into some strips and smallest distance is found from the strip array.

Two lists are created with data points:

•	To hold data points which are sorted on x values.

•	To hold data points which are sorted on y values.

The time complexity of this algorithm will be O (n log n)
