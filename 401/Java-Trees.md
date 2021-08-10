# Trees

Trees are non-linear data structures. They are often used to represent hierarchical data.

## Terminology

* Node - it is a tree component that has value.
* Root - is the node where the tree starts.
* K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
* Left - A reference to one child node, in a binary tree
* Right - A reference to the other child node, in a binary tree
* Edge - The edge in a tree is the link between a parent and child node
* Leaf -  A leaf has a parent node but has no child node.
* Height - The height of a tree is the number of edges from the root to the furthest leaf.

## Types of Trees

* K-ary trees
* Balanced trees
* Binary trees
* Binary Search Trees
* AVL Trees
* Red-Black Trees
* 2-3 Trees
* 2-3-4 Trees

1. K-ary Tree

In K-ary tree, a node can have child nodes from 0-K.

![k-ary](https://media.geeksforgeeks.org/wp-content/uploads/tree-1-1-300x200.jpg)

2. Binary Search Trees

A Binary Search Tree is a binary tree in which every node has a key and a value.

![Binary](https://media.geeksforgeeks.org/wp-content/uploads/BSTSearch.png)

3. Binary Trees

* Complete Binary Tree

A complete binary tree exists when every level, excluding the last, is filled and all nodes at the last level are as far left as they can be

![Complete](https://www.techiedelight.com/wp-content/uploads/Complete-Binary-Tree.png)

* Full Binary tree

A full binary tree exits when every node, excluding the leaves, has two children.

![full](https://www.andrew.cmu.edu/course/15-121/lectures/Trees/pix/full_complete.bmp)

## Traversals

Unlike linear data structures (Array, Linked List, Queues, Stacks) which have only one logical way to traverse them, trees can be traversed in different ways.

![travers](https://media.geeksforgeeks.org/wp-content/cdn-uploads/2009/06/tree12.gif)

* Depth First

Depth first traversal is where we prioritize going through the depth (height) of the tree first.

Preorder (Root, Left, Right) : 1 2 4 5 3

Inorder (Left, Root, Right) : 4 2 5 1 3

Postorder (Left, Right, Root) : 4 5 2 3 1

* Breadth First

Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.

Breadth First or Level Order Traversal : 1 2 3 4 5
