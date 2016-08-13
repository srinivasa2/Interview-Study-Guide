#Which Sort Is Used?

These will be discussed:

1. Quick Sort
  * Why: Use this when you do not require a stable sort and average case performance matters more than
worst case performance.
  * WC: O(N^2) Worst case occurs when you pick a pivot that is either the smallest or largest value in the array. 
  * BC: O(log(N)) Best case is when the pivot is the median value (not the middle index) of the array. Once, you partition and swap, the
resulting array will have its left and the right parts as the same size. 
  * Avg: O(N*log(N)) Average case occurs when there are log(N) partitions. In order to obtain each partitions, N comparisons are made. The number of swaps; however, are no more than N/2. From this, one obtains that the complexity is O(N*log(N))
  
2. Merge Sort
  * Why: Merge sort is used when one requires a consistently recurring runtime, O(N*log(N)). While consistency is obtained, there is the downside of
  requiring an auxillary array O(N). 
  * Important Caveat: Professor Kevin Wayne, has said that in many cases recursion is faster than iteration because of caching improved performances.
  * WC:
  * BC:
  * Avg:

3. Heap Sort
   * Why: 
   * WC:
   * BC:
   * Avg:
4. Intro Sort
   * Why:  
   * WC:
   * BC:
   * Avg:
5.Tim  Sort
   * Why:  
   * WC:
   * BC:
   * Avg:
6.Bubble  Sort
   * Why:  
   * WC:
   * BC:
   * Avg:
7. Selection  Sort
   * Why:  
   * WC:
   * BC:
   * Avg:
8. Radix Sort (Non-comparison Sort)
   * Why:  
   * WC:
   * BC:
   * Avg:
9. Bucket Sort (Non-comparison Sort)
   * Why:  
   * WC:
   * BC:
   * Avg:

Sorting  Algorith | WC | BC | Avg (if applicable)| When to use?
--- | --- | --- | --- | ---
Quick Sort | O(N^2) | O(log(N)) | O(N*log(N))| Stable runtime isn't required. You may randomize your pivot selection in order to get more stability. 
Merge Sort|O(n*log(n))| O(n*log(n))|X| You require a consistent runtime
Heap Sort| | | X| 
Intro Sort| | | X| 
Tim Sort| | | X| 
Selection Sort| | | X| 
Bubble Sort| | | X| 
Bubble Sort| | | X| 
Radix Sort| | | X| 
Bucket Sort| | | X| 


