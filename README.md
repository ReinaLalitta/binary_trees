# Binary Trees in C

This repository contains implementations of various binary tree data structures and algorithms in C. It includes functions for creating, manipulating, and traversing binary trees.

## Overview

The project covers the following topics:

- Binary trees
- Binary search trees (BST)
- AVL trees
- Max Binary Heap

## Contents

- `binary_tree_print.c`: A utility function for printing binary trees in a visually appealing manner.
- `binary_trees.h`: Header file containing definitions and function prototypes for all binary tree-related operations.

## Data Structures

The primary data structure used throughout the project is:

```c
typedef struct binary_tree_s {
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
} binary_tree_t;
