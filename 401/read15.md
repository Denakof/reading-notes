# read15

Node - A Tree node is a component which may contain it’s own values, and references to other nodes
Root - The root is the node at the beginning of the tree
K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
Left - A reference to one child node, in a binary tree
Right - A reference to the other child node, in a binary tree
Edge - The edge in a tree is the link between a parent and child node
Leaf - A leaf is a node that does not have any children
Height - The height of a tree is the number of edges from the root to the furthest leaf

![img](https://cdn.slidemodel.com/wp-content/uploads/2013/09/1144-tree-diagram-wide-1.jpg)


Traversals

Traversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:

Depth First
Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. Here are three methods for depth first traversal:

Pre-order: root >> left >> right
In-order: left >> root >> right
Post-order: left >> right >> root


Breadth First
Breadth-first search (BFS) is an algorithm for searching a tree data structure for a node that satisfies a given property. It starts at the tree root and explores all nodes at the present depth prior to moving on to the nodes at the next depth level. Extra memory, usually a queue, is needed to keep track of the child nodes that were encountered but not yet explored.

Binary Tree Vs K-ary Trees
A binary tree for which the root node has no right child, can be viewed as a general tree, and any binary tree can be viewed as a collection (forest) of general trees. A K-ary tree is a tree in which no node can have more than K children.


K-ary Trees
The K-ary tree is a rooted tree, where each node can hold at most k number of children. ... If the value of k is 2, then this is known as binary tree. The binary tree, or ternary trees are some specialized k-ary trees. So k-ary trees re generalized

Breadth First Traversal
Traversing a K-ary tree requires a similar approach to the breadth first traversal. We are still pushing nodes into a queue, but we are now moving down a list of children of length k, instead of checking for the presence of a left and a right child.

Big O
The Big O time complexity for inserting a new node is O(n). Searching for a specific node will also be O(n). Because of the lack of organizational structure in a Binary Tree, the worst case for most operations will involve traversing the entire tree. If we assume that a tree has n nodes, then in the worst case we will have to look at n items, hence the O(n) complexity.

A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

Searching a BST
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.


