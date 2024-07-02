# 0x1D. C - BINARY TREES

This Repository is home to all files required for learning of foundational principles related to Binary Trees and Binary Search Trees as well as completion of the '0x1D. C - Binary trees' Project by ALX Africa to its Software Program.

## REQUIREMENTS

### GENERAL

	->	Allowed editors:
			vi, vim, emacs
	->	All files will be compiled on:
			Ubuntu 20.04 LTS using gcc,
				using the options:
					-Wall -Werror -Wextra -pedantic -std=gnu89
	->	All files should end with a new line
	->	A README.md file, at the root of the folder of the project, is mandatory
	->	Code should use the Betty style. It will be checked using:
			betty-style.pl and
			betty-doc.pl
	->	Use of global variables is not allowed
	->	No more than 5 functions per file
	->	Use of the standard library is not allowed
	->	The prototypes of all functions should be included in header file called:
			binary_trees.h
	->	All header files should be include guarded

## MORE INFO

### DATA STRUCTURES
The following data structures and types are in use for binary trees.

### BASIC BINARY TREE

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
	
### BINARY SEARCH TREE
	typedef struct binary_tree_s bst_t;

### AVL TREE
	typedef struct binary_tree_s avl_t;
### MAX BINARY HEAP
	typedef struct binary_tree_s heap_t;
