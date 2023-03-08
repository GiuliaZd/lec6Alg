# Activities

## Task 1

- Refer to the following link. Discuss how Binary Search Trees work:
  https://www.cs.usfca.edu/~galles/visualization/BST.html
  answer:DONE in the class

## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-binary-search-tree/

Discuss the Time and Space complexity of Binary Search Tree (BST) operations (Searching, Insertion, Deletion) in the Best case, average case and worst case.
the answer:
OPERATION WORST CASE AVERAGE CASE BEST CASE SPACE
Search O(N) O(logN) O(1) O(N)
Insert O(N) O(logN) O(1) O(N)
Delete O(N) O(logN) O(N) O(N)

## Task 3

- Explain how the code in ./src/bst.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/introduction-to-binary-search-tree-data-structure-and-algorithm-tutorials/
  the answer: Insert a node into a BST: A new key is always inserted at the leaf. Start searching a key from the root till a leaf node. Once a leaf node is found, the new node is added as a child of the leaf node.

## Task 4: Individual (at home)

- Refer to te following link. Explain how In-order Traversal is used to print a binary search tree.
  https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html#inorder-traversal
  answer:
  An inorder traversal first visits the left child (including its entire subtree), then visits the node, and finally visits the right child (including its entire subtree). The binary search tree makes use of this traversal to print all nodes in ascending order of value.
  So the items are "collected" in the growing order, thus making the traversal In-order.

## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/binary-search-tree-data-structure/
