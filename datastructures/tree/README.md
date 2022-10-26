# Tree in Data Structure

Here is a simple defination of the tree Data Structure from [geeksforgeeks](https://www.geeksforgeeks.org/introduction-to-tree-data-structure-and-algorithm-tutorials/).

> A tree is non-linear and a hierarchical data structure consisting of a collection of nodes such that each node of the tree stores a value and a list of references to other nodes (the “children”).

## Anatomy of tree visually

<!-- TODO: Add image here: https://www.geeksforgeeks.org/introduction-to-tree-data-structure-and-algorithm-tutorials -->

## Terminologies

1. **Root node:** The node at the top of the tree is known as root node.
2. **Parent Node:** Every node (excluding a root) in a tree is connected by a directed edge from exactly one other node. This node is called a parent node.
3. **Levels:** Each step from top to bottom is called as level of tree.
4. **Child Node:** The node which is immediate successor of a node is called the child node.
5. **Siblings:** Child node with same parents under same level.
6. **Leaf node or External node:** Node with no child node.
7. **Subtree:** Any node of the tree along with its descendant.

## Properties of tree

1. **Number of edges:** An edge can be defined as the connection between two nodes. If a tree has N nodes then it will have (N-1) edges. There is only one path from each node to any other node of the tree.
2. **Depth of a node:** The depth of a node is defined as the length of the path from the root to that node. Each edge adds 1 unit of length to the path. So, it can also be defined as the number of edges in the path from the root of the tree to the node.
3. **Height of a node:** The height of a node can be defined as the length of the longest path from the node to a leaf node of the tree.
4. **Height of the Tree:** The height of a tree is the length of the longest path from the root of the tree to a leaf node of the tree.
5. **Degree of a Node:** The total count of subtrees attached to that node is called the degree of the node. The degree of a leaf node must be 0. The degree of a tree is the maximum degree of a node among all the nodes in the tree.

## Operation of tree

1. **Create:** create a tree in data structure.
2. **Insert:** Inserts data in a tree.
3. **Search:** Searches specific data  in a tree to check it is present or not.
4. **Preorder Traversal** perform Traveling a tree in a pre-order manner in data structure .
5. **In order Traversal:** perform Traveling a tree in an in-order manner.
6. **Post order Traversal:** perform Traveling a tree in a post-order manner.
