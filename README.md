# DATA-STRUCTURE AND ALGORITHM 
Bubble Sort

A simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

Algorithm

1. Start at the beginning of the list.
2. Compare the first two elements.
3. If the first element is greater than the second element, swap them.
4. Move to the next pair of adjacent elements and repeat steps 2-3.
5. Repeat steps 1-4 until no more swaps are needed (the list is sorted).


Jump Search

A search algorithm for sorted arrays. It works by jumping ahead by fixed steps and then performing a linear search in the block where the element is likely to be.

Algorithm

1. Calculate the jump size (usually √n, where n is the size of the array).
2. Jump ahead by the jump size until the element at that index is greater than the target element or the end of the array is reached.
3. Perform a linear search backwards from the previous jump point to find the target element.
Finding the Second Largest Element

An algorithm to find the second largest element in an array or list.

Algorithm

1. Initialize two variables, largest and second_largest, to negative infinity or the smallest possible value.

2. Iterate through the array:
  - If the current element is greater than largest:
   - Update second_largest to the previous value of largest.
   - Update largest to the current element.
  - Else if the current element is greater than second_largest but not equal to largest:
   - Update second_largest to the current element.

3. After iterating through the entire array, second_largest will hold the second largest element. If second_largest is still at its initial value, it means there wasn't a distinct second largest value.


   
