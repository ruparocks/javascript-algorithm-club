# javascript-tree-traversal

This is a work in progress. Every few years, I try to go back and revisit basic programming concepts to ensure that my memory is not fading away. 

Review tree traversal: https://en.wikipedia.org/wiki/Tree_traversal

According to the link above, tree traversal (also known as tree search) is a form of graph traversal and refers to the process of visiting (checking and/or updating) each node in a tree data structure, exactly once. Such traversals are classified by the order in which the nodes are visited. The following algorithms are described for a binary tree, but they may be generalized to other trees as well.

Things to remember:
- Unlike linear data structures, trees can be traversed differently. 
- There are three main steps for traversing a tree: visiting the current node, traversing to the left child, and traversing to the right child
- Since each node can have more that one child node, some nodes must be deferred in some way (stack/queue)
- A tree is a self-referential data structure, so traversal can be done with recursion or corecursion (https://en.wikipedia.org/wiki/Corecursion)

