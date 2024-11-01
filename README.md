# LIBFT


![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Language](https://img.shields.io/badge/language-C-blue)

> **Libft** is my first project at 42 School, where I created a custom C library. This project includes essential functions from the standard library and additional utilities that I will use in future projects. The objective is to deepen my knowledge of C, memory management, and function handling.

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Functions](#functions)
- [Compilation](#compilation)
- [Usage](#usage)

---

## About

This project includes:
- **Standard functions**: Recreating basic C library functions.
- **Memory functions**: Functions to manage memory allocation and manipulation.
- **Extra utilities**: Additional string manipulation functions and other utilities.
- **Bonus functions**: Handling linked lists and other data structures.

## Features

| Function Group         | Description                                               | Example                  |
|------------------------|-----------------------------------------------------------|--------------------------|
| **String Manipulation**| Manipulates and analyzes strings in various ways.         | `ft_strlen`, `ft_strcpy` |
| **Memory Management**  | Handles memory allocation, deallocation, and copying.     | `ft_memset`, `ft_calloc` |
| **Character Checks**   | Checks properties of characters (e.g., `isalnum`, `isdigit`). | `ft_isalpha`, `ft_isdigit` |
| **Linked Lists**       | Implements functions for linked list management.          | `ft_lstadd`, `ft_lstdelone` |

---

## Functions

Here’s a list of all the functions included in **Libft**:

| **Function**         | **Function**         | **Function**         |
|----------------------|----------------------|----------------------|
| `ft_atoi.c`          | `ft_bzero.c`         | `ft_calloc.c`        |
| `ft_isalnum.c`       | `ft_isalpha.c`       | `ft_isascii.c`       |
| `ft_isdigit.c`       | `ft_isprint.c`       | `ft_itoa.c`          |
| `ft_lstadd_back.c`   | `ft_lstadd_front.c`  | `ft_lstclear.c`      |
| `ft_lstdelone.c`     | `ft_lstiter.c`       | `ft_lstlast.c`       |
| `ft_lstmap.c`        | `ft_lstnew.c`        | `ft_lstsize.c`       |
| `ft_memchr.c`        | `ft_memcmp.c`        | `ft_memcpy.c`        |
| `ft_memmove.c`       | `ft_memset.c`        | `ft_putchar_fd.c`    |
| `ft_putendl_fd.c`    | `ft_putnbr_fd.c`     | `ft_putstr_fd.c`     |
| `ft_split.c`         | `ft_strchr.c`        | `ft_strdup.c`        |
| `ft_striteri.c`      | `ft_strjoin.c`       | `ft_strlcat.c`       |
| `ft_strlcpy.c`       | `ft_strlen.c`        | `ft_strmapi.c`       |
| `ft_strncmp.c`       | `ft_strnstr.c`       | `ft_strrchr.c`       |
| `ft_strtrim.c`       | `ft_substr.c`        | `ft_tolower.c`       |
| `ft_toupper.c`       | `libft.h`            |                      |

---

## Compilation

To compile the library, run the following command:

```bash
make


