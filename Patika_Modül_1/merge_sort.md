# **Merge Sort Project**

    B = [16,21,11,8,12,22]  

1.Write the stages of the array according to the sort type.

2.Write the Big-O notation.

#### **Answer 1**

Step 1 − We divide the array into 2 parts. The  sub-arrays left half and right half:

      [16 21 11]                        [8 12 22]


Step 2 − These arrays of size 3 is divided into 2 sub-arrays:

* Left side, the first consisting of elements (16,21) and the second one being (11) 
* Right side, the first consisting of elements (8,12) and the second one being (22)


      [16 21]  [11]                      [8 12]   [22]


Step 3 − We split into single element arrays:

* Left side, the first array consisting of elements (16,21) is divided into 2 subarrays consisting of elements 16 and 21 respectively.
* Right side, the first array consisting of elements (8,12) is divided into 2 sub-arrays consisting of elements 8 and 12 respectively.

      [16]  [21]                     [8]  [12]  


Step 4 − We start to merge these arrays:

* We compare the element for each array and then combine them into another array in a sorted manner.
* Sort each array in itself

* Left side, 2 sub-arrays formed in the last step are then merged together in sorted order leading to a new array.
* Right side, 2 sub-arrays formed in the last step are then merged together in sorted order leading to a new array.

 
      [16 21]                          [8 12] 


Step 5 − Merge  :

* We need to merge the array consisting of elements 11 and 22 too with this arrays, leading to the new sorted arrays.


      [11 16 21]                        [8 12 22] 


Step 6 − We will merge these 2 halves to create the final sorted array:

      Final merged and sorted array: [ 8, 11, 12, 16, 21, 22]

#### **Answer 2**

Big-O Notation: O(nlogn)
