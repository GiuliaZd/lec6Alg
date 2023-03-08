# Activities

## Task 1: Tree Definition

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/DefSumm.html
  answer:
  Select the one true statement.- None of the above
  What is the minimum number of internal nodes in a binary tree with 8 nodes? - 4
  Suppose T is a binary tree with 14 nodes. What is the minimum possible height of T? -3
  Which statement is false? - Every binary tree has at least one node
  What is the minimum number of nodes in a complete binary tree with height 3? - 8

## Task 2

- Explain how the code in ./src/bt.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-tree-array-implementation/

## Task 3: Tree Traversal

Refer to the following links. Discuss the difference between the different ways binary trees can be traversed.

- [Pre-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPreorderPRO.html)
- [Post-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPostorderPRO.html)
- [In-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravInorderPRO.html)
  answer: pre-order traversal: The first node printed is the root. Then all nodes of the left subtree are printed (in preorder) before any node of the right subtree.(ie we make sure that we visit any given node before we visit its children).
  post-order traversal: we wish to visit each node only after we visit its children (and their subtrees). We would like to delete the children of a node before deleting the node itself. But to do that requires that the children’s children be deleted first, and so on.
  in-order traversal: first visits the left child (including its entire subtree), then visits the node, and finally visits the right child (including its entire subtree). The binary search tree makes use of this traversal to print all nodes in ascending order of value.

## Task 4: Individual (at home)

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/TravSumm.html
  the answer:
  1.Visiting each element in a tree is known as: - traversing
  2.When you print out the nodes of binary tree, the leaf nodes appear in the same relative order for the preorder, inorder, and postorder traversals. -true
  3.If you are given the order of the nodes as visited by a preorder traversal and the order of the nodes as visited by an inorder traversal, do you have enough information to reconstruct the original tree? Assume that the nodes all have unique values. - true
  4.Why does function preorder2() presented in the Traversal module make only half as many recursive calls as function preorder()?-Because half of the pointers are null
  5.The n nodes in a binary tree can be visited in: - O(n) time

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/Treeprobs.html
  the answer:
  1. What is the depth of this tree? - Trees have height -- they do not have depth
     2.How many nodes in the tree have at least one sibling? - 6
  2. How many descendents does the root of this tree have? - 8
     4.What is the height of this tree? -3
     5.Which statement is correct? - th tree is neither full nor complete

## Links

- https://cpp.sh/
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTree.html
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html
