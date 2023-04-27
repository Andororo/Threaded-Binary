# Threaded-Binary
A threaded binary tree is a binary tree in which all null pointers are replaced with references to other nodes in the tree. The threads are created by setting a specific pointer in a node to either the inorder predecessor or inorder successor of that node. This allows for efficient traversal of the tree without requiring recursion or a stack, as in the case of a normal binary tree.

In a threaded binary tree, each node has either zero, one, or two children. The left and right children of a node can be either a regular child pointer or a thread. If the left child pointer is a thread, it points to the inorder predecessor of the node, while if the right child pointer is a thread, it points to the inorder successor of the node.
