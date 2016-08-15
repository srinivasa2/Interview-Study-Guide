#Study Guide Topics


These will be discussed:

1. Sorting Algorithms
  * Bubble Sort
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
2. Data Structures
  * Singly Linked List
  * Doubly Linked List
  * Circular Linked List
  * Bit Maps
  * Queue
  * Stack
  * Deque
  * Hash Table
  * Hash Map
  * Hash Set
  * Set (Interface)
  * Map (Interface)
  * Binary Tree
  * Binary Search Tree
  * Red-Black Tree
  * AVL Tree
  * Spanning Tree
  * Graphs (Undirected, Weighted Acyclic, Tree, Forest)
  * Flow Network (aka directed graph)
  * Priority Queue
  * Trie
  * Suffix Tree
  * Heap
  * Binary Heap
3.  General Alogirthms
  * Binary Search
  * Knuth–Morris–Pratt Algorithm
  * Robin-Karp Alogirthm
  * Dijkstra's Algorithm
  * A*
  * Depth First Search
  * Breadth First Search
  * Minimum Spanning Tree
  * MST Prim's
  * MST Kruskal's
  * Chu-Li Edmond's (Directed Graphs)
  * LRU cache
  * Knapsack [Dynamic]
  * Fibonacci [Dynamic]
  * Towers of Hanoi [Dynamic]
  * Longest Common Subsequence [Dynamic]
  * Ford-Fulkerson Algorithm
  * Min-Max Theorem (Network Flow)
  * Simplex (Network Flow)
  * Blossom algorithm (Graph)
  * Steinhaus Johnson Trotter (Permutations)
4. Common Interview Problems
  * Palindromes
  * Most/Least common character
  * Longest Alphabetized Substring
  * Word Ladder
  * Linked-List/Graph Traversal (Sum)
  * Backtracking
  * DFS/BFS
5. Networking
  * Network Layer
  * HTTP Protocol
  * SSL
  * IP Routers
  * TCP & UDP
  * Subnetting Mask
  * STMP & POP3
  * Ping
  * TCP Handshake
  * Browser; what happens?
6. OS
  * Process & Threads
  * Memory organization
  * Booting Process
  * Deadlock
  * Starvation
  * IPC
  * Inode
  *Extras: Daemon, etc.
7. Databases
  * SQL Queries
  * Indexing
  * Normalization
  * ACID
  * SQL Injection & Prevention (security)
  * Inner and Outer Join
8. Architecture
  *Backend Architecture
9. UNIX




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
  <td>O(n*log(n))</td><td>O(n*log(n))</td><td></td><td> </td>
</tr>
  <!---->
<tr><th>Quick Sort</th>
   <td>O(n*log(n))</td><td>O(n<sup>2</sup>)</td><td></td><td> </td>
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
  <td> You require a consistent runtime  </td>
  <td>X </td>
</tr>
<!---->
<tr><th>Quick Sort</th>
  <td> Stable runtime isn't required. You may randomize your pivot selection in order to get more </td>
  <td>X </td>
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





<table><thread><tr>
    <th>Data Structure</th>
    <th> Methods  </th> <th>Runtimes </th> <th> Java Code </th>
  </tr></thread><tbody>

<tr><th>Singly Linked List</th>
  <td> X</td> <td>X </td>
  <td> <a href =  "https://github.com/ChristianCSE/MyStructures/blob/master/src/LinkedLists/SinglyLinkedList/SinglyLinkedList.java"> Done</a></td>
</tr>
<!---->
<tr><th>Doubly Linked List </th>
  <td> X</td> <td>X </td>
  <td><a href="https://github.com/ChristianCSE/MyStructures/blob/master/src/LinkedLists/DoublyLinkedList/DoublyLinkedList.java"> Done </a></td>
</tr>
<!---->
<tr><th>Circular Linked List</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Bit Map</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Queue</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Stack</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Deque</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Hash Table</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Hash Map</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Hash Set</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Set</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Map</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Binary Tree</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Binary Search Tree</th>
  <td> X</td> <td>X </td>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/DataStructures/tree/BST.java"> Done </a> </td>
</tr>
<!---->
<tr><th>Priority Queue</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Red-Black Tree</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>AVL Tree</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th> Spanning Tree</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Graphs (Undirected, Weighted Acyclic, Tree, Forest)</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Flow Network (aka directed graph)</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Trie</th>
  <td> X</td> <td>X </td>
   <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/tree/master/src/DataStructures/trie"> Done </a> </td>
</tr>
<!---->
<tr><th>Suffix Tree</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
<!---->
<tr><th>Heap</th>
  <td> X</td> <td>X </td>  <td>X </td>
</tr>
 </tbody></table>





<table>
<thread>
  <tr>
    <th>Data Structure Specifics</th>
    <th>Explain</th>
  </tr>
 </thread><tbody>

<tr><th>Singly Linked List</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Doubly Linked List </th>
  <td> X</td>
