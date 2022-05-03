# leetcode
This is a repository for me to work on problems for leetcode.com

Binary Tree:
Binary tree is a tree type data structure that has at most two children (left and right) Objectives in this area are:
1. Understand the concepts of a binary tree and trees more generally.
2. Familiarize with traversal methods (iterating over trees).
    - Pre-order Traversal:
        - Pre-order traversal is a traversal algorithm with in which you start from the root node and traverse the left subtree then the right subtree.
    - In-order Traversal:
        - In-Order traversal is a traverrsal algorithm where you search the left subtree then back track to the root node then search the right subtree.
        - Typically for a binary search tree you can retrieve the data in sorted order using in order traversal.
    - Post-order Traversal
        - Traversal algorithm where you search the left subtree, then the right subtree, you always end the search with root.
        - When a tree or subtree is deleted this is done in post-order (children of a node must be deleted before the node itself is).
        - Post order is also widely used in mathematical expressions since it's easier to parse them in post-order.
    - NOTE: When working with these methods attempt to implement each in both recursive and iterative formats.

3. Use Recursion to solve binary-tree problems.

PROBLEMS:
1. Binary Tree Preorder Traversal - Given the root of a binary tree, return the preorder traversal of it's node's values.
    - EXAMPLE 1:
        1
         \
          2
         /
        3

    - Input1: root = [1, null, 2, 3]
    - Output1: [1,2,3]

    - Input2: root = []
    - Output2: []
    
    - Input3: root = [1]
    - Output3: [1]

    - CONSTRAINTS:
        - The number of nodes in the tree is in the range [0, 100]
        - -100 <= Node.val <= 100
    
    - Language: Java
    - Code File: ./BinaryTrees/BinaryTreePreorderTraverseal


Stack:

Recursion I:

Dynamic Programming:
