## TREES:

- it is a fundamental data structure in computer science. Trees are widely used to represent hierarchical relationships and are crucial in various algorithms and applications.

Common Terminology
- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

_ _ _
![BinaryTree1](./BinaryTree1.png)
_ _ _
* Traversals :Tree traversal refers to the process of visiting each node in a tree. There are two categories of traversals when it comes to trees:

1. Depth First :is where we prioritize going through the depth (height) of the tree first.
* Pre-order: root >> left >> right
* In-order: left >> root >> right
* Post-order: left >> right >> root

2. Breadth First

/ The most common way to traverse through a tree is to use recursion , the describtion is in this link 
[recursion in trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

_ _ _
Quiz: Trees

What is a tree in the context of computer science?
a) A linear data structure
b) A non-linear data structure
c) A graph data structure
d) A collection of nodes

Which of the following is NOT a key terminology associated with trees?
a) Root
b) Parent
c) Child
d) Link

What is the purpose of tree traversal?
a) To rearrange the nodes in a tree
b) To remove leaf nodes from the tree
c) To visit each node in a tree
d) To balance the tree structure

In a binary tree, each node can have a maximum of how many children?
a) 0
b) 1
c) 2
d) 3

What is the main characteristic of a binary search tree (BST)?
a) All nodes have the same value.
b) The left child's value is greater than the parent's value.
c) The right child's value is less than the parent's value.
d) The tree has a balanced height.

Answers:

b) A non-linear data structure
d) Link
c) To visit each node in a tree
c) 2
c) The right child's value is less than the parent's value.