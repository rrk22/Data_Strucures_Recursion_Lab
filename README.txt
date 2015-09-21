Raheel Khoja
CS 314 Data Structures
Novak
UT EID: rrk549

Assignment 2: Recursion and Lists

2. One invariant property of peanoplus is the Big O of peanoplus, (When the compiler isn't changed).
Regardless of how big or small X and Y are respectively, the Big O of peanoplus will remain O(N). 
However, depending on the compiler, the Big(O) may be O(1).

3. The Big O of peanotimes is O(N^2),

because each peanotimes recursion has a Big O of O(N), and each of these peanotimes recursions calls
peanoplus, where each peanoplus call inside peanotimes has a Big O of O(N), resulting in the Big O
of peanoplus being O(N)*O(N) or O(N^2).

8. The value of (choose n k) is the same as the value of the binomial coefficient represented in 
the (k+1)th position of the (n+1)th row of Pascal's triangle.

i.e.
    1       n = 0 (Row 1)
   1 1	    n = 1 (Row 2)
  1 2 1     n = 2 (Row 3)
 1 3 3 1    n = 3 (Row 4)
1 4 6 4 1   n = 4 (Row 5)

(choose 4 0) = 1  <- 1st position of Row 5 of Pascal's Triangle
(choose 4 1) = 4  <- 2nd position of Row 5 of Pascal's Triangle
(choose 4 2) = 6  <- 3rd position of Row 5 of Pascal's Triangle
(choose 4 3) = 4  <- 4th position of Row 5 of Pascal's Triangle
(choose 4 4) = 1  <- 5th position of Row 5 of Pascal's Triangle