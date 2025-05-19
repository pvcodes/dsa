# Binary Tree

### TERMINOLOGIES

-   **Node**: A structure that contains data and reference/address (pointer) to another child node
-   **Root**: The topmost node of any tree from where the tree starts, also know as _root node_.
-   **Leaf Node**: The node that does not have any _children nodes_.
-   **Ancestors**: All the nodes, on the way from a particular node to the root node.
-   **Level**: The number of parent nodes corresponding to a given a node of the tree. i.e. _for root node the level is 0_ and _for first childrens of the root node, the level us 1_ and so on.
-   **Height of a tree**: The maximum number of edges between the root node and any leaf node in the tree

### Types of Binary Tree

-   **Full Binary Tree**: Every node in the tree having either _0_ or _2_ children.

-   **Complete Binary Tree**:

    -   All the levels are completely filled except the last level
    -   The last level has all nodes left as possible

-   **Perfect Binary Tree**:

    -   All leaf nodes are at the same levels.

-   **Balanced Binary Tree**:
    -   Height of the tree is at max `log(n)` where n is the number of nodes.

-   **Degenerate Binary Tree** (*Skew Binary Tree*):
    -   Every node has only 1 child node.
    -   Looking like a linked list.

