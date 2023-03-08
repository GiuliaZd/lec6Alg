# Activities

## Task 1

- Refer to the following link. Discuss how Min Heap data structure works:
  https://www.cs.usfca.edu/~galles/visualization/Heap.html
  the answer: if the value is greater than in the exisiting node, it just moves to the leaf place of the node(from the left to the right; filling all the possible possitions). If the value is smaller than in the parent node, it would swap with a node value. And swapping will go on up to root level for example, if the given value is the minimum possible value of the entire tree.

## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-heap/

Discuss the Time and Space Complexity of Heap data structure operations, in the Best case, average case and worst case.
the answer: the article was read and alalyzed, the final results are copied from there.
OPERATION TIME COMPLEXITY SPACE COMPLEXITY
Insertion Best Case: O(1) O(1)
Worst Case: O(logN)
Average Case: O(logN)
Deletion Best Case: O(1) O(1)
Worst Case: O(logN)
Average Case: O(logN)
Searching Best Case: O(1) O(1)
Worst Case: O(N)
Average Case: O(N)
Max Value In MaxHeap: O(1) O(1)
In MinHeap: O(N)
Min Value In MinHeap: O(1) O(1)
In MaxHeap: O(N)
Sorting All Cases: O(NlogN) O(1)
Creating a Heap By Inserting all elements: O(NlogN) O(N)
Using Heapify O(N) O(1)

## Task 3

- Explain how the code in ./src/priority-queue.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/priority-queue-using-binary-heap/

## Task 4: Individual (at home)

- Explain how the code in ./src/heap.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-heap/

## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/array-representation-of-binary-heap/
