#Sorting Algorithms
  * Bubble Sort <a href = "https://github.com/ChristianCSE/Interview-Study-Guide/blob/master/99-answerKey/algorithms/sorting/comparison-based/Bubble-Sort/BubbleSort.java"> [Complete: Java] </a>
  * Selection Sort
  * Insertion Sort
  * Mergesort
  * Quicksort
  * Intro Sort
  * Tim Sort
  * Radix Sort Distribution Based|
  * Bucket Sort [Distribution Based]
  * Shell Sort
  * Topological Sort


<ul>
<li>O(1) < O(log(n)) < O(n) < O(n*log(n)) < O(n<sup>2</sup>) < O(2<sup>n</sup>) < O(n!)</li>
</ul>

<table><thread><tr>
    <th>Sorting Algorithm</th>
    <th>Best Case</th><th>Worst Case</th><th>Avg Case [If applicable]</th>
    <th>Space Complexity</th>
  </tr></thread><tbody>

<tr><th>Bubble Sort</th>
  <td>O(n)</td><td>O(n<sup>2</sup>)</td><td></td><td> </td>
</tr>
<!---->
<tr><th>Selection Sort</th>
  <td>O(n<sup>2</sup>) </td><td> O(n<sup>2</sup>) </td><td> </td><td> </td>
</tr>
  <!---->
<tr><th>Insertion Sort</th>
  <td>O(n)</td><td>O(n<sup>2</sup>)</td><td></td><td> </td>
  </tr>
<!---->
<tr><th>Merge Sort</th>
  <td>O(n*log(n))</td>
  <td>O(n*log(n))</td>
  <td></td>
  <td> </td>
</tr>
  <!---->
<tr><th>Quick Sort</th>
   <td>O(n*log(n))</td>
   <td>O(n<sup>2</sup>)</td>
   <td>O(n*log(n))</td>
   <td> </td>
</tr>
<!---->
<tr><th>Intro Sort</th>
     <td>O(n*log(n))</td><td>O(n*log(n))</td><td></td><td> </td>
</tr>
<tr><th>Tim Sort</th>
  <td>O(n)</td><td>O(n*log(n))</td><td></td><td> </td>
</tr>
  <!---->
<tr><th>Radix Sort [Distribution Based]</th>
<td> </td><td></td><td></td><td> </td>
</tr>
  <!---->
<tr><th>Bucket Sort [Distribution Based]</th>
<td></td><td></td><td></td><td> </td>
</tr>
  <!---->
<tr> <th>Shell Sort</th>
<td></td><td></td><td></td><td> </td>
</tr>
  <!---->
<tr> <th>Topological Sort</th>
<td></td><td></td><td></td><td> </td>
</tr>
  <!---->
 </tbody></table>


<table><thread><tr>
    <th>Sorting Algorithm Explained</th>
    <th> When to use? </th><th>Explain Runtime & Space Complexity</th>
  </tr></thread><tbody>

<tr><th>Bubble Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Selection Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Insertion Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Merge Sort</th>
  <td> <b>Why</b>: Merge sort is used when one requires a consistently recurring runtime, O(N*log(N)). While consistency is obtained, there is the downside of requiring an auxillary array O(N).
  <br/>
  <b>Important Caveat</b>: Professor Kevin Wayne, has said that in many cases recursion is faster than iteration because of caching improved performances.
  </td>
  <td> </td>
</tr>
<!---->
<tr><th>Quick Sort</th>
  <td>
  <b>Why</b>: Use this when you do not require a stable sort and average case performance matters more than worst case performance.
  </td>
  <td>
<b>BC</b>: O(log(N)) Best case is when the pivot is the median value (not the middle index) of the array. Once, you partition and swap, the resulting array will have its left and the right parts as the same size.
<hr/><br/>
<b>WC</b>: O(N^2) Worst case occurs when you pick a pivot that is either the smallest or largest value in the array.
<hr/><br/>
<b>Avg</b>: O(Nlog(N)) Average case occurs when there are log(N) partitions. In order to obtain each partitions, N comparisons are made. The number of swaps; however, are no more than N/2. From this, one obtains that the complexity is O(Nlog(N))
   </td>
</tr>
<!---->
<tr><th>Intro Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Tim Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Radix Sort [Distribution Based]</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Bucket Sort [Distribution Based]</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Shell Sort</th>
  <td> X</td> <td>X </td>
</tr>
<!---->
<tr><th>Topological Sort </th>
  <td> X</td> <td>X </td>
</tr>
<!---->
</tbody></table>