</tr>
<!---->
<tr><th>Circular Linked List</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Bit Map</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Queue</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Stack</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Deque</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Hash Table</th>
  <td> Synchronized, allows duplcates, doesn't allow nulls, (K,V) </td>
</tr>
<!---->
<tr><th>Hash Map</th>
  <td> No duplicates, not synchronized, order is not maintained, not thread safe, allows null</td>
</tr>
<!---->
<tr><th>Hash Set</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Set</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Map</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Binary Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Binary Search Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Priority Queue</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Red-Black Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th>AVL Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th> Spanning Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Graphs (Undirected, Weighted Acyclic, Tree, Forest)</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Flow Network (aka directed graph)</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Trie</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Suffix Tree</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Heap</th>
  <td> X</td>
</tr>
<!---->
<tr><th>Binary Heap</th>
  <td> X</td>
</tr>

 </tbody></table>




<table><thread><tr>
    <th>General Algorithms </th>
    <th>Runtimes</th><th>Java Code</th>
  </tr></thread><tbody>
<tr><th> Binary Search</th>
  <td> X</td><td>  <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/algorithms/binarySearch.java"> Done </td>
</tr>
<!---->
<tr><th> Knuth-Morris-Pratt </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Robin-Karp </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Dijkstra's</th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>A*</th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Depth First Search </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Breadth First Search </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Minimum Spanning Tree </th>
  <td> X </td><td> X </td>
</tr>
<!---->
<tr><th>MST Prim's </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>MST Kruskal's </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Chu-Li Edmond's </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> LRU cache </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Knapsack [Dynamic] </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Fibonacci [Dynamic] </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Towers of Hanoi [Dynamic] </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Longest Common Subsequence [Dynamic] </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th>Ford-Fulkerson </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Min-Max Theorem </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Simplex </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Blossom </th>
  <td> X</td><td> X </td>
</tr>
 </tbody></table>




<table><thread><tr>
    <th>Common Questions </th>
    <th>Complete/Examples ? </th> <th>Data Structures/Concepts Used </th>
  </tr></thread><tbody>

<tr><th> Palindromes </th>
  <td> <a href = ""> </td><td> X </td>
</tr>
<!---->
<tr><th> Permutations </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/general/allPermutations/allPermutations.java"> Done </td> <td> X </td>
</tr>
<!---->
<tr><th> Bracket Pairing </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/general/closedBrackets/closedBrackets.java"> Done </td>
  <td> X </td>
</tr>
<!---->
<tr><th> String compression (aa->a2) </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/companies/yelps/stringcompression.java"> Done</a></td>
  <td> X </td>
</tr>
<!---->
<tr><th> Print a Ladder </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/general/printLadder/ladderVPrint.java"> Done </a></td><td> X </td>
</tr>
<!---->
<tr><th> Least common character </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Most common character </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Longest Alphabetized Substring </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Word Ladder </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Singly Linked List Sum Traversal </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Graph Traversal </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Only Unique Chars </th>
  <td> <a href="https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/Mix-Of-Problems/Uniq-Chars/UniqueChars.java">  Done</a></td>
  <td> X </td>
</tr>
<!---->
<tr><th> Inverting a Tree </th>
  <td> <a href = " https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/DataStructures/tree/Test-tree/invertBST.java"> Done </a></td>
  <td> X </td>
</tr>
<!---->
<tr><th> Backtracking </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Anagrams </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/leetcode/groupAnagrams/Solution.java"> Done </a></td>
  <td> X </td>
</tr>
<!---->
<tr><th> DFS </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> BFS </th>
  <td> X</td><td> X </td>
</tr>
<!---->
<tr><th> Binary Gap </th>
  <td> <a href = "https://github.com/ChristianCSE/PracticeProgramming/blob/master/src/codility/binarygap/binarygap.java"> Done </a></td>
  <td> X </td>
</tr>
</tbody></table>



<table><thread><tr>
    <th>5. Newtorks </th>
    <th> Explain</th>
  </tr></thread><tbody>


<tr><th> Network  </th>
  <td> A network is a collection of PC's or PC-like devices that can communicatie across a common transmission medium. <br/>
A network protocol; however, is a system of common rules that define the complex process of network communication.</td>
  </tr>

<tr><th> Network Layer </th>
  <td> X</td>
</tr>

<tr><th> TCP/IP Protocols </th>
<td>
SMTP: Simple Mail Transfer Protocol <br/>
MIME: Multi-purpose Internet Mail Extensions <br/>
POP: Post Office Protocol <br/>
IMAP: internet Message Access Protocol
</td>
</tr>



<tr><th> TCP/IP Protocol Stack  </th>
<td>
Application L. (FTP, HTTP, Telnet)<br/>
Transport L. (TCP or UDP)<br/>
Internet L. (IP)<br/>
Network Access L. (Ethernet,etc) <br/>
Each layer is used for a particular connection. Each layer also wraps around a section of the packet.  <br/>
At each layer, the packet consists of two parts; header and body: <br/>
<b>Header</b>: Protocol information w.r.t. layer. <br/>
<b>Body</b>: Data w.r.t. layer.  This usually consists of a whole packet form the next layer in the stack.  <br/>
Each layer treats the info it gets from layer above. Each layer also applies its own header to that data.  Nothing is lost; hence, the packet contains all info passed from higher layer : encapsulation.
</td>
</tr>






