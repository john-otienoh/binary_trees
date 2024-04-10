# 0x1D. C - Binary trees
C | Group project | Algorithm | Data structure
- | ------------- | --------- | --------------
## General
1. What is a binary tree
1. What is the difference between a binary tree and a Binary Search Tree
1. What is the possible gain in terms of time complexity compared to linked lists
1. What are the depth, the height, the size of a binary tree
1. What are the different traversal methods to go through a binary tree
1. What is a complete, a full, a perfect, a balanced binary tree.

## More Info
__Data structures__
Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

**Basic Binary Tree**
```
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```
**Binary Search Tree**
```
typedef struct binary_tree_s bst_t;
```
**AVL Tree**
```
typedef struct binary_tree_s avl_t;
```
**Max Binary Heap**
```
typedef struct binary_tree_s heap_t;
```
**Print function** - This function is used only for visualization purposes.
To match the examples in the tasks, you are given this [function](https://github.com/alx-tools/0x1C.c).
