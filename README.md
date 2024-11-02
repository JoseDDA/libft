# Libft

- [Libft](#libft)
  - [Overview](#overview)
  - [Project Structure](#project-structure)
  - [Functions](#functions)
    - [Part 1: Standard Library Functions](#part-1-standard-library-functions)
    - [Part 2: Additional Functions](#part-2-additional-functions)
    - [Bonus Part: Linked List Functions](#bonus-part-linked-list-functions)
  - [Compilation](#compilation)
  - [Usage](#usage)

## Overview

The **Libft** project is a personal library of essential C functions. This library includes implementations of commonly used standard library functions, as well as additional functions to handle strings, memory management, and linked lists. This project provides a solid foundation in C programming and serves as a useful toolkit for future projects.

## Project Structure

- **libft.a**: The compiled static library containing all functions.
- **Makefile**: Automates the compilation process with standard rules (`all`, `clean`, `fclean`, `re`).
- **libft.h**: The header file containing function prototypes and necessary definitions.
- **ft\_\*.c**: Source files with individual function implementations.

## Functions

### Part 1: Standard Library Functions

The first part of **Libft** replicates a series of functions from the standard C library (libc), such as `ft_strlen`, `ft_memset`, `ft_atoi`, etc., with the `ft_` prefix.

### Part 2: Additional Functions

This part includes more complex functions like `ft_substr`, `ft_strjoin`, `ft_itoa`, and `ft_split`, which facilitate string manipulation, memory allocation, and conversions.

### Bonus Part: Linked List Functions

If the mandatory part is completed perfectly, a bonus section adds support for linked list functions, such as:

- **ft_lstnew**: Creates a new list node.
- **ft_lstadd_front** and **ft_lstadd_back**: Add nodes to the front or back of the list.
- **ft_lstsize** and **ft_lstlast**: Retrieve the size and last element of the list.
- **ft_lstdelone** and **ft_lstclear**: Delete single or multiple nodes.
- **ft_lstiter** and **ft_lstmap**: Apply functions to each node or create a new list with modified content.

## Compilation

To compile the library, run:

```bash
make
```

This will produce `libft.a`, which can be linked to other C projects.

## Usage

Include `libft.h` in your C files and link `libft.a` during compilation:

```bash
gcc my_program.c -L. -lft -o my_program
```
