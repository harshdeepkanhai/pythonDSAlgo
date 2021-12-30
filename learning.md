## 22. Tree/Binary Tree

### 1. What is a Tree ?
--> A tree is a nonlinear data structure with hierarchical relationships between its elements without having any cycle, it is basically reversed from a real life tree.

Properties:
 - Represent hierarchical data
 - Each node has two components: data and a link to its sub category
 - Base category and sub categories under it

Tree Properties:
 - Represent hierarchical data
 - Each node has two components: data and a link to its sub category
 - Base category and sub categories under it

### 2. Why a Tree ?
- Quicker and Easier access to the data
- Store hierarchical data, like folder structure, organization structure, XML/HTML data.
- There are many different types of data structures which performs better in various situations
    - Binary Search Tree, AVL, Red Black Tree, Trie

### 3. Tree Terminology
- **Root**: yop node without parent
- **Edge**: a link between parent and child
- **Leaf**: a node which does not have children
- **Sibling**: children of same parent
- **Ancestor**: parent, grandparent, great grandparent of a node
- **Depth of node**: a length of the path from root to node
- **Height of node**: a length of the path from the node to the deepest node
- **Depth of tree**: depth of root node (Depth of tree is always 0)
- **Height of tree**: height of root node (number of edge from root to the deepest node)

### 4. How to create basic tree in Python
    `tree\CreateTree.py`