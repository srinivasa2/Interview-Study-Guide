#Which Sort Is Used?

These will be discussed:

1.  Quick Sort
  * Why: Use this when you do not require a stable sort and average case performance matters more than
worst case performance.
  * WC: O(N^2) Worst case occurs when you pick a pivot that is either the smallest or largest value in the array. 
  * BC: O(log(N)) Best case is when the pivot is the median value (not the middle index) of the array. Once, you partition and swap, the
resulting array will have its left and the right parts as the same size. 
  * Avg: O(N*log(N)) Average case occurs when there are log(N) partitions. In order to obtain each partitions, N comparisons are made. The number of swaps; however, are no more than N/2. From this, one obtains that the complexity is O(N*log(N))
  
2.  Merge Sort
3.  Heap Sort
4.  Intro Sort
5.  Bubble Sort
6.  Selection Sort
7.  Non-comparison Sort: 
8.  Radix Sort
9.  Bucket Sort

Sorting Algorith | WC | BC | Avg (if applicable)| When to use?
--- | --- | --- | --- | ---
Quick Sort | O(N^2) | O(log(N)) | O(N*log(N))| 
