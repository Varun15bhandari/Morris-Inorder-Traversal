# Morris-Inorder-Traversal
why this traversal is used? there are many Traversals ?
this algo uses the space complexity of O(1) and TC=O(n) 
and this algo uses the threads for linking temporary nodes that overrides the stack and recursive solns;
We have to taking of 3 main primary scenarios as follows:
The traversal encompasses three primary scenarios: nodes without a left child, nodes with a left child where the in-order predecessor does not have a right child, and nodes with a left child where the right child of the in-order predecessor points back to the current node. Addressing these scenarios allows for an efficient and accurate in-order traversal while preserving the tree's structure.
