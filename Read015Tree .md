# Trees

The topmost node is called root of the tree. The elements that are directly under an element are called its children. The element directly above something is called its parent. For example, ‘a’ is a child of ‘f’, and ‘f’ is the parent of ‘a’. Finally, elements with no children are called leaves.

## Why Trees?
- One reason to use trees might be because you want to store information that naturally forms a hierarchy.

- Trees provide moderate access/search (quicker than Linked List and slower than arrays).

- Trees provide moderate insertion/deletion (quicker than Arrays and slower than Unordered Linked Lists).

- Like Linked Lists and unlike Arrays, Trees don’t have an upper limit on number of nodes as nodes are linked using pointers.

## Terminiology

- Node: component which may contain it’s own values, and references to other nodes
- Root: node at the beginning of the tree
- K: number that specifies the maximum number of children any node may have in a k-ary tree (in a binary tree, k = 2)
- Left: reference to one child node, in a binary tree
- Right: reference to the other child node, in a binary tree
- Edge: link between a parent and child node
- Leaf: node that does not have any children
- Height: number of edges from the root to the furthest leaf

## Binary Trees versus K-ary Trees
Trees can have any number of children per node, but Binary Trees restrict the number of children to two
If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree
K refers to the maximum number of children that each Node is able to have
Adding a Node
Since there are no structural rules for where nodes go in binary trees, it doesn't matter where a new node gets placed
One strategy for adding a new node to a binary tree is to fill all "child" spots from the top down
When you want to place a node in a specific location, you need to reference both the new node to create, and the parent node upon which the child is attached to

## Binary Search Trees
Type of tree that does have some structure
Nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right