<tr><th> TCP/IP</th>
  <td>
  Network communication process, how a unit of data should look like, and what info it should contain. All of this is so the receiving PC can interpret the message correctly. <br/>
  TCP/IP Standards =/= TCP/IP implementation <br/>
  Implementation: Software components that perform function to enable PC’s to partake in networks <br/>
  Standards: System of rules defining communication on networks. This ensures compatibility. <br/>
  Hence, one can understand that the TCP/IP model does not provide the services for its 4 layers: Application, Transportation, Internet, Network Access<br/>
  Instead the model acts more like an interface, as it defines the service that should be provided, but offers no implementation of said services. Software implementation: The provider of the services. <br/>
  <br/>
  <b>End node verification</b>: 2 PC"s communicaion and they are at the end of the messaging chain. <br/>
<b>Dynamic routing</b>:  Multiple paths and the router chooses a path for the data based on conditions. <br/>

  </td>
  </tr>

</tr>HTTP Protocol</th>
  <td> X</td>
</tr>


<tr><th>  SSL </th>
  <td> X</td>
</tr>


<tr><th> IP Routers  </th>
  <td>
  IP Routers: IP packets are sent through here; hence, its purpose is to send these packets to their correct destination. Paths may vary, even when being sent to the same end point. It does this by being mindful of : correct addressing, traffic volume, errors in the network, etc. <br/>
  32 bits or four 10-base digits, where each the maximum value is 255 for each. By this it means: aaa.bbb.ccc.ddd each 10-decimal representation can be of value (0-255). In other words each value is represented as an 8 bit binary value <br/>
  We know from binary arithmetic that an 8 bit number has 256 UNIQUE values, but a maximum value of 255. It is also important to note, that each computer has a unique IP value. <br/>
  We currently run on IPv4: 2^32.
  </td>
</tr>


<tr><th> TCP & UDP  </th>
  <td> X</td>
</tr>


<tr><th>  Subnetting Mask </th>
  <td> X</td>
</tr>


<tr><th>  STMP & POP3 </th>
  <td> X</td>
</tr>


<tr><th> Ping  </th>
  <td> X</td>
</tr>


<tr><th> TCP Handshake  </th>
  <td> X</td>
</tr>


<tr><th>  Browser; url? </th>
  <td> A web address is translated to a number by a DNS. When domain names are registered together with a TCP/IP address, the DNS update this information. </td>
</tr>


</tbody></table>



<table><thread><tr>
    <th>6. OS </th>
    <th> Explain</th>
  </tr></thread><tbody>


<tr><th>  Process & Threads </th>
  <td> X</td>
</tr>


<tr><th>  Memory Organization (Stack & Heap) </th>
  <td> X</td>
</tr>


<tr><th> Booting Process  </th>
  <td> X</td>
</tr>


<tr><th>  Starvation </th>
  <td> X</td>
</tr>


<tr><th>  IPC </th>
  <td> X</td>
</tr>


<tr><th>  Inode </th>
  <td> X</td>
</tr>


<tr><th> daemon </th>
  <td>
  Program running as a background process rather than direct control of an interactive user.  <br/>
  </td>
</tr>




</tbody></table>





<table><thread><tr>
    <th>7. Databases </th>
    <th> Explain</th>
  </tr></thread><tbody>

<tr><th>  SQL Queries</th>
  <td> X</td>
</tr>


<tr><th> Indexing </th>
  <td> X</td>
</tr>


<tr><th>Normalization</th>
  <td> X</td>
</tr>


<tr><th> ACID  (Atomicity, Consistency, Isolation, Durability) </th>
  <td> X</td>
</tr>


<tr><th> SQL Injection & Prevention </th>
  <td> X</td>
</tr>


<tr><th> Inner & Outer Join </th>
  <td> X</td>
</tr>


<tr><th>  Distribute Systems </th>
  <td> X</td>
</tr>

</tbody></table>





<table><thread><tr>
    <th>8. Architecture </th>
    <th> Explain</th>
  </tr></thread><tbody>

<tr><th>  Backend Architecture </th>
  <td>
      Scaling: <br/>
      Web Servers: <br/>
      Languages: <br/>
      Databases: <br/>
  </td>
</tr>


</tbody></table>



<table><thread><tr>
    <th>9. UNIX </th>
    <th> Explain</th>
  </tr></thread><tbody>

<tr><th> Basic commands </th>
  <td>
   "< " Read <br/>
   "> " Write <br/>
   "|" Pipe: This takes stdOut from the previous proces and uses it in stdIn of the next process. Pipes, in the
   command line at least, are unidirectional. <br/>
   </td>
</tr>



</tbody></table>

