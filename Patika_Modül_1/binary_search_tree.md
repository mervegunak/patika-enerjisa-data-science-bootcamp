# **Binary Search Tree Project**


      C = [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. Write Binary-Search-Tree steps.
2. Write the Big-O notation.

#### **Answer 1**

Step 1 − Root : 7

Step 2 − 
* As 5 < 7, so insert 5 to the left of 7.

Step 3 − 
* As 1 < 7, so insert 1 to the left of 7.
* As 1 < 5, so insert 1 to the left of 5.

Step 4 − 
* As 7 < 8, so insert 8 to the right of 7.

Step 5 − 
* As 3 < 7, so insert 3 to the left of 7.
* As 3 < 5, so insert 3 to the left of 5.
* As 1 < 3, so insert 3 to the right of 1.

Step 6 − 
* As 6 < 7, so insert 6 to the left of 7.
* As 5 < 6, so insert 6 to the right of 5.

Step 7 − 
* As 0 < 7, so insert 0 to the left of 7.
* As 0 < 5, so insert 0 to the left of 5.
* As 0 < 1, so insert 0 to the left of 1.

Step 8 − 
* As 7 < 9, so insert 9 to the right of 7.
* As 8 < 9, so insert 9 to the right of 8.

Step 8 − 
* As 4 < 7, so insert 4 to the left of 7.
* As 4 < 5, so insert 4 to the left of 5.
* As 1 < 4, so insert 4 to the right of 1.
* As 3 < 4, so insert 4 to the right of 3.

Step 8 − 
* As 2 < 7, so insert 2 to the left of 7.
* As 2 < 5, so insert 2 to the left of 5.
* As 1 < 2, so insert 2 to the right of 1.
* As 2 < 3, so insert 2 to the left of 3.

#### **Answer 2**

Big-O Notation: O(logn)









