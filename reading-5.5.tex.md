# Reading Questions - Section 5.5

1. Consider the set of points {(1,4), (6,3), (2,3), (4,4), (8,2), (3,10)}. 
Give the ordered lists P and Q as suggested in the book (page 192).


2. Consider the divide-and-conquer algorithm to solve *Closest-Pairs*.
    a. There are three possibilities for where the smallest distance is. What are they?

    b. Why do we only need to consider points that are of distance at most d from the vertical strip? (Hint: in your answer, you will need to make use of how d is defined.)

    c. Why is it important to consider the points in order by y coordinate in the second part of the algorithm (the non-recursive part)?


3. Consider the following points. When doing computations, you can just use your best guess since the exact coordinates are not given.

    ![A bunch of points](imgs/points-55.png)

    Show the result of each of the following on separate drawings (do your best to recreate the location of the points).

    1. Show the first step of the *quickhull* algorithm. Clearly label p1 and pn.

    2. Do the next step of the *quickhull* algorithm for the upper hull. Clearly label pmax.

    3. Do the next step of the *quickhull* algorithm for the lower hull. Clearly label pmax.

    4. Do one more step for the lower hull (which will involve 2 more subproblems).

    5. Do one more step for the lower hull (which will involve 2 more subproblems).


4. Describe a set of points that might be considered a worst-case input for *quickhull*.


