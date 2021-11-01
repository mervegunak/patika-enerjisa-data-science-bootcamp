# **Insertion Sort Project**


      A = [22,27,16,2,18,6]

1. Write the stages of the array according to the sort type.
2. Write the Big-O notation.
3. Time Complexity:
    * Average case: The number we are looking for is in the middle,
    * Worst case: The number we are looking for is at the end,
    * Best case: The number we are looking for is at the beginning of the array.
4. After the series is sorted, which case does the number 18 fall into?
5. X = [7,3,5,8,2,9,4,15,6] Write the first 4 steps according to insertion sort.




#### **Answer 1**

**First Iteration:**

* Compares the first two elements. 22 and 27 are already in ascending order. 

* Insertion sort moves ahead and compares 27 with 16. And finds that 27 is not in the correct position.


* It swaps 27 with 16. It also checks with all the elements of sorted sub-list. 16 < 22, we swap two.

                  Array now becomes: 16 22 27 2 18 6 

**Second Iteration:**

* Next, it compares 2 with 27. Since 2 < 27, we swap two. 

* It compares 2 with 22. Since 2 < 22, we swap two.

* It compares 2 with 16. 2 < 16, we swap two. 


                  Array now becomes: 2 16 22 27 18 6 
                                                 
**Third Iteration:**


* Next, it compares 18 with 27. Since 18 < 27, we swap two. 

* It compares 18 with 22. 18 < 22, we swap two.

* It compares 18 with 16. 16 < 18, no swapping takes place. 


                  Array now becomes: 2 16 18 22 27 6 

**Fourth Iteration:**

* The last iteration calls for the comparison of the last element (6), with all the preceding elements and make the appropriate swapping between elements.

* The last comparison for the iteration is to compare 6 with 2.

* Since 2 < 6, no swapping takes place.

                  The array now becomes: 2 6 16 18 22 27

This is the final array after all the corresponding iterations and swapping of elements.

#### **Answer 2**

Big O Notation :  Ο(n2)

#### **Answer 3**

Worst Case Time Complexity : O(n2)
 
Best Case Time Complexity : O(n)

Average Time Complexity : O(n2)

#### **Answer 4**

This is the final array :

      A = [2, 6, 16, 18, 22, 27]
      
Answer is : Average Case

#### **Answer 5**

B = [7,3,5,8,2,9,4,15,6]

Step 1 −  compares the first two elements, 3 < 7 no swapping takes place.

                 B = 3 7 5 8 2 9 4 15 6

Step 2 −  5 < 7 we swap the two.

                 B = 3 5 7 8 2 9 4 15 6
                 
Step 3 −  3 < 5 no swapping takes place.

                 B = 3 5 7 8 2 9 4 15 6
                 
Step 4 −  7 < 8 no swapping takes place.

                 B = 3 5 7 8 2 9 4 15 6

