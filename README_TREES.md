# Trees Cheat Sheet


### Tree Basics

A tree is a hierarchical data structure composed of nodes.
A tree has one node called the root, from which all other nodes are descendants.
Nodes in a tree are connected by edges.
Nodes in a tree can have children (nodes that are one level below) and parents (nodes that are one level above).
Nodes with the same parent are called siblings.
Nodes with no children are called leaves.
The depth of a node is the number of edges from the root to that node.
The height of a tree is the maximum depth of any node in the tree.

---

### Types of Trees

Binary Tree: A tree in which each node has at most two children, referred to as the left child and the right child.

Binary Search Tree (BST): A binary tree where each node's left child is less than or equal to the node, and the right child is greater than the node.

Balanced Tree: A tree where the depth of the left and right subtrees of every node differ by at most one.

Complete Binary Tree: A binary tree in which every level, except possibly the last, is completely filled, and all nodes are as left as possible.

Full Binary Tree: A binary tree in which every node has either 0 or 2 children.

Perfect Binary Tree: A binary tree in which all interior nodes have two children, and all leaves have the same depth.

---

### Tree Traversal

Tree traversal is the process of visiting all nodes in a tree. There are three common methods:

a. Inorder Traversal: Visit the left subtree, then the current node, then the right subtree.

b. Preorder Traversal: Visit the current node, then the left subtree, then the right subtree.

c. Postorder Traversal: Visit the left subtree, then the right subtree, then the current node.


---

### Tree Operations

Insertion: Adding a new node to the tree.
Deletion: Removing a node from the tree.
Searching: Finding a specific node in the tree.
Traversal: Visiting all nodes in a specific order.